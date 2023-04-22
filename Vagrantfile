Vagrant.configure("2") do |config|
config.vm.define "web03" do |web03|
web03.vm.box = "spox/ubuntu-arm"
web03.vm.network "private_network", ip: "192.168.10.15"
web03.vm.provider "vmware_desktop" do |vmware|
vmware.gui = true
vmware.allowlist_verified = true
end
end
end


