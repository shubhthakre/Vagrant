Vagrant - Getting Started | Install > Setup > Use

Step 1 - Install Vagrant: https://www.vagrantup.com/downloads

Check if Vagrant is installed by running \`vagrant --version\`.

Step 2 - Select a VM Provider. Vagrant has direct support for VirtualBox, Hyper-V, Docker.

Install VirtualBox: https://www.virtualbox.org/wiki/Downloads

Step 3 - Create a new folder for Vagrant project.

Step 4 - On terminal or command line, navigate to the folder and initiate Vagrant project:

\`vagrant init\`

Step 5 - Choose a box to use: https://app.vagrantup.com/boxes/search

A box is a pre-configured virtual machine image that you can use as a starting point for your virtual machine.

Step 6 - Add configuration of the box in Vagrantfile:

\`config.vm.box = "ubuntu/bionic64"\`

Step 7 - Start virtual machine using command \`vagrant up\`.
