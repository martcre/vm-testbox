# vm-testbox
My VM box playground to learn and test new things.

## Technologies used
- Debian Bullseye
- libvirt
- Qemu
- KVM
- Vagrant
- Ansible
- Docker
- Docker-Compose
- Nginx

## Usage
Start the VM:
```
sudo vagrant up
```
Stop the VM:
```
sudo vagrant halt
```
Remove the VM:
```
sudo vagrant destroy
```
Check status:
```
sudo vagrant status
```
Check status of all VMs:
```
sudo vagrant global-status
```




## Host Setup
Maybe incomplete list of steps:
```
sudo apt install libvirt qemu-kvm libvirt-clients libvirt-daemon-system bridge-utils virtinst libvirt-daemon
vagrant plugin install vagrant-libvirt
```
Setup of Network bridge: https://linuxconfig.org/how-to-use-bridged-networking-with-libvirt-and-kvm
