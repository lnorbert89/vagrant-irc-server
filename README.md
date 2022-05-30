# vagrant-irc-server

Automated Vagrant installer for VirtualBox Virtual Machine with Ubuntu LTS and running an InspIRCd service on it.

Put the Vagrantfile and inspircd.conf to the same folder, wich will be your VM-s folder.
Edit the inspircd.conf configuration file.
If you change the default port in the inspircd.conf, be sure you changed the forwarded port in the Vagrantfile to the same.

Run ```vagrant up``` command from the same folder in your CLI.


