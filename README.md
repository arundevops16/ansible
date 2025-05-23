# Ansible playbook usercreation.yml

### Prerequisite:
* Ansible should be installed on conrol machine
* contorl machine and nodes should have ssh access
* ssh keys needs to place on which user ansible control machine login to remote machines. 
* pub key of conrtol machine should be added in user authorized_keys of remote machine. 
* Update IP's in host file (inventory-hosts)
### #Commands:

`ansible-playbook -i inventory-hosts -e user_name=arun usermanagement.yml`

`ansible-playbook -i inventory-hosts -e user_name=arun deleteuser.yml`


