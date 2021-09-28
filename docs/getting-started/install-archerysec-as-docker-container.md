---
layout: default
title: Install ArcherySec As Docker Container
nav_order: 6
parent: Getting Started
permalink: /docs/install-archerysec-as-docker-container
last_modified_date: 2021-09-29T22:54:08+0000
---

# Install ArcherySec As Docker Container

## Introudction

Follow the procedure on this page to deploy ArcherySec on a Linux host running the Docker container engine.

## Prerequisites

- Docker
- docker-compose

## ArcherySec Run As Container

```bash
$ docker pull archerysec/archerysec
$ docker run \
    -e NAME=user \
    -e EMAIL=user@user.com \
    -e PASSWORD=admin@123A  \
    -it -p 8000:8000 archerysec/archerysec:latest
```

## Provision Through docker-compose

```bash
# Git clone archerysec project
git clone https://github.com/archerysec/archerysec.git
```

```bash
# Move to archerysec directory
cd archerysec
```

```bash
# Run docker-compose 
docker-compose up -d
```


