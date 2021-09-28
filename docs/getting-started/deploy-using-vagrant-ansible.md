---
layout: default
title: Deploy Using Vagrant and Ansible
nav_order: 5
parent: Getting Started
permalink: /docs/deploy-using-vagrant-and-ansible
last_modified_date: 2021-09-29T22:54:08+0000
---


# Deploy Using Vagrant and Ansible

## Introudction
Vagrant and Ansible can be used to quickly build or rebuild virtual servers. ArcherySec can be configured using Vagrant and Ansible and in this example we'll going to deploy archerysec automatically using Ansible on Ubuntu Server. 

> ***DO NOT EXPOSE PUBLICLY, INTERNAL USE ONLY***

## Prerequisites
- Varant
- VirtualBox
- Ansible

## Deploy ArcherySec using Vagrant and Ansible 

- Run the following commands to setup:

```bash
# Clone Git repositiory
git clone https://github.com/archerysec/archerysec-vagrant-ansible.git

# Move into directory
cd archerysec-vagrant-ansible

# Run vagrant command to provision archerysec server
vagrant up --provision
```

![img](img/ansible-vagrant/ansible-provision.png)


- Access the archerysec by using link [http://archerysec.local/](http://archerysec.local/)
- Default Username: `archerysec@archerysec.lab`
- Default Password: `test@123A`

## File Structure

```bash
├── README.md
├── Vagrantfile
├── playbook.yml
├── roles
│   ├── defaults
│   │   └── main.yml
│   ├── handlers
│   │   └── main.yml
│   ├── tasks
│   │   └── main.yml
│   └── templates
│       ├── archerysec.service
│       ├── django_bootstrap.conf
│       ├── gunicorn_start
│       └── nginx.conf
└── ubuntu-bionic-18.04-cloudimg-console.log
```

### Change Default Password

If you want to change Default password of ArcherySec follow the below instruction.

1. Edit file roles main.yml file in path `roles/defaults/main.yml`
2. Change the vaule of `admin_email` and `admin_pass`
3. Run the vageant previsining command: `vagrant up --provision`
4. Access they URL [http://archerysec.local/](http://archerysec.local/) and provide new credentials

### Change Default Database Instance

If you want to change Database Default Credential follow the below instruction.

1. Edit file roles main.yml file in path `roles/defaults/main.yml`
2. Change the vaule of `db_user`, `db_password`, `db_host` and `db_name`
3. Run the vageant previsining command: `vagrant up --provision`

### Change Django Default Secret Key

1. Edit file roles main.yml file in path `roles/defaults/main.yml`
2. Change the vaule of `django_secret_key`
3. Run the vageant previsining command: `vagrant up --provision`