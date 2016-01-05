#!/usr/bin/env ruby

Vagrant.configure(2) do |config|
  config.vm.box = "bento/centos-7.1"
  config.vm.provision "shell", inline: "/vagrant/bin/provision"
end
