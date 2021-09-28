---
layout: default
title: Quick Start Guide For Linux
nav_order: 4
parent: Getting Started
permalink: /docs/quick-start-guide-for-linux
last_modified_date: 2021-09-29T22:54:08+0000
---

# Quick Start Guide For Linux

## Introudction

Follow the procedure on this page to deploy ArcherySec in your Linux environement quickly and easily. This quick-start deployment is suited for environments intended for instruction, development, and test.

> ***DO NOT EXPOSE PUBLICLY, INTERNAL USE ONLY***

## Prerequisites

Make sure you have the following environment setup available

1. Ubuntu Server 
2. Python Python 3.6+ with pip installed

## Deploy ArcherySec in Linux

1. Run the following commands to setup:

```bash
# Git clone archerysec project
git clone https://github.com/archerysec/archerysec.git
```

```bash
# Move to archerysec directory
cd archerysec
```

```bash
# Running Setup Command
# ex. NAME=User EMAIL=user@user.com PASSWORD=admin@123A bash setup.sh
NAME=<NAME OF USER> EMAIL=<EMAIL ID OF USER> PASSWORD=<USER ACCOUNT PASSWORD> bash setup.sh
```

2. Run the ArcherySec by executing below command

```bash
# Running archerysec
bash run.sh
```

## Environment variables for this project

The following environment variables are used to change behaviour of the container settings

`TIME_ZONE`


```bash
export TIME_ZONE='Asia/Kolkata'
```

https://en.wikipedia.org/wiki/List_of_tz_database_time_zones

`DB_PASSWORD`
Database password for the postgres db server

`DB_USER`
Database user for the postgres db server

`DB_NAME`
Database name for the postgres db server

`DJANGO_SETTINGS_MODULE`
Django setting to use. currently this can be set to `archerysecurity.settings.development` or `archerysecurity.settings.production` depending on your needs

`DJANGO_SECRET_KEY`
Always generate and set a secret key for you project. Tools like this one can be used for this purpose

`DJANGO_DEBUG`
Set this variable to `1` if debug should be enabled

`EMAIL_HOST`

```bash
export EMAIL_HOST='smtp.xxxxx.com'
```

`EMAIL_USE_TLS`

```bash
export EMAIL_USE_TLS=True
````

Set this variable to True or False

`EMAIL_PORT`

```bash
export EMAIL_PORT=587
```

Set this variable to SMTP port.

`EMAIL_HOST_PASSWORD`

```bash
export EMAIL_HOST_PASSWORD='password'
```

Set this variable to SMTP Password.

`EMAIL_HOST_USER`

```bash
export EMAIL_HOST_USER=xxxxxxxxxxxxx@gmail.com
```

Set this variable to SMTP Email.

## Accessing ArcherySec for the First Time

When you access ArcherySec for the first time, you will be required to provide the username and password that are povided while setup.

1. Access deployed URL: [https://0.0.0.0:8000](https://0.0.0.0:8000)

![img](img/getting-started/archerysec-login.png)


![img](img/getting-started/landing-page.png)