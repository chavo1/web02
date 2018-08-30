Vagrant.configure("2") do |config|
  config.vm.box = "chavo1/xenial64base"
  config.vm.box_version = "0.0.1"
  config.vm.hostname = "bananas3"
  config.vm.network "private_network", ip: "192.168.56.56"
  config.vm.provision "shell", path: "scripts/provision.sh"

end
