
Vagrant.configure("2") do |config|
  config.ssh.insert_key = false
  config.vm.box = "vb-vagrant-centos-6.7.box"
  config.vm.provider "virtualbox" do |vb|
    vb.customize ["modifyvm", :id, "--memory", 1024]
  end
end
