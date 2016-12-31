## Mini Project ##

This is an example mini project using Ansible to create an AWS security group and new EC2 instance passing data from one role to the next role.

The Vagrant file is included to test Ansible locally without having to create EC2 instances:
* Vagrant up (this also runs the serverspec tests)
* Vagrant provision will also run the serverspec tests)
* curl localhost:8080 (test the setup)

To run this project simply do the following:
* Install Ansible (http://docs.ansible.com/ansible/intro_installation.html)
* Rename the vars_tmpl.yml file to vars.yml and fill in
* Run the following command "ansible-playbook playbook/ec2_provision.yml"

