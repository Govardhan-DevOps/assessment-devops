# assessment-devops
This repo is for Assessment from Pyramid Consulting

# 1. copy-public-ssh-key.yml - This file is used to copy the public SSH key in remote machines.

# How to run:- 
 
# ansible-playbook copy.yml --extra-vars='pubkey="~/.ssh/id_rsa.pub"' 

# 2. install-ssh-keys.yml - This file is used to install the SSH keys into remote machine
ansible-playbook copy.yml -i hosts install-ssh-keys.yml 
