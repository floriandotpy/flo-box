# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant.configure("2") do |config|

  config.vm.box = "scotch/box"
  config.vm.network "private_network", ip: "10.20.30.40"
  config.vm.hostname = "scotchbox"
  config.vm.synced_folder "/Users/flo/htdocs", "/var/www/public", :mount_options => ["dmode=777", "fmode=666"]

end
