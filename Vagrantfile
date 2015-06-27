
# map your host data to vm
mount_path = { host: "/Users/zavalit/textmining/",
			 	 vm: "/opt"}


Vagrant.configure("2") do |config|

  config.vm.box = "ubuntu/trusty64"

  config.vm.synced_folder mount_path[:host], mount_path[:vm]

  config.vm.provision :ansible do |provision|

  	provision.playbook = "provisioning/playbook.yml"

  end



end
