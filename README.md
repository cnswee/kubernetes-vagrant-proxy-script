# Environment

vagrant version: 2.2.19

virtualbox version: 6.1.32



# Preparation

sudo mkdir /etc/vbox 

sudo cp networks.conf /etc/vbox/networks.conf

cp VagrantfileProxy ~/.vagrant.d/Vagrantfile

vagrant plugin install vagrant-proxyconf



# Logs

Some bugs had been fixed and some code was updated for users who have to use proxy.

After install and configure vagrant-proxyconf, Use 'vagrant up' to set up.

*The node may fail to join because the cni is not ready, if so try to join manually after it is ready.
