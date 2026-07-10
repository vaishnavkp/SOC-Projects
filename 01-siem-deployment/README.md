# SIEM Deployment: Splunk, Wazuh & ELK Stack

## Objective
[1-2 sentences: what you set out to build and why — e.g. "Built a multi-SIEM home lab to gain hands-on experience with log ingestion, correlation, and dashboarding across the three most commonly used platforms in SOC environments."]

## Environment / Architecture

- **Host OS:** [e.g. Windows 11]
- **Virtualization:** [e.g. VirtualBox]
- **Endpoints monitored:** [e.g. Kali Linux, Windows 10 VM]
- **Tools deployed:**
  - Splunk [version]
  - Wazuh [version]
  - Elastic Stack — Fleet Server + Elastic Agent

```
[Simple architecture diagram or bullet list of topology, e.g.:
Windows 11 Host
 ├── Splunk Enterprise (log indexing + SPL)
 ├── Wazuh Manager (agent-based endpoint monitoring)
 └── ELK Stack
      ├── Fleet Server
      └── Elastic Agent → Kali Linux endpoint
]
```

## Steps

### 1. Splunk Deployment
[What you did — installation, log source onboarding, index configuration]

```
[commands or config snippets used]
```

![Splunk dashboard](./screenshots/splunk-dashboard.png)

### 2. Wazuh Deployment
[What you did — manager/agent setup, any issues resolved (e.g. cert errors, DHCP/IP changes)]

```
[commands or config snippets used]
```

![Wazuh dashboard](./screenshots/wazuh-dashboard.png)

### 3. ELK Stack Deployment
[What you did — Fleet Server setup, Elastic Agent enrollment on Kali, SSL/firewall/network binding issues you resolved]

```
[commands or config snippets used]
```

![Elastic dashboard](./screenshots/elastic-dashboard.png)

## Challenges & Troubleshooting
[This section matters a lot for SOC roles — document 2-3 real issues you hit and how you fixed them. e.g. "Elastic Agent failed to enroll due to a certificate mismatch between Fleet Server and the host — resolved by regenerating the CA and re-enrolling the agent."]

## Log Sources Ingested
| Source | Platform | Purpose |
|--------|----------|---------|
| [e.g. Windows Event Logs] | [Splunk/Wazuh/ELK] | [Auth monitoring, process creation] |
| [e.g. Sysmon] | [Splunk/ELK] | [Process/network telemetry] |

## Outcome / What I Learned
[What this build let you do that you couldn't do before — e.g. "This gave me a working correlation pipeline to test detection logic against, which I used in later projects (see 02-brute-force-investigation)."]

## Next Steps
[Optional — e.g. "Integrate osquery logs into this ELK pipeline for endpoint threat hunting."]

