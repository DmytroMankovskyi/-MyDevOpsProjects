# WordPress Deployment with Ansible

This project demonstrates automated deployment of a WordPress server using Ansible.

## Technologies

- AWS EC2
- Ansible
- Nginx
- PHP
- MySQL
- WordPress

## Description

The Ansible playbook installs and configures a web server environment and deploys WordPress automatically on a Linux server.

The playbook performs the following steps:

1. Updates system packages
2. Installs required packages (nginx, php, mysql)
3. Downloads the latest WordPress release
4. Extracts WordPress to the web directory
5. Sets correct permissions
6. Starts and configures the web server

## Project Structure
