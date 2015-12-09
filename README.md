# ansible-buildbot
Ansible deployment of buildbot cluster on Ubuntu 14.04

## Vagrant test :
*For Vagrant test environment, install Vagrant, Ansible and Virtualbox*
*Vagrant uses "hostmanager" plugin. Before running, install with: `vagrant plugin install vagrant-hostmanager`*

To spin up two buildbot  VMs (master and slave) , run:

`vagrant up`

Buildbot interface will then be located at:

http://buildbot1.internal.tld:8010

username: buildbot pass: password

edit `inventory/group_vars/all.yml` to change software versions and passwords

