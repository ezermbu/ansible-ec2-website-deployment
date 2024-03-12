# Deploying a Website on Apache Web Servers Across Multiple EC2 Instances



## Introduction
This project aims to guide users through deploying a website on Apache web servers across multiple EC2 instances using Ansible playbooks. By automating the deployment process, this approach eliminates the need for manual installation on each server, streamlining the setup and ensuring consistency.

## Why Ansible?
Regardless of your role or automation goals, Ansible offers value by simplifying IT automation, connecting teams, and freeing up DevOps resources for more strategic tasks. Its straightforward approach to automation reduces repetitive tasks and enhances efficiency within organizations.

## Agenda
This guide will walk through the steps involved in deploying a website across numerous AWS EC2 Instances using Ansible Playbooks. By following this demonstration, users will gain insights into the pivotal role of automation in DevOps and the benefits of adhering to the principle of 'Automate everything'.

## Pre-requisites
- AWS account
- Basic Knowledge of Ansible & Ansible playbooks
- Basic Linux Knowledge

## Project Architecture
![Project Architecture](architecture.png)

## Steps Involved
1. **Step 1**: Creating Security Groups
   - Create security groups for the Ansible Control Master Server and Ansible nodes.
   - Configure inbound rules to allow SSH and HTTP traffic.

2. **Step 2**: Creating the Ansible Master EC2 Instance
   - Launch an EC2 instance for the Ansible master server.
   - Configure network settings and security groups.

3. **Step 3**: Creating SSH Key Pairs
   - Generate SSH key pairs on the Ansible master server.
   - Import the public key into the EC2 console.

4. **Step 4**: Launching Ansible Node Servers
   - Launch multiple EC2 instances to serve as Ansible nodes.
   - Configure network settings and security groups.

5. **Step 5**: Testing Connectivity
   - Test SSH connectivity between the master and node servers.

6. **Step 6**: Installing Ansible on the Master Server
   - Update the master server and install Ansible.

7. **Step 7**: Creating an Ansible Inventory File
   - Define the managed nodes in an inventory file.

8. **Step 8**: Creating an Ansible Playbook
   - Write a playbook to deploy the website on the Apache server.

9. **Step 9**: Running the Playbook
   - Execute the playbook to install the web server on the servers.

10. **Step 10**: Conclusion
    - Summary of the deployment process and cleanup instructions.

## Conclusion
This project demonstrates how to automate the deployment of a website on Apache web servers across multiple EC2 instances using Ansible playbooks. By following the outlined steps, users can efficiently deploy and manage web applications in an AWS environment.

## Authors
- [Your Name](https://github.com/yourusername)
- [Co-author's Name](https://github.com/coauthorusername)

## Contact
For any inquiries or feedback, please contact:
- [Your Email](mailto:youremail@example.com)
- [Co-author's Email](mailto:coauthoremail@example.com)

## Resources Used
- GitHub Repository: [https://github.com/mudasirhaji/website.git](https://github.com/mudasirhaji/website.git)

If you found this guide helpful, please consider leaving feedback in the comments section and showing your support by following and applauding the project. Your feedback is greatly appreciated!

Thank you.
Medium blog : https://medium.com/@ezermbu3/deploying-a-website-on-apache-web-servers-across-multiple-ec2-instances-8d36eee65501
