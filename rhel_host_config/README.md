# rhel_host_config
This play adds or removes user accounts and adds or removes yum packages

### group_vars
users, group_name, user_password, package_list

### Extra Vars
 - user_state: <present | absent>
 - package_state: <present | absent>

## Role: manage_account

### Tasks
- Add or remove user account
- chage to 0 for force passwd reset upon first login

## Role: manage_packages

### Tasks 
- install or remove yum packages


