# Ansible playbook usercreation.yml

ansible-playbook -i inventory-hosts -e user_name=arun usermanagement.yml
ansible-playbook -i inventory-hosts -e user_name=arun deleteuser.yml
