# workshop_play 
This play performs various admin tasks including creating accounts, installing packages, change passwords, subscribe to satellite, and validate /etc/resolv.conf

### group_vars
users, group_name, user_password, package_list

### Extra Vars
 - user_state: "\<present \| absent\>"
 - package_state: "\<present \| absent\>"

## Role: manage_account
- Creates or removes specified user accounts on a RHEL host

## Role: manage_packages
- Installs or removes specified yum packages 

## Role: change_password
- changes a password for a specified linux account

## Role: sub_to_sat
- registers a RHEL host with a Satellite server

## Role: dns_config
- Updates /etc/resolv.conf to match a template


