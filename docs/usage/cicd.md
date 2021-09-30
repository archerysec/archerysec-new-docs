---
layout: default
title: CI/CD
nav_order: 20
parent: Usages
permalink: /docs/cicd_scans
last_modified_date: 2021-09-29T22:54:08+0000
---

# CI/CD Scans

<br>

ArcherySec integrates with CI/CD pipelines using the archerysec-cli. `archerysec-cli` automated and inject scanners in CI/CD pipeline.

<br>
![img](img/cicd/cicd.png)
<br>


## CI/CD Scan Policies

CI/CD policies define the criteria for passing or failing a archerysec-cli scan. The archerysec-cli scanner returns either exit code 0 pass or exit code 1 fail after each scan, enabling you to stop the build or deployment process on basis of defined criteria.

<br>
![img](img/cicd/scan-policy.png)
<br>

## Add New CI/CD Scan Policie

<br>

To define a CI/CD policy:

1. Move to CI/CD module 
2. Click on Add Policy
3. Provide `Policies Name`
4. Select `Project` from options. [Create new project](/) if you have not created one.
5. Define `Threshold` from issue type `High` `Medium` and `Low`
6. Select `SCM Server`
7. Select `Build Server`
8. Provide `Target Name`
9. Provide `Code Path/Target` (Code Path for SAST or SCA scan and Target for DAST)
10. Select your scanner type
11. Copy Command and inject into your Pipeline script
12. Now Click on `Submit`

<br>
![img](img/cicd/create-policy.png)
<br>

<br>
![img](img/cicd/copy-cmd.png)
<br>

## archerysec-cli Scan

<br>
![img](img/cicd/cli-scan.png)
<br>