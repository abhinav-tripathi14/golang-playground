Vagrant.configure("2") do |config|
  config.vm.provider "virtualbox"
  config.vm.box = "abhinav-YFPXV0K6KK"
  config.vm.provision "shell", path: "https://raw.githubusercontent.com/kikitux/curl-bash/master/provision/go.sh"
  config.vm.provision "shell", path: "scripts/provision-tf.sh"
end
