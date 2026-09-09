# Cybersecurity-Home-Lab
Digital Regenesys 

The projects were done as part of an exam for my cybersecurity certificate. 

# 🛡️ Cybersecurity Projects Portfolio

## 👨‍💻 About This Portfolio

Welcome to my cybersecurity portfolio.

This repository documents my hands-on cybersecurity labs and projects covering **Security Operations, SIEM, network analysis, intrusion detection, vulnerability assessment, web application security, phishing analysis, and incident reporting**.

The projects were completed in controlled lab environments and were designed to develop practical skills relevant to **SOC Analyst and Junior Cybersecurity Analyst** roles.

---

## 🎯 Cybersecurity Focus Areas

- Security Operations (SOC)
- Security Monitoring & Alert Triage
- SIEM
- Network Traffic Analysis
- Intrusion Detection
- Vulnerability Assessment
- Web Application Security
- Phishing & Email Security
- Incident Investigation
- Incident Reporting
- Threat Detection
- Security Hardening
- Network Reconnaissance

---

# 📂 Projects

## 1. 🔎 SIEM Security Monitoring & Alert Triage

### Objective

Develop practical experience with Security Information and Event Management (SIEM) platforms by collecting, monitoring, and analyzing security events.

### Tools

- Splunk
- Wazuh
- Ubuntu
- Windows
- SIEM dashboards and logs

### Activities

- Analyzed security logs and events.
- Investigated suspicious activity.
- Practiced alert triage.
- Identified potentially malicious events.
- Correlated security information from logs.
- Determined when an alert required escalation.
- Practiced basic incident investigation workflows.

### Skills Demonstrated

`SIEM` `Log Analysis` `Alert Triage` `Threat Detection` `Incident Investigation` `Escalation`

---

# 2. 🌐 Network Reconnaissance & Vulnerability Assessment

### Objective

Use network reconnaissance techniques to identify hosts, services, and potential attack surfaces within a controlled lab environment.

### Tools

- Nmap
- Kali Linux
- VMware
- Windows
- Netstat

### Activities

- Performed host discovery.
- Conducted port scanning.
- Identified open, closed, and filtered ports.
- Investigated exposed services.
- Assessed the potential attack surface.
- Documented reconnaissance results.

### Example

A vulnerable web application environment was scanned to identify its exposed services and determine how the application was accessible across the network.

### Skills Demonstrated

`Nmap` `Network Reconnaissance` `Port Scanning` `Attack Surface Analysis` `Kali Linux`

---

# 3. 🕵️ Network Traffic Analysis with Wireshark & TCPDump

### Objective

Analyze network packets to understand communication between systems and identify suspicious or security-relevant traffic.

### Tools

- Wireshark
- TCPDump
- Kali Linux
- Windows
- OWASP Juice Shop

### Activities

- Captured network traffic.
- Inspected TCP connections.
- Analyzed HTTP requests and responses.
- Investigated client/server communication.
- Used packet filters to isolate relevant traffic.
- Investigated XSS-related HTTP requests.
- Compared TCPDump captures with IDS detection.

### Investigation

Network traffic generated during controlled web application security testing was captured and analyzed to identify the requests associated with the test activity.

### Skills Demonstrated

`Wireshark` `TCPDump` `Packet Analysis` `HTTP Analysis` `Network Investigation` `TCP/IP`

---

# 4. 🚨 Suricata Intrusion Detection System

### Objective

Deploy and configure Suricata as an Intrusion Detection System (IDS) and develop custom rules for detecting suspicious network activity.

### Tools

- Suricata 8.0.5
- Kali Linux
- Nmap
- Wireshark
- TCPDump

### Activities

- Installed and configured Suricata.
- Configured network interfaces using `af-packet`.
- Created custom Suricata detection rules.
- Developed detection logic for Nmap SYN scanning.
- Created rules for detecting XSS-related HTTP requests.
- Investigated Suricata signature errors.
- Troubleshot duplicate signatures.
- Monitored Suricata logs.
- Validated alerts using `fast.log`.

### Detection Scenarios

#### Nmap SYN Scan Detection

Created a custom IDS rule designed to identify suspicious SYN scanning activity against commonly used service ports.

#### XSS Detection

Created and tested custom rules designed to identify XSS-related strings in HTTP traffic generated within the controlled Juice Shop environment.

### Skills Demonstrated

`Suricata` `IDS` `Custom Rules` `Threat Detection` `Network Security` `Log Analysis` `Detection Engineering`

---

# 5. 🕸️ Web Application Security Testing

## OWASP Juice Shop

### Objective

Perform controlled web application security testing against OWASP Juice Shop to understand common web vulnerabilities and how they appear in HTTP traffic.

### Tools

- OWASP Juice Shop
- Burp Suite
- Wireshark
- Nmap
- Netcat
- Kali Linux

### Activities

- Identified vulnerable application functionality.
- Intercepted HTTP traffic using Burp Suite.
- Inspected GET and POST requests.
- Analyzed HTTP responses.
- Used Burp Repeater to modify and replay requests.
- Tested XSS functionality using harmless payloads.
- Captured the resulting traffic in Wireshark.
- Developed Suricata detection rules for the observed traffic.
- Documented findings and remediation recommendations.

### Skills Demonstrated

`Burp Suite` `OWASP Juice Shop` `XSS` `HTTP` `Web Security` `Vulnerability Assessment`

---

# 6. 🎣 Phishing Investigation & Email Security

### Objective

Develop practical experience investigating phishing-related indicators and identifying characteristics of potentially malicious emails and files.

### Investigation Areas

- Suspicious email analysis
- Phishing indicators
- Malicious links
- Suspicious attachments
- Sender analysis
- Email header analysis
- File/hash investigation
- Threat intelligence
- Security reporting

### Tools & Resources

- VirusTotal
- Email/header analysis techniques
- Hash/checksum analysis
- Threat intelligence concepts
- Security reporting

### Activities

- Investigated suspicious phishing indicators.
- Examined email characteristics that could indicate social engineering.
- Analyzed suspicious attachments and files in a controlled environment.
- Used file hashes/checksums for identification and investigation.
- Used VirusTotal as a threat intelligence source.
- Assessed indicators of compromise.
- Documented investigation findings.
- Developed recommendations for preventing similar phishing attacks.

### Phishing Indicators Investigated

- Suspicious sender information
- Unexpected attachments
- Suspicious URLs
- Potentially malicious files
- Social engineering techniques
- Impersonation indicators
- Abnormal email characteristics
- File hashes and reputation

### Skills Demonstrated

`Phishing Analysis` `Threat Intelligence` `IOC Analysis` `VirusTotal` `Hash Analysis` `Email Security` `Incident Reporting`

---

# 7. 📡 Netcat HTTP & Network Communication Lab

### Objective

Understand HTTP communication at a lower level by manually establishing TCP connections and sending HTTP requests.

### Tools

- Netcat
- Kali Linux
- OWASP Juice Shop

### Activities

- Established TCP connections using Netcat.
- Manually constructed HTTP GET requests.
- Used `printf` to send HTTP requests.
- Examined server responses.
- Investigated differences between ports.
- Practiced understanding the relationship between TCP ports and application services.

### Skills Demonstrated

`Netcat` `TCP` `HTTP` `Network Troubleshooting` `Command Line`

---

# 8. 🔐 Security Investigation & Incident Reporting

### Objective

Combine evidence from multiple cybersecurity tools to produce structured security findings and incident reports.

### Tools

- Splunk
- Wazuh
- Wireshark
- TCPDump
- Nmap
- Suricata
- Burp Suite
- VirusTotal

### Activities

- Collected technical evidence.
- Analyzed security events.
- Investigated suspicious network traffic.
- Reviewed IDS alerts.
- Documented vulnerabilities.
- Assessed potential impact.
- Identified security weaknesses.
- Recommended security controls.
- Produced structured incident reports.

### Reporting Areas

- Executive summary
- Technical findings
- Evidence
- Indicators of compromise
- Risk/impact
- Investigation methodology
- Detection methods
- Remediation
- Security hardening recommendations

### Skills Demonstrated

`Incident Response` `Technical Reporting` `Evidence Analysis` `Risk Assessment` `Security Documentation`

---

# 🧰 Technical Toolkit

| Category | Tools / Technologies |
|---|---|
| SIEM | Splunk, Wazuh |
| Network Analysis | Wireshark, TCPDump |
| Network Security | Suricata |
| Reconnaissance | Nmap |
| Web Security | Burp Suite, OWASP Juice Shop |
| Network Utilities | Netcat, Netstat |
| Threat Intelligence | VirusTotal |
| Operating Systems | Kali Linux, Ubuntu, Windows |
| Virtualization | VMware |
| Endpoint Security | EDR Concepts |
| Security Operations | Alert Triage, Investigation, Escalation |
| Reporting | Incident & Vulnerability Reports |

---

# 🧠 Skills Developed

Through these projects, I have developed practical exposure to:

### Security Operations
- Security monitoring
- Alert triage
- Threat detection
- Incident investigation
- Incident escalation
- Security event analysis

### Network Security
- Network reconnaissance
- Port scanning
- Packet capture
- Network traffic analysis
- IDS configuration
- Detection rule development

### Web Application Security
- HTTP analysis
- XSS testing
- Request/response analysis
- Burp Suite
- Vulnerability identification
- Security remediation

### Threat & Phishing Analysis
- Phishing investigation
- IOC identification
- Hash/checksum analysis
- Threat intelligence
- Suspicious file analysis
- Email security

### Documentation
- Incident reporting
- Vulnerability reporting
- Technical evidence documentation
- Risk assessment
- Security hardening recommendations

---

# 🔬 Lab Environment

Most of the practical exercises were performed in controlled environments using:

```text
                    ┌─────────────────┐
                    │   Kali Linux    │
                    │                 │
                    │ Nmap            │
                    │ Wireshark       │
                    │ TCPDump         │
                    │ Suricata        │
                    │ Burp Suite      │
                    │ Netcat          │
                    └────────┬────────┘
                             │
                             │ Network Traffic
                             │
                    ┌────────▼────────┐
                    │ Windows Host    │
                    │                 │
                    │ OWASP Juice Shop│
                    └─────────────────┘

