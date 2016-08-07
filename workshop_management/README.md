# create_workshop_users
This play creates Ansible lab users


### Extra Vars
 - user_file: path to csv file with user names
   format:
   ```
   firstname,lastname,email
   John,Smith,jsmith@company.com
   ```
 - org: name or org to be associated with

## Role: add_user
- Creates or removes specified user accounts on a RHEL host
