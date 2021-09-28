---
layout: default
title: OWASP ZAP Scanner Connector
nav_order: 29
parent: Connector
permalink: /docs/owas-zap-connector
last_modified_date: 2021-09-29T22:54:08+0000
---

# OWASP ZAP Connector

Connect ArcherySec with your OWASP ZAP instance by configering OWASP ZAP API into ArcherySec settings. 

## Before you begin

The prerequisites are:

1. OWASP ZAP is running and accessible from ArcherySec server
2. OWASP ZAP API enabled and reachable through archerysec

Tools > Options > API

![img](img/owasp-zap-connector/zap-api-enable.png)

3. Copy API Key
4. Copy address and port 

![img](img/owasp-zap-connector/zap-local-proxy.png)


## Setup Steps

1. Login into ArcherySec
2. Go to Settings > Add Connector > OWASP ZAP 
3. Enable API
4. Provide `Zap API Key` 
5. Provide `Zap API Host`
6. Provide `Zap API Port`

![img](img/owasp-zap-connector/zap-setting-archerysec.png)

>Check the connection status

![img](img/owasp-zap-connector/zap-connection-status.png)

>>!!! Congratulations you have successfully configured OWASP ZAP Connector

## Troubleshooting and FAQ

Let us know if you have any issue or query at info@archerysec.com or [raise issue](https://github.com/archerysec/archerysec/issues)