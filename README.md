# soc_projects

This repository documents hands-on security investigations and detection projects from my home lab, built as part of my journey toward a career as a SOC Analyst.

## About Me
I'm Arsalan Agha, a Computer Network and Security student. This repo is where I simulate real-world attack scenarios, detect them using SIEM tools, and document the full investigation process — from attack to detection to lessons learned.

## Home Lab Setup
- Windows 10 VM (target)
- Lubuntu VM running Splunk (SIEM)
- Sysmon for enhanced Windows event logging
- VirtualBox with an isolated NAT Network

## Cases

| Case | Description | Tools Used |
|---|---|---|
| [Case 01: Brute Force Attack Detection](./01-Brute-Force) | Simulated an RDP/SMB brute-force attack using Hydra, detected via Windows Event Logs and Splunk | Hydra, Sysmon, Splunk |

## Skills Demonstrated
- Log analysis and correlation
- Splunk search query writing (SPL)
- Windows Security event log investigation (Event IDs 4624/4625)
- Attack simulation and detection engineering
- Incident documentation and reporting

## Connect
- 🔗 [LinkedIn](arsalan-agha-963b982b9)
