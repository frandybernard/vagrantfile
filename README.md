# vagrantfile
VagrantFile - Provisioning VM-ubuntu-14.04-Apache

 
- VirtualBox (VirtualBox.org)
- Operating System ISO (https://ubuntu.com/download/server) 
- Vagrant (https://developer.hashicorp.com/vagrant/install?product_intent=vagrant)

PREREQUISITES
- Ubuntu 22.04
- VirtualBox Installed
- Non-root Sudo user privileges

SETTING UP YOUR VAGRANT PROJECT
Once you have the necessary software installed, you can start setting up your project:
1. Create a new directory for your project and navigate into it.
2. Initialize a new Vagrant environment by running: vagrant init.
3. This command creates a Vagrantfile, which is crucial for configuring your environment.

LAUNCH YOUR VM
vagrant up

This command reads your Vagrantfile, downloads the necessary box if it's not already present, and sets up the virtual machine according to your configuration.

ACCESSING YOUR VM
Once the machine is running, you can access it via SSH:
vagrant ssh

This will give you shell access to the virtual machine so you can work on it as if you were logged into a remote server.

HALT, SUSPEND, & DESTROYING YOUR VM
To stop your virtual machine while preserving its state, run:
vagrant halt

If you want to pause your work and resume later, use:
vagrant suspend

To completely remove the virtual machine (destroying all its contents), execute:
vagrant destroy

