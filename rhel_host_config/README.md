# rhel_host_config
This play performs a number of basic RHEL tasks for user, password, package management, etc.

## Role: host_common

### Extra Vars
 - user_state: "\<present \| absent\>"
 - users:
 - package_state: "\<present \| absent\>"
 - packages:
 - password_users:

### Tasks
- Add or remove user account(s)
- chage to 0 for force passwd reset upon first login
- Add or remove yum packages
- Update user's password
- Install /etc/resolv.conf from template
- Install /etc/motd from template

### Templates
 - motd.j2
 - resolv.conf.j2
