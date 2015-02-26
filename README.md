# lab-zfs

A test lab for deployment the zfs system at home

by Jing.

### Requirement
1. VirtualBox
2. Vagrant
	vagrant box add ubuntu/trusty64
3. puppet
	- puppet module install puppetlabs-apt

### Usage:
1. [server] vagrant up && vagrant ssh
2. [vm1] vagrant up && vagrant ssh

### Resource:
1. admin: provide dns server
2. vm1: the lab
   /dev/sdb: 500G
   /dev/sdc: 500G
   /dev/sdd: 500G
   /dev/sde: 500G

