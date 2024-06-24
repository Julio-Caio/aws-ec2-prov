# AWS EC2 Instance Provisioning Project

This repository contains scripts and configurations for automated provisioning of AWS EC2 instances.

## Features

- Initial setup of development environment.
- Scripts to provision EC2 instances using Ansible.
- Automation of server configuration tasks.

## How to Use

1. **Setting Up the Environment:**
   - Clone this repository:
     ```bash
     git clone https://github.com/Julio-Caio/aws-ec2-instance-provisioning.git
     ```
   
2. **Configuring Variables:**
   - Before running the playbook, navigate to the `vars` folder:
     ```bash
     cd vars
     ```
   - Configure the necessary variables in the `main.yml` file according to your needs.

3. **Provisioning EC2 Instances:**
   - Ensure you have AWS credentials configured locally.
   - Execute the provisioning scripts using Ansible:
     ```bash
     cd ..
     ansible-playbook tasks/main.yml
     ```
   
4. **Contributions:**
   - Contributions are welcome! Feel free to submit pull requests.

## Requirements

- Python 3.x
- Ansible 2.x
- AWS account with appropriate IAM access for EC2 instance provisioning.
