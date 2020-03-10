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
