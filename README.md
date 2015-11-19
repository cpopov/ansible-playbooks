# Ansible-playbooks
Personal collection of Ansible playbooks

Roles:

* ec2
* httpd (Apache)

Playbooks:

* create_webserver_centos_ec2 - creates ec2 instances with Centos 7 and provisions Apache server

Run with:
```
ansible-playbook create_webserver_centos_ec2.yml -e "keypair={{your key pair}} vpc_subnet_id={{your subnet id}}"
```