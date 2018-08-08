# -*- mode: ruby -*-
# vi: set ft=ruby :

# All Vagrant configuration is done below. The "2" in Vagrant.configure
# configures the configuration version (we support older styles for
# backwards compatibility). Please don't change it unless you know what
# you're doing.
Vagrant.configure("2") do |config|
  config.vm.box = "ubuntu/trusty64"
  config.vm.hostname = "lamp-ansible"  
  config.vm.network "private_network", ip: "192.168.33.21"

  config.vm.provider "virtualbox" do |vb|
    vb.memory = "512"
  end
  # shell provisioner to install ansible
#  config.vm.provision "shell", inline: <<-SHELL
#     sudo apt-add-repository ppa:ansible/ansible
#     sudo apt-get update
#     sudo apt-get install -y ansible
#   SHELL
#
  # Ansible Local Provisioner
#  config.vm.provision "ansible_local" do |ansible|
#    ansible.playbook = "site.yml"
#  end

end
