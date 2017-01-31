Vagrant.configure("2") do |config|
	 config.vm.define "box1" do |box1|

         box1.vm.box="ubuntu/trusty64"

         box1.vm.network :forwarded_port, guest: 22, host: 10122, id: "ssh"

 end

  config.vm.define "box2" do |box2|

         box2.vm.box="scotch/box"

         box2.vm.network :forwarded_port, guest: 22, host: 10222, id: "ssh"
 end
end

#This is an edit!
#This is another edit! Mwahahaha!!!
#This is Svetlana's change!
