Proof of concept bootstrapping and provision VMs using cloud-init on KVM

It uses 'default' libvirt network with dhcp server to obtain connectivity on first interface.

Than if need more network interfaces, add secondary using virsh and configure it manually inside VM.

