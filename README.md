
# Terraform + Ansible NGINX Deployment (AWS)

## Overview
This project demonstrates provisioning AWS EC2 instances using Terraform and
automating web server configuration using Ansible.

## Architecture
- Terraform provisions EC2 instances
- One instance acts as the Ansible control node
- Ansible installs and configures NGINX on multiple web servers
- SSH key-based authentication is used for secure access

## Tools Used
- AWS EC2
- Terraform
- Ansible
- Amazon Linux
- NGINX
- SSH
- Bash

## Screenshots

### EC2 Instances Running
![EC2 Instances](screenshots/ec2-instances.png)

### Ansible Playbook Execution
![Ansible Run](screenshots/ansible-playbook-run.png)

### NGINX Service Running
![NGINX Status](screenshots/nginx-running.png)

### NGINX Accessible in Browser
![NGINX Browser](screenshots/browser-nginx.png)

