# Mongo DB migration with Ansible Playbook

## Prerequisites
- [Database Tools](https://www.mongodb.com/docs/database-tools/installation/installation/)
- [Ansible](https://docs.ansible.com/ansible/latest/installation_guide/intro_installation.html)

## How to use
1. Install Database Tools
2. Install Ansible
3. Clone this repository
4. Change mongodump.cfg and mongorestore.cfg accordingly
5. Open up playbook.yml then change USERNAME and DATABASE_NAME
6. Execute `ansible-playbook playbook.yml` in the terminal

For more details, follow this [article](https://dev.to/budiantoip/how-to-migrate-a-mongo-database-with-ansible-playbook-2fha).