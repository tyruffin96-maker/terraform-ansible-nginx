
# Terraform + Ansible NGINX Deployment (AWS)

## 📌 Overview
This project demonstrates infrastructure provisioning with Terraform and configuration management using Ansible. Terraform provisions an EC2 instance, and Ansible installs and configures NGINX on the server.


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

## 🧪 Commands Executed

```bash
terraform init
terraform apply

ansible-playbook -i inventory nginx.yml

