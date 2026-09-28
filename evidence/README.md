# Assessment Evidence Index

This directory contains the verified visual evidence collected during the authorized VAPT laboratory assessment. 

*Note: Sensitive values (such as extracted password hashes and real email addresses) visible in the final data-exposure evidence have been intentionally redacted with solid black boxes prior to public publication to ensure ethical disclosure standards.*

## Evidence Mapping

| Stage | Tool | Screenshot Evidence | Related Documentation |
| :--- | :--- | :--- | :--- |
| **01. Environment** | Web Browser | [01-juice-shop-interface.png](01-environment/01-juice-shop-interface.png) | [Project Overview](../README.md) |
| **02. Reconnaissance** | Nmap | [02-nmap-enumeration.png](02-nmap/02-nmap-enumeration.png) | [Reconnaissance](../docs/reconnaissance.md) |
| **03. Web Scanning** | Nikto | [03-nikto-scan-results.png](03-nikto/03-nikto-scan-results.png) | [Vulnerability Assessment](../docs/vulnerability-assessment.md) |
| **04. Vuln Assessment** | OpenVAS | [04-openvas-findings.png](04-openvas/04-openvas-findings.png)<br>[05-openvas-tls-finding.png](04-openvas/05-openvas-tls-finding.png) | [Vulnerability Assessment](../docs/vulnerability-assessment.md) |
| **05. Traffic Inspection** | Burp Suite | [06-burp-login-request.png](05-burp-suite/06-burp-login-request.png) | [SQL Injection Validation](../docs/sql-injection-validation.md) |
| **06. Exploitation Validation** | SQLmap | [07-sqlmap-injection-detection.png](06-sqlmap/07-sqlmap-injection-detection.png)<br>[08-sqlmap-injection-validation.png](06-sqlmap/08-sqlmap-injection-validation.png)<br>[09-sqlmap-table-enumeration.png](06-sqlmap/09-sqlmap-table-enumeration.png) | [SQL Injection Validation](../docs/sql-injection-validation.md) |
| **07. Impact Analysis** | SQLmap | [10-data-exposure-impact.png](07-impact/10-data-exposure-impact.png) | [Security Impact](../docs/security-impact.md) |
