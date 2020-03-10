https://www.digitalocean.com/community/cheatsheets/how-to-use-ansible-cheat-sheet-guide

Ansible 
[defaults]
inventory = ./inventory
remote_user = user
ask_pass = false
[privilege_escalation]
become = true
become_method = sudo
become_user = root
become_ask_pass = false


- name: Public key is deployed to managed hosts for Ansible
hosts: all
tasks:
- name: Ensure key is in root's ~/.ssh/authorized_hosts
authorized_key:
user: root
state: present
key: '{{ item }}'
with_file:
- ~/.ssh/id_rsa.pub





