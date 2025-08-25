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

