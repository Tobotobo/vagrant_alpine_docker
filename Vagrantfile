# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant.configure("2") do |config|
    config.vm.box = "ubuntu/jammy64"
    config.vm.box_version = "20240223.0.0"

    config.vm.network "private_network", ip: "192.168.33.10"
    # config.vm.network "private_network", type: "dhcp"
    
    config.vm.provision "docker"

    # config.vm.provision "docker" do |d|
    #   # 
    # end
  end