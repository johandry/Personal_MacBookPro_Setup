# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant.configure("2") do |config|
  config.vm.box = "jhcook/macos-sierra"

  # config.vm.box_check_update = false
  # config.vm.network "forwarded_port", guest: 80, host: 8080

  config.vm.network "private_network", ip: "192.168.10.100"
  config.vm.network "public_network", ip: "192.168.20.200", bridge: "en0: Wi-Fi (AirPort)"

  # config.vm.network "private_network", ip: "192.168.33.10"
  # config.vm.network "public_network"

  config.vm.synced_folder ".", "/Users/vagrant/OS_Setup", type: "nfs"
end
