# windows-security-monitoring
A windows security monitoring lab using Sysmon to detect suspicious activity, analyse logs, and build detection rules.
# Windows Security Monitoring Lab (Sysmon)
This project demonstrates how to use Sysmon for Windows endpoint monitoring, log analysis, and threat detection.  
It includes Sysmon installation, log generation, simulated attacker activity, and custom detection rules.

##  What This Project Covers
- Installing and configuring Sysmon
- Generating Windows telemetry (process, network, file events)
- Simulating suspicious PowerShell activity
- Analyzing Sysmon logs in Event Viewer
- Creating detection rules for attacker behavior
- Documenting findings like a SOC analyst

##  Project Structure
windows-security-monitoring/
│
├── README.md
├── detections/
├── screenshots/
└── sysmon-config.xml (optional)

## Tools Used
- Sysmon (Sysinternals)
- Windows Event Viewer
- PowerShell
