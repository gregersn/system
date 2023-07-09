When doing `vagrant up` on a server, an inventory is created for that machine for ansible use, in `.vagrant/provisioners/ansible/inventory/vagrant_ansible_inventory`


## Ansible

Basic stuff

`ansible all -m gather_facts`

`--become --ask-become-pass`

`ansible-playbook playbooks/webtrees.yml`

