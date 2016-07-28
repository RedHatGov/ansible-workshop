## Role: manage_account
- Adds to removes a list of user accounts to a RHEL host

### Tasks
- Add or remove user account
- chage to 0 for force passwd reset upon first login

### group_vars
users, group_name, user_password

### extra_vars
- user_state: "\<present \| absent\>"
