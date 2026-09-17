# Enterprise SOC Lab — Splunk, Sysmon & MITRE ATT&CK

A hands-on Enterprise Security Operations Center (SOC) laboratory project
built to practice SIEM monitoring, detection engineering, threat analysis,
MITRE ATT&CK mapping, automated response, and lightweight incident analysis.

## Architecture

The lab consists of:

- Splunk Enterprise — SIEM and centralized security monitoring
- Microsoft Windows Server 2022 — Active Directory / Domain Controller
- Windows 10 — Endpoint monitoring
- Sysmon — Endpoint telemetry
- Kali Linux — Security testing and attack simulation
- pfSense — Network infrastructure and gateway
- VMware — Virtualized laboratory environment
- MITRE ATT&CK — Detection and technique mapping

## Key Implementations

- Centralized Windows event collection
- Sysmon process monitoring
- PowerShell activity detection
- Failed login detection
- Windows account creation detection
- Suspicious process detection
- Brute-force login detection
- MITRE ATT&CK mapping
- SOC monitoring dashboard
- Automated response script
- Lightweight incident-analysis prototype

## Detection Engineering

| ID | Detection |
|---|---|
| DET-001 | PowerShell Process Execution |
| DET-002 | Windows Failed Login |
| DET-003 | Suspicious PowerShell Activity |
| DET-004 | Windows Account Creation |
| DET-005 | Suspicious Process Execution |
| DET-006 | Brute-Force Login Attempt |

## Documentation

The complete project documentation explains the architecture,
installation, configuration, detection rules, testing,
MITRE ATT&CK mapping, automated response, and incident analysis.

[View Full Project Documentation](Documentation/Enterprise-SOC-Project-Documentation.docx)

## Screenshots

Screenshots of the actual laboratory environment and Splunk implementation
are available in the `Screenshots` directory.

## Project Purpose

This project was built as a practical cybersecurity learning project
to develop hands-on skills in:

- SOC Operations
- SIEM
- Threat Detection
- Windows Security
- Incident Response
- MITRE ATT&CK
- Security Monitoring
- Network Security

## Tools & Technologies

Splunk Enterprise  
Microsoft Windows Server  
Windows 10  
Sysmon  
Kali Linux  
pfSense  
VMware  
MITRE ATT&CK

## Author

Muhammad Jamal
