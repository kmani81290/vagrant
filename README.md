to create with bridged network

Vagrant.configure("2") do |config|
  config.vm.box = "chrislentz/trusty64-lamp"
  config.vm.network "public_network", bridge: "en1: Wi-Fi (AirPort)"
end
