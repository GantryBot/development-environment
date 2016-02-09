Vagrant.configure(2) do |config|
  config.vm.box = "hashicorp/precise64"
  config.vm.network "private_network", ip: "10.10.10.10"
  config.vm.provision :shell, :path => "provision/installation.sh"
end
