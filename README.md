# ansible-financio
Ansible playbook to install financio

###### Prerequisite

- Ansible 2.0.0.2*

- Miniconda* 

- open SSH connection to remote host  (root access)

*installed on host that running ansible script


###### Supported platform

- Ubuntu 14.04 

######## Adding target remote host ip

- Add target host ip in hosts file


###### Default script

ansible-playbook ~/financio-installer/main.yml -i ~/financio-installer/hosts --ask-pass -vvvv
