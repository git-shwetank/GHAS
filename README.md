# GHAS
Reference: https://learn.microsoft.com/en-us/training/modules/introduction-github-advanced-security/1-introduction?source=learn

GHAS - Git Hub Advanced Security

- Applied to Software Development Project
- Purpose is to enhace security compliance of deliverables.
- Comprises of _Tools_ and _Features_
- Strong integration with _GitHub Enterprise Cloud_

Features
- Code Scanning
- Secret Scanning
- Automated Dependency Management (Dependabot)

Outcomes
- Identify and Protect Sensitive code
- Manage risk at scale
- Compliance to Security Standards
- Tend to a framework for security

**The Security Ecosystem** - <u>A derivation of Secure Software Development Life Cycle</u>
Products
- GitHub Secret Protection
  1. Push Protection (Blocks a commit if there is a match to patterns and/or signature indicating sensitive information)
  2. Alerts on Identified security risks and Intervention advise for quick remediation.
     
- GitHub Code Security
  1. Code Scanning: Static code Analysis tool to identify Security Vulnerabilities and Coding Errors.
  2. Employs feedback by hooks on Pull Request workflow.
     
- Dependabot: Keep project dependencies upto date
  1. _Alerts_ for known vulnerabilities
  2. _Security updates_ for vulnerable packages
  3. _Version updates_ to keep dependencies current
  4. Employs- _GitHub Advisory Database_
  5. No insecure dependency use are allowed to Merge (PR workflow)

# How to enable Secret Scanning, Code Scanning and Dependabot alert   
**Git Organisation**
Organizations are shared accounts where _businesses_ and _open-source projects_ can **collaborate** across many projects at once, with _sophisticated security_ and _administrative features_.

**_Types of Accounts_ with in GitHub Organisation**
- User accounts: It is an individual unit identity. Every person's login to git-hub is linked to a User Account.
- Organization accounts: Group of Individual Accounts enhancing security and collaboration on git workflows.
- Enterprise accounts: A set or group of Organisations in GitHub

A user account can be seen as an individual contributor to a department. 
As there can be multiple contributors and teams to a Department, hence a department can be seen as an organisation.
Since, there are collaborations possible b/w different departments as well, hence Enterprise enables collaboration of these Organisations.

**There are two types of user account:**
- Personal accounts (accounts created for personal use by individual)
- Managed user accounts (account created for individual by an enterprise on GitHub Enterprise Cloud)
  
**What is-**
1. GitHub Team 
2. GitHub Enterprise Cloud

Above grant full fledged features of using _Git Organisation_. 
