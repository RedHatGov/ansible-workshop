# Role: add_user
- adds users to Tower from user_file

## Requirements
- include_csv
  https://galaxy.ansible.com/detail#/role/6589
- tower-cli config username set to admin user
- tower-cli config password set to admin user password

## Extra Vars
- user_file
  This is the csv file of lab members. it's executed on localhost (the Tower server). The variable is the path to the file on the server.
  format:
   ```
   firstname,lastname,email
   John,Smith,email@email.com
   ```
- default_password: ansibleLab20160808
- organizaiton: lab (this is the default. the org is created ahead of time)
