# workshop_play 
This play performs various admin tasks including creating accounts, installing packages, change passwords, subscribe to satellite, and validate /etc/resolv.con

### group_vars
users, group_name, user_password, package_list

### Extra Vars
 - user_state: "\<present \| absent\>"
 - package_state: "\<present \| absent\>"

## Role: manage_account

### Tasks
- Add or remove user account
- chage to 0 for force passwd reset upon first login

## Role: manage_packages

### Tasks 
- install or remove yum packages

## Role: change_password

## Role: sub_to_sat

## Role: dns_config


