Vagrant.configure("2") do |config|

  config.vm.define "projetoubuntu" do |projetoubuntu|
    projetoubuntu.vm.box = "ubuntu/focal64"
    projetoubuntu.vm.hostname = "projetoubuntu"
    projetoubuntu.vm.network "public_network", bridge: "Intel(R) Wi-Fi 6 AX201 160MHz"
    projetoubuntu.vm.provider "virtualbox" do |vb|
      vb.memory = "1024"
      vb.cpus = 1
      vb.name = "projetoubuntu"
    end
    projetoubuntu.vm.synced_folder "C:\\Users\\Davidson\\Documents\\vagrant-ubuntu", "/var/www/html"
  end

end