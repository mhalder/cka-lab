## Vagrant Setup

### Comment
As of v1.17.1 the minimum (as in barely works) size for VirtualBox is:
* 3 vCPU, 4G RAM, 5G HDD
* 1 vCPU, 2G RAM, 5G HDD

Since this is more than my MacBook can provide, VirtualBox is just using an example playbook and the cluster will be deployed on GCE instead.

### Prerequisistes
Install Vagrant vbguest Plugin
```bash
vagrant plugin install vagrant-vbguest
```

Start VMs
```bash
vagrant up
```

Provision VMs
```bash
vagrant provision
```