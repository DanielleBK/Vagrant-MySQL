Vagrant.configure("2") do |config|
  config.vm.box = "anhdht/mysql"
  config.vm.hostname = "MBA"
  config.vm.network "forwarded_port", guest: 3306, host: 3306
  config.vm.network "private_network", ip: "192.168.33.10"
  config.vm.provider "virtualbox" do |vb|
    #vb.gui = true
    vb.memory = "1024"
  end
end
