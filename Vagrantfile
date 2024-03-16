Vagrant.configure("2") do |config|
  config.vm.box = "ubuntu/focal64"
  config.vm.synced_folder ".", "/vagrant"
  config.vm.hostname = "single.example.com"
  config.vm.network "private_network", ip: "192.168.56.10"
  config.vm.provider "virtualbox" do |vb|
    vb.name = "single"
    vb.cpus = 2
    vb.memory = 2048
    vb.gui = false
  end
end