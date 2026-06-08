# Kurt B. | Security Engineer

I'm a security practitioner transitioning from 
on-premises security into cloud and AI security 
architecture. My focus is the intersection of 
offensive security, detection engineering, and 
identity — because that's where the real attacks 
happen and where most defenses fall short.

I don't just study attack techniques. I simulate 
them in a real lab environment, hunt the telemetry 
they generate in Microsoft Sentinel, and build 
detection rules that catch them. Everything here 
is validated against live data.

## What I'm Building
A full adversary simulation lab — Active Directory, 
AWS cloud infrastructure, and a Sysmon + AMA + 
Azure Sentinel telemetry pipeline — used to document 
attack techniques and build detections across 
traditional, cloud, and AI environments.

## Current Focus
- Offensive security & detection engineering
- AWS cloud security — IAM, VPC, CloudTrail, GuardDuty
- AI security & adversarial ML techniques
- Identity & trust architecture across all three layers

## Published Work
| Repo | Technique | MITRE |
|------|-----------|-------|
| [recon-detection-gap](https://github.com/bdk3000/recon-detection-gap) | Network recon blind spot analysis | T1046, T1595 |
| [privileged-logon-anomaly](https://github.com/bdk3000/privileged-logon-anomaly) | After-hours admin logon detection | T1078.002 |
| [llm-attack-techniques](https://github.com/bdk3000/llm-attack-techniques) | LLM prompt injection — 7 techniques | LLM01, LLM08 |
| [c2-dns-beacon-detection](https://github.com/bdk3000/c2-dns-beacon-detection) | DNS-based C2 beacon detection | T1071.004 |
| [ntlm-enumeration-detection](https://github.com/bdk3000/ntlm-enumeration-detection) | NTLM enumeration burst detection | T1046, T1078 |
| [aws-iam-priv-esc](https://github.com/bdk3000/aws-iam-priv-esc) | AWS IAM privilege escalation | T1078 |
| [identity-impossible-travel](https://github.com/bdk3000/identity-impossible-travel) | Impossible travel detection | T1078 |

## Lab Environment

Kali Linux → DC01 (Windows Server 2022)
→ WIN11-CL01
→ RHEL
→ Ubuntu
Telemetry: Sysmon → AMA → Azure Arc →
DCR → Log Analytics → Sentinel

## Stack

Offensive:   Kali Linux • Nmap • Metasploit
Detection:   Sysmon • Microsoft Sentinel • KQL
Cloud:       AWS • IAM • CloudTrail • GuardDuty
Identity:    Active Directory • Azure Arc
Frameworks:  MITRE ATT&CK • MITRE ATLAS • OWASP LLM Top 10

## Certifications
- CompTIA Security+
- CompTIA CySA+ (Cybersecurity Analyst)
-  AWS Certified Solutions Architect — Professional (SAP-C02)
- Microsoft Azure Fundamentals (AZ-900)
- Cisco CCNA

## Currently Studying
- Offensive security — CEH/OSCP track
- AWS Security Specialty
- AI security & adversarial ML
