# Ansible Projects
This project includes various Ansible plays, mostly focused on RHEL system administration

# Build_VM
NOTE:  This is work in progress
Build_VM clones an existing KVM guest to a new guest

## Dependencies 
None

## Role = clone_vm

### vars
source_vm, target_vm, path, connect

#### Tasks 
- virsh to suspend and resume source VM
- virt-clone to clone an source VM to target VM

## Role = setup_new_vm

### vars
hostname, ipaddr, passwd

# License
GPLv3
# Author Information
Bill Hirsch bhirsch@redhat.com

