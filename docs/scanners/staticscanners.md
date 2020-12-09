---
layout: default
title: Static Scanners
parent: Scanners
nav_order: 4
---

## Static Scanners 

Currently Archerysec supports below the list of Static Scanners plugin and report parser.

- [x] [OWASP Dependency-Check](#Dependency-Check)
- [x] [FindBug](#FindBug)
- [x] [Bandit Scan](#Bandit-Scan)
- [x] [npm_audit](#npm_audit)
- [x] [nodejsscan](#nodejsscan)
- [x] [clair](#clair)
- [x] [bandit](#bandit)
- [x] [Trivy](#Trivy)


### OWASP Dependency-Check
----------------------------

Dependency-Check is a Software Composition Analysis (SCA) tool that attempts to detect publicly disclosed vulnerabilities contained within a project’s dependencies. It does this by determining if there is a Common Platform Enumeration (CPE) identifier for a given dependency. If found, it will generate a report linking to the associated CVE entries. [more](https://owasp.org/www-project-dependency-check/)

### FindBug
----------------------------

FindBugs is an open-source static code analyser created by Bill Pugh and David Hovemeyer which detects possible bugs in Java programs. Potential errors are classified in four ranks: scariest, scary, troubling and of concern. This is a hint to the developer about their possible impact or severity. [more](http://findbugs.sourceforge.net/)

### Bandit Scan
----------------------------

Bandit is a tool designed to find common security issues in Python code. To do this, Bandit processes each file, builds an AST from it, and runs appropriate plugins against the AST nodes. Once Bandit has finished scanning all the files, it generates a report. [more](https://bandit.readthedocs.io/en/latest/)


### npm_audit
----------------------------

npm audit is a new command that performs a moment-in-time security review of your project’s dependency tree. Audit reports contain information about security vulnerabilities in your dependencies and can help you fix a vulnerability by providing simple-to-run npm commands and recommendations for further troubleshooting. [more](https://blog.npmjs.org/post/173719309445/npm-audit-identify-and-fix-insecure)

### nodejsscan
----------------------------

Static security code scanner (SAST) for Node.js applications powered by libsast and semgrep. [more](https://github.com/ajinabraham/nodejsscan)

### clair
----------------------------

Clair is an open source project for the static analysis of vulnerabilities in application containers (currently including appc and docker). [more](https://github.com/quay/clair)


### Trivy
------------

Trivy (tri pronounced like trigger, vy pronounced like envy) is a simple and comprehensive vulnerability scanner for containers and other artifacts. A software vulnerability is a glitch, flaw, or weakness present in the software or in an Operating System. Trivy detects vulnerabilities of OS packages (Alpine, RHEL, CentOS, etc.) and application dependencies (Bundler, Composer, npm, yarn, etc.). Trivy is easy to use. Just install the binary and you're ready to scan. All you need to do for scanning is to specify a target such as an image name of the container. [more](https://github.com/aquasecurity/trivy)