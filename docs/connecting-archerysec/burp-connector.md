---
layout: default
title: Burp Scan Connector
nav_order: 30
parent: Connector
permalink: /docs/burp-connector
last_modified_date: 2021-09-29T22:54:08+0000
---

# Burp Pro Scanner Connector

Connect ArcherySec with your Burp Pro Scanner instance by configering Burp Pro Scanner API into ArcherySec settings. 

## Before you begin

The prerequisites are:

1. Burp Pro Scanner is running and accessible from ArcherySec server
2. Burp Pro Scanner API enabled and reachable through archerysec

User options > Misc > REST API

![img](img/burp-scanner-connector/burp-enable-api.png)

3. Create and Copy API Key
4. Copy address and port 

![img](img/burp-scanner-connector/burp-endpoint.png)


## Setup Steps

1. Login into ArcherySec
2. Go to Settings > Add Connector > Burp 
3. Provide `Burp API Key` 
4. Provide `Burp host`
5. Provide `Burp API Port`

![img](img/burp-scanner-connector/burp-archerysec-setting.png)

>Check the connection status

![img](img/burp-scanner-connector/burp-connection-status.png)

>>!!! Congratulations you have successfully configured Burp Pro Scanner Connector

## Troubleshooting and FAQ

Let us know if you have any issue or query at info@archerysec.com or [raise issue](https://github.com/archerysec/archerysec/issues)