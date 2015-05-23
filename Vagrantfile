# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant.configure("2") do |config|
  config.vm.box = "janbarta/ubuntu-mongo-node-nginx"
  config.vm.provision :shell, :path => "start_server.sh", run: "always", privileged: false

  config.vm.network "forwarded_port", guest: 8081, host: 8083
    # CHANGE THE PATH BELOW TO YOUR WORKSPACE DIRECTORY
    config.vm.synced_folder "/Users/janbarta/Documents/workspace/tacho/", "/srv/www"
    config.vm.provider "virtualbox" do |v|
        v.memory = 2048
    end
end