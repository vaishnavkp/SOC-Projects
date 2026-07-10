# SOC Portfolio

Hands-on Security Operations projects covering SIEM deployment, alert triage, threat hunting, and Active Directory attack detection — built in a self-managed home lab (Splunk, Wazuh, ELK Stack).

Each folder below is a self-contained write-up: objective, setup, steps, detection logic, and findings.

## Projects

| # | Project | Level | Skills Demonstrated |
|---|---------|-------|----------------------|
| 01 | [SIEM Deployment (Splunk, Wazuh, ELK)](./01-siem-deployment) | L1 | SIEM architecture, log ingestion, dashboarding |
| 02 | [Brute Force Investigation](./02-brute-force-investigation) | L1 | Alert triage, SPL/Wazuh detection rules |
| 03 | [Phishing Email Analysis](./03-phishing-email-analysis) | L1 | Header analysis, IOC extraction, escalation |
| 04 | [Data Exfiltration Investigation](./04-data-exfiltration-investigation) | L2 | Traffic analysis, scoping, containment |
| 05 | [DNS Tunneling Detection](./05-dns-tunneling-detection) | L2 | Query entropy analysis, detection engineering |
| 06 | [PowerShell Abuse Detection](./06-powershell-abuse-detection) | L2 | LOLBin detection, MITRE ATT&CK mapping |
| 07 | [AD Attack Lab (Kerberoasting, Pass-the-Hash, AS-REP Roasting)](./07-ad-attack-lab) | L2 | Offense + detection engineering |
| 08 | [Threat Hunting with osquery](./08-threat-hunting-osquery) | L2 | Hypothesis-driven hunting, persistence detection |

## Lab Environment

- **SIEM:** Splunk, Wazuh, ELK Stack (Fleet Server + Elastic Agent)
- **Endpoint telemetry:** Sysmon, osquery
- **Attack simulation:** Kali Linux, Active Directory lab (Kerberoasting, Pass-the-Hash, AS-REP Roasting)
- **Reference framework:** MITRE ATT&CK

## About Me

Security Researcher & Trainer with hands-on experience in SOC operations and VAPT. Full profile: [github.com/zero2root](https://github.com/zero2root)

---

*Note: All logs, IPs, and credentials shown in this portfolio are from an isolated lab environment and have been sanitized where necessary.*
