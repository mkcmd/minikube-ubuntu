Vagrant.configure("2") do |config|
  config.vm.box = "hashicorp/bionic64"
  config.vm.provision :shell, path: "provision"
  config.vm.provider "virtualbox" do |v|
    v.memory = 4000
    v.cpus = 2
  end
end
