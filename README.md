# SOC Analyst Incident Investigation Lab

## Overview
A homelab SOC environment simulating real cyberattacks and investigating them using Splunk SIEM.

## Tools Used
- Splunk Enterprise (SIEM)
- Sysmon (Windows logging)
- Kali Linux (Attacker)
- Windows 10 VM (Target)
- Atomic Red Team (Attack simulation)
- VirtualBox

## Attack Techniques Simulated
- T1059.001 — PowerShell Execution
- T1105 — Ingress Tool Transfer
- T1110 — Brute Force /Failed Login

## What I Did
1. Built a mini SOC environment with VirtualBox
2. Installed and configured Splunk as SIEM
3. Installed Sysmon for detailed Windows logging
4. Simulated attacks using Atomic Red Team
5. Detected and investigated attacks in Splunk
6. Wrote a full incident report

## Skills Demonstrated
- SIEM configuration and management
- Log analysis and threat detection
- Incident investigation and response
- MITRE ATT&CK framework knowledge
- Network security fundamentals

## Screenshots
<img width="1600" height="878" alt="Events" src="https://github.com/user-attachments/assets/15657c80-6251-4586-962e-3ffc179c3c29" />
<img width="1600" height="881" alt="Failed Logins" src="https://github.com/user-attachments/assets/ec0e2e53-6975-4a7b-ab2b-f5abf0622b88" />
<img width="1600" height="890" alt="PowerShell activity" src="https://github.com/user-attachments/assets/65526dd3-9157-4d7d-a541-ea3abaab846d" />
<img width="1600" height="887" alt="PowerShell Execution" src="https://github.com/user-attachments/assets/3ea737eb-3318-48dc-8eb4-88aad676f946" />
<img width="1600" height="860" alt="Process Creation" src="https://github.com/user-attachments/assets/b20e3a15-5bcc-4c87-9cd4-70eb4ecc6a8b" />
<img width="1600" height="963" alt="Ingress Tool Transfer" src="https://github.com/user-attachments/assets/9ee8bab2-2ba5-4fe9-bd73-d36a8252e6bf" />


## Incident Report
https://drive.google.com/file/d/1eYlEIX0dkn_zhuRtIrnkkmgWi0A2JSP8/view?usp=drive_link
