# build_vm
This play clones an existing KVM guest to a new guest

## Role: clone_vm

### vars
source_vm, target_vm, path, connect

#### Tasks 
- virsh to suspend and resume source VM
- virt-clone to clone an source VM to target VM

## Role: setup_new_vm

### vars
hostname, ipaddr, passwd

