# -*- mode: ruby -*-
# vi: set ft=ruby :

# All Vagrant configuration is done below. The "2" in Vagrant.configure
# configures the configuration version (we support older styles for
# backwards compatibility). Please don't change it unless you know what
# you're doing.
Vagrant.configure(2) do |config|

  
  config.vm.box = "ubuntu-trusty-lemp"
  config.vm.hostname = "ubuntu-trusty-lemp"
  
  # config.cache.auto_detect = true
  # config.cache.scope = :machine

  config.vm.network :public_network, ip: "192.168.1.33"
  config.vm.network :private_network, ip: "33.33.33.33"


  config.vm.provider :virtualbox do |vb|
    vb.customize ["modifyvm", :id, "--memory", "1024"]
  end

  # config.vm.synced_folder "./files/web_app", "/var/www/web_app", id: "vagrant-root", :owner => "vagrant", :group => "www-data, :mount_options => ["dmode=777", "fmode=666"]"


end
