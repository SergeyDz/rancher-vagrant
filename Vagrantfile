Vagrant.configure("2") do |config|
  config.vm.provider "virtualbox" do |v|
    v.memory = 8024
    v.cpus = 8
  end
  config.vm.box = "ubuntu/xenial64"
  config.vm.network "private_network", type: "dhcp"
  config.vm.provision "shell", path: "setup.sh"
end