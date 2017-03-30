# Ansible Project/Playbook

This play book does the following:

  - Spins up three aws mirco instances in EU
  - Two instances have nginx install on them and started
  - One instance has HAProxy installed and started
  - The playbook updates the haproxy.cfg file to add in the nginx servers as backend nodes
  - The playbook enables haproxy to run.
  


### Installation

Project requires 
  - [Ansible](https://www.ansible.com/) 

 
To run the play book
```sh
$ cd ansible_project
$ ansible-playbook -vvv provision-ec2.yml
```

