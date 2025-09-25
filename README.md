# cs-task3
Perform a Basic Vulnerability Scan


## Objective : Use free tools to identify common vulnerabilities on your computer.
## Tools: OpenVAS Community Edition (free vulnerability scanner) or Nessus Essentials.
## Deliverables: Vulnerability scan report with identified issues.


## Tool Used : Nessus Essentials


## Steps Followed
1. Installed **Nessus Essentials** and registered with free activation code. Installed and launched at https://localhost:8834/ in the browser.
2. Set up a Network Scan targeting (127.0.0.1).
   Scan Name : Vulnerability Scan.
   Scan Target : 127.0.0.1 (localhost)
   Save.
3. Start a full vulnerability scan.
   Go to My Scans -> select Vulnerability Scan(saved scan).
   Click Launch.
   Nessus begins scanning your system.
4. Wait for Scan to Complete (30–60 mins)
   Runtime: 20–40 mins depending on plugins.  
5. Review the Report for Vulnerabilities
   Open completed scan.
   Nessus shows:
   Severity distribution: Critical, High, Medium, Low, Info.
   List of vulnerabilities with CVSS scores 


## Scan Summary
- Policy: Basic Network Scan  
- Duration: ~9 minutes  
- Vulnerabilities found: **1 Medium, 3 Info**

  
## Screenshot Added
**Screenshot 1 – Nessus Essential Installed** 
**Screenshot 2 – Nessus Dashboard** 
**Screenshot 3 – Vulnerability Scan** 
**Screenshot 4 – Scan Running** 
**Screenshot 5 – Vulnerability Summary** 
**Screenshot 6 – Vulnerability Summary2**
**Screenshot 7 – Detailed Vulnerability**
**Screenshot 8 – Detailed Vulnerability2**


## Detailed Vulnerability Example
- Name : SSL Certificate Cannot Be Trusted  
- Severity : Medium  
- CVSS Score : 6.5  
- Description : The SSL certificate on the target cannot be trusted, which may allow attackers to impersonate the service.  
- Solution : Use a valid SSL/TLS certificate signed by a trusted Certificate Authority (CA).  


## Key Concepts :  Vulnerability scanning, risk assessment, CVSS, remediation, security tools
- **Vulnerability Scanning**: Automated process to identify system weaknesses.  
- **CVSS (Common Vulnerability Scoring System)**: Standard scoring system (0–10) to measure vulnerability severity.    
- **Prioritization**: Critical and High severity issues should be fixed first.  


**Outcome: Introductory vulnerability assessment experience and understanding of common PC risks.**

