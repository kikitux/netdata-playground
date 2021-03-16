Vagrant.configure("2") do |config|
  config.vm.box = "hashicorp/bionic64"
  config.vm.network "forwarded_port", guest: 19999, host: 19999
  config.vm.provision "shell",
    path: "https://raw.githubusercontent.com/kikitux/curl-bash/master/provision/netdata.sh"
end
