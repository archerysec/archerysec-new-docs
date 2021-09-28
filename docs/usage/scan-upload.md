---
layout: default
title: Scan Upload
nav_order: 10
parent: Usages
permalink: /docs/scan_upload
last_modified_date: 2021-09-28T17:54:08+0000
---

# Scan Upload

<br>
Scan upload functionality provides you to import scanners result into ArcherySec and consolidate data in one place. ArcherySec support multiple scanners report format parser.

## Upload Scans

<br>

Using file upload functionality you can upload scanners report that [Supported by ArcherySec](#scanner-file-format-support)

![img](img/scans/scan-upload.png)

## Scanner File Format Support 

<br>

Below are scanner and their file type supported by archerysec. 

| Scanners        | File Type      | Sample |
|:-------------|:------------------|:------|
| OWASP ZAP    | XML               | [Link](https://raw.githubusercontent.com/archerysec/report-sample/main/OWASP-ZAP/OWASP-ZAP-v2.7.0.xml) |
| Burp Pro Scanner | XML           | [Link](https://raw.githubusercontent.com/archerysec/report-sample/main/Burp/Burp_Report.xml) |
| Aarachni Scanner | XML           | [Link](https://raw.githubusercontent.com/archerysec/report-sample/main/Arachni/Arachni_v1.3.xml) |
| Netsparker Scanner | XML         | [Link](https://raw.githubusercontent.com/archerysec/report-sample/main/Netsparker/Netsparker_report.xml) |
| Webinspect Scanner | XML         | [Link](https://raw.githubusercontent.com/archerysec/report-sample/main/Webinspect/Webinspect_v18.20.xml) |
| Acunetix Scanner   | XML         | [Link](https://raw.githubusercontent.com/archerysec/report-sample/main/Acunetix/Acunetix_report_sample.xml) |
| DependencyCheck Scanner | XML    | [Link](https://raw.githubusercontent.com/archerysec/report-sample/main/Dependency-check/dependency-check-report_v5.2.1.xml) |
| Checkmarx Scanner   | XML        | [Link](https://raw.githubusercontent.com/archerysec/report-sample/main/Checkmarx/Checkmarx_v8.9.0.210.xml) |
| FindSecBugs Scanner | XML        | [Link](https://raw.githubusercontent.com/archerysec/report-sample/main/Findbugs/findbugs_report_v3.1.5.xml) |
| Bandit Scanner      | JSON        | [Link](https://raw.githubusercontent.com/archerysec/report-sample/main/Bandit/bandit_report.json) |
| Clair Scanner       | JSON        | [Link](https://raw.githubusercontent.com/archerysec/report-sample/main/Clair/clair_output.json) |
| Trivy Scanner       | JSON        | [Link](https://raw.githubusercontent.com/archerysec/report-sample/main/Trivy/trivy_results.json) |
| NPM-Audit Scanner   | JSON        | [Link](https://raw.githubusercontent.com/archerysec/report-sample/main/Npmaudit/npm_audit_report.json) |
| Nodejs Scanner      | JSON        | [Link](https://raw.githubusercontent.com/archerysec/report-sample/main/Nodejsscan/nodejsscan_report.json) |
| Tfsec Scanner       | JSON        | [Link](https://raw.githubusercontent.com/archerysec/report-sample/main/tfsec/tfsec_report.json) |
| Whitesource Scanner  | JSON        | [Link](https://raw.githubusercontent.com/archerysec/report-sample/main/Whitesource/whitesource-report.json) |
| Inspec           | JSON        | [Link](https://raw.githubusercontent.com/archerysec/report-sample/main/Inspec/inspec_report.json) |
| Dockle Scanner   | JSON        | [Link](https://raw.githubusercontent.com/archerysec/report-sample/main/Dockle/dockle_report.json) |
| Gitlab SAST Scanner  | JSON        | [Link](https://raw.githubusercontent.com/archerysec/report-sample/main/Gitlab/gl-sast-report.json) |
| Gitlab SCA Scanner    | JSON        | [Link](https://raw.githubusercontent.com/archerysec/report-sample/main/Gitlab/gl-dependency-scanning-report.json) |
| Gitlab Container Scanner  | JSON        | [Link](https://raw.githubusercontent.com/archerysec/report-sample/main/Gitlab/gl-container-scanning-report.json) |
| Semgrep Scanner          | JSON        | [Link](https://raw.githubusercontent.com/archerysec/report-sample/main/Semgrep/semgrep-WebGoat.json) |
| Twistlock Scanner        | JSON        | [Link](https://raw.githubusercontent.com/archerysec/report-sample/main/Twistlock/twistlock.json) |
| Breakman Scanner         | JSON        | [Link](https://raw.githubusercontent.com/archerysec/report-sample/main/Brakeman/brakeman_output.json) |
| OpenVAS Scanner         | XML        | [Link](https://raw.githubusercontent.com/archerysec/report-sample/main/Openvas/openvas.xml) |

