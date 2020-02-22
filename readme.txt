# Ansible Commands

sudo apt-get install ansible

ansible -i hosts ocean --list-hosts

ansible -i hosts ocean -m ping

ansible-playbook -i hosts -C first.yml
ansible-playbook -i hosts first.yml