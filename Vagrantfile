Vagrant.configure("2") do |config|
  config.vm.box = "ubuntu/bionic64"  # Use your preferred OS
  config.vm.network "private_network", type: "dhcp"

  config.vm.provider "virtualbox" do |vb|
    vb.memory = "2048" # Allocate 2GB RAM
    vb.cpus = 2        # Allocate 2 CPU cores
  end
end #vm deploy in virtual box
