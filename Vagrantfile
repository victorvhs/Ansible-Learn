Vagrant.configure("2") do |config|

    config.vm.box = "ubuntu/trusty64"
    config.vm.provider "virtualbox" do |v|
    v.memory = 512
    end

    config.vm.define "wp" do |m|
      m.vm.network "private_network", ip:"172.17.177.39"
    end
end
