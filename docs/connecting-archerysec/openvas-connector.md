---
layout: default
title: OpenVAS Connector
nav_order: 32
parent: Connector
permalink: /docs/openvas-connector
last_modified_date: 2021-09-29T22:54:08+0000
---

# OpenVAS Connector

# OpenVAS Scanner Connector

Connect ArcherySec with your OpenVAS Scanner instance by configering OpenVAS Scanner API into ArcherySec settings. 

## Before you begin

>Note that, at this time, Archery generates a TCP connection towards the OpenVAS Manager (not the GSA): therefore, you need to update your OpenVAS Manager configuration to bind this port. Its default port (9390/tcp), but you can update this in your settings.

The prerequisites are:

1. OpenVAS Scanner is running and accessible from ArcherySec server
2. OpenVAS Scanner API enabled and reachable through archerysec


## Setup Steps

1. Login into ArcherySec
2. Go to Settings > Add Connector > OpenVAS 
3. Provide `OpenVAS API Host` 
4. Provide `OpenVAS API Port`
5. Provide `OpenVAS API User`
6. Provide `OpenVAS API Pass`

![img](img/openvas-connector/openvas-archerysec.png)

>Check the connection status

![img](img/openvas-connector/openvas-status.png)

>>!!! Congratulations you have successfully configured OpenVAS Scanner Connector

## Troubleshooting and FAQ

Let us know if you have any issue or query at info@archerysec.com or [raise issue](https://github.com/archerysec/archerysec/issues)