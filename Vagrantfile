VAGRANTFILE_API_VERSION = "2"

Vagrant.configure("2") do |config|  
config.vm.box = "hashicorp/bionic64"

  config.vm.define :db do |db_config|
    db_config.vm.network :private_network, :ip => "192.168.33.10"
  end

  config.vm.define :web do |web_config|
    web_config.vm.network :private_network, :ip => "192.168.33.12"
  end

end
