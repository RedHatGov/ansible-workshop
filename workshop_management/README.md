# bootstrap-tower.yml
This play configures Ansible Tower in AWS to be used in a guided workshop.  
It creates the following configurations:
* organizations
* teams
* users (student1-10)
* projects
* inventories


### Vars
* aws_region:
* aws_credential:
* lab_user_credential:
* lab_admin_credentials:
* organizations:
* teams:
* projects:
* users:

### Dependencies
* tower-cli must be installed on the ansible master
* tower-cli must be configured to connect to the target host (Tower instance)
