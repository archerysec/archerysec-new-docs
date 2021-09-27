---
layout: default
title: Email Connector
nav_order: 34
parent: Connector
permalink: /docs/email-connector
---

# Email Connector

Connect ArcherySec with your Email ticketing system by configering Email API into ArcherySec settings. 

## Before you begin

The prerequisites are:

1. Email is running and accessible from ArcherySec server
2. ArcherySec run.sh ran with below environment varable

- `EMAIL_HOST` # End point of SMTP server
- `EMAIL_USE_TLS` # True or False
- `EMAIL_PORT` # SMTP Server Port
- `EMAIL_HOST_PASSWORD` # SMTP Token or Password
- `EMAIL_HOST_USER` # SMTP Server username

```bash
# archerysec start through run.sh 
EMAIL_HOST=127.0.0.1 \
EMAIL_PORT=1025 \
EMAIL_USE_TLS=True \
EMAIL_PORT=1025 \
EMAIL_HOST_PASSWORD=test \
EMAIL_HOST_USER=test \
bash run.sh
```

## Setup Steps

1. Login into ArcherySec
2. Go to Settings > Add Connector > Email 
3. Provide `Email Message :` # optional
4. Provide `Email Subject:` # optional
5. Provide `To Email` # email where you want to recieve notification

![img](img/mail-connector/email-form.png)

>Check the connection status

![img](img/mail-connector/email-status.png)

>>!!! Congratulations you have successfully configured Email Connector

## Troubleshooting and FAQ

Let us know if you have any issue or query at info@archerysec.com or [raise issue](https://github.com/archerysec/archerysec/issues)