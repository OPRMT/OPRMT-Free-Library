SECURITY.md
Repository: OPRMT™ Free Library
Owner: Michael W. Fleming
Framework: OPRMT™ (Objective, Parameters, Results, Method, Tools)
Website: https://oprmt.solutions
Security Contact: engineering@oprmt.solutions
1. Security Policy Overview
The OPRMT™ Free Library is a public repository providing structured prompt engineering artifacts under controlled licensing.
This repository:
Does NOT contain proprietary enterprise systems
Does NOT contain private automation credentials
Does NOT contain internal validation infrastructure
Does NOT contain commercial certification logic
However, it DOES represent intellectual property under the OPRMT™ trademark and framework architecture.
Security is treated at three levels:
Level
Category
Scope
L1
Infrastructure Security
GitHub repository, commits, branches
L2
Intellectual Property Protection
Framework structure and derivative misuse
L3
Dependency & Automation Risk
Scripts, templates, automation examples
2. Supported Versions
Only the main branch is considered supported.
Version
Supported
main
Yes
All other branches
No
Security patches will be applied only to the main branch.
3. Reporting a Vulnerability
If you discover a vulnerability, misuse vector, or IP abuse:
DO NOT open a public issue.
Instead:
Email:
engineering@oprmt.solutions
Subject line format:
Copy code

[SECURITY REPORT] – OPRMT Free Library – {Short Description}
Include:
Description of issue
Steps to reproduce (if applicable)
Impact assessment
Suggested mitigation (optional)
Screenshots or logs (if relevant)
4. Response Timeline
Phase
Target Time
Acknowledgment
Within 72 hours
Initial Assessment
Within 7 business days
Mitigation Plan
Within 14 business days
Resolution (if valid)
As determined by severity
Severity is internally classified as:
Critical – IP theft vector or automation exploit
High – Structural misuse enabling derivative commercial cloning
Medium – Misconfiguration or automation weakness
Low – Documentation or formatting inconsistency
5. Intellectual Property & Abuse Reporting
OPRMT™ is a trademarked framework owned by Michael Willis Fleming.
Security includes:
Unauthorized resale of library content
Repackaging under alternate branding
Derivative commercial exploitation violating license
False certification claims using OPRMT™
If you identify:
Cloned repositories
Unauthorized course products
Commercial misuse
Report to:
engineering@oprmt.solutions
Subject: [IP ABUSE REPORT]
6. Prohibited Security Testing
The following are strictly prohibited without written permission:
Automated scraping of repository at scale
Reverse-engineering commercial OPRMT™ systems
Attempted bypass of licensing mechanisms
Bot-driven extraction for resale
Violation may result in:
DMCA takedown
Platform reporting
Legal enforcement under trademark law
7. Dependency & Automation Guidelines
If this repository includes:
Google Apps Script examples
GitHub Actions workflows
Automation templates
Users must:
Never commit API keys
Never store credentials in plain text
Use .env files locally (excluded via .gitignore)
Enable GitHub secret scanning
Recommended:
Enable Dependabot
Enable secret scanning
Enable branch protection rules
Require pull request reviews
8. Secure Contribution Requirements
If pull requests are enabled:
All contributions must:
Avoid embedded credentials
Avoid proprietary system leaks
Avoid non-permitted license conflicts
Preserve OPRMT™ structural integrity
All PRs are subject to compliance validation.
9. Security Philosophy
The OPRMT™ Framework is engineered as:
A structured prompt architecture system
A compliance-driven prompt engineering methodology
A deterministic output design framework
Security includes:
Architectural integrity
Trademark protection
Structural consistency
Controlled extensibility
This repository represents the educational and foundational tier only.
Enterprise automation, certification engines, scoring models, and commercial generators are not included in the Free Library.
10. Acknowledgments
Responsible disclosures that materially improve the security posture of this repository may be publicly acknowledged at the discretion of the repository owner.
No monetary bounty program is currently active.
11. Policy Updates
This SECURITY.md may be updated without notice.
Last Updated: 2026-02-11
Policy Version: 1.0.0