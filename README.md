# Hello, I'm David

<a href="https://www.linkedin.com/in/david-l-59a650369/">
  <img src="https://img.shields.io/badge/LinkedIn-0072b1?style=for-the-badge&logo=linkedin&logoColor=white" />
</a>

I'm a cybersecurity student building hands-on experience in defensive security operations. My focus is on the practical skills that matter in SOC environments: analyzing network traffic, investigating logs, tuning detection rules, and automating repetitive analyst tasks.

I work primarily with open-source security tools (Wazuh, Suricata, Wireshark) and I'm developing automation workflows that integrate threat intelligence APIs into detection pipelines. My goal is to understand how attacks look at the packet and log level, and build defenses that catch them.

**Currently pursuing:** CompTIA Security+ 

---

## Career Focus

**Target Role:** SOC Analyst > Security Analyst > Detection Engineer

I'm building toward a career in blue-team operations with a long-term focus on detection engineering. Right now I'm focused on mastering the fundamentals (log analysis, network forensics, incident documentation) while developing the automation and scripting skills that separate Tier 1 analysts from engineers.

---

## Featured Projects

### [Wazuh SIEM + VirusTotal Integration](https://github.com/dlpz-SEC/Wazuh-SIEM-automation-lab)
`Wazuh` `VirusTotal API` `Python` `Automated Enrichment`

Automated alert enrichment pipeline that queries VirusTotal for file hash reputation data when Wazuh generates alerts. Reduces manual IOC lookups and adds threat context directly to alert metadata.

---

### [SOC Threat Hunting Lab](https://github.com/dlpz-SEC/soc-threat-hunting-lab)
`SQL` `Log Analysis` `Threat Detection` `Investigation Queries`

Lab environment with security event datasets for writing investigative queries. Scenarios include detecting brute-force patterns, identifying anomalous login times, and correlating events across multiple log sources.

---

### [Detection-as-Code Pipeline](https://github.com/dlpz-SEC/detection-as-code)
`GitHub Actions` `Sigma Rules` `Python` `CI/CD` `Infrastructure as Code`

Building a version-controlled detection engineering workflow. Detection rules are written as code, validated through automated testing, and deployed via CI/CD pipeline. Enables rapid iteration, peer review of detection logic, and rollback capabilities when rules cause false positives.

**Key Components:**
- Sigma rule development and conversion
- GitHub Actions for automated rule validation
- Python-based rule testing framework
- Version control for detection rule lifecycle

**Status:** In Development

---

### [ADTE (Azure Sentinel Triage Engine)](https://github.com/dlpz-SEC/adte-azure-sentinel-triage-engine)
`Azure Sentinel` `Logic Apps` `Azure Functions` `Python` `SOAR`

Automated alert triage engine to reduce alert fatigue and accelerate incident response. The engine enriches incoming alerts with threat intelligence, auto-closes known false positives based on defined criteria, and escalates high-fidelity alerts with contextual data attached.

**Key Components:**
- Azure Logic Apps for orchestration workflows
- Azure Functions (Python) for enrichment logic
- Sentinel API integration for alert ingestion
- Threat intel enrichment from external feeds

---

## Core Skills & Associated Projects

| **Core Skill Area** | **Associated Projects** |
|----------------------|--------------------------|
| **SIEM & Security Automation** | • [Wazuh SIEM + VirusTotal Integration](https://github.com/dlpz-SEC/Wazuh-SIEM-automation-lab)<br>• [ADTE - Azure Sentinel Triage Engine](https://github.com/dlpz-SEC/adte-azure-sentinel-triage-engine) |
| **Detection Engineering** | • [Detection-as-Code Pipeline](https://github.com/dlpz-SEC/detection-as-code) |
| **SQL-Based Threat Hunting** | • [SOC Threat Hunting Lab](https://github.com/dlpz-SEC/soc-threat-hunting-lab) |
| **Network Analysis & Attack Detection** | • [SYN Flood Attack Incident Report](https://github.com/dlpz-SEC/Incident-Report)<br>• [Wireshark Packet Analysis](https://github.com/dlpz-SEC/Wireshark-Packet-Analysis)<br>• [tcpdump Packet Capture & Analysis](https://github.com/dlpz-SEC/tcpdump-packet-capture-analysis) |
| **Intrusion Detection & Log Analysis** | • [Suricata IDS Lab *(signature tuning + log investigation)*](https://github.com/dlpz-SEC/Suricata-IDS-Lab) |
| **Incident Response & Documentation** | • [Incident Handler's Journal](https://github.com/dlpz-SEC/Incident-Report)<br>• Phishing IR Playbook Execution *(IOC review + response steps)* · `In Progress` |
| **Risk & Threat Modeling** | • PASTA Framework Case Study · `In Progress` |
| **Governance, Risk & Compliance (GRC)** | • Botium Toys Security Audit *(controls, compliance, safeguards)* · `In Progress` |
| **Email Security & Phishing Analysis** | • Malicious Email Filtering *(headers, URLs, IOC triage)* · `In Progress` |
| **Malware & IOC Investigation** | • Suspicious File Hash Investigation *(OSINT + threat intelligence)* · `In Progress` |
| **Vulnerability & Threat Identification** | • USB Attack Vector Assessment *(physical attack simulation)* · `In Progress` |
| **System Hardening & Defense** | • Network Hardening Solutions · `In Progress` |
| **Security Automation (Python)** | • Python Log Parsing & IOC Extraction · `In Progress` |
| **Cryptography & Encryption** | • Encryption & Decryption Workflow · `In Progress` |
| **Security Framework Applications** | • CIA Triad Workplace Scenario Application · `In Progress`<br>• Risk Scoring Using NIST Concepts · `In Progress` |

---

## Tools

### Network Monitoring & Traffic Analysis
<div>
    <img src="https://img.shields.io/badge/-Wireshark-1679A7?&style=for-the-badge&logo=Wireshark&logoColor=white" />
    <img src="https://img.shields.io/badge/-Suricata-EF3B2D?&style=for-the-badge&logo=Suricata&logoColor=white" />
    <img src="https://img.shields.io/badge/-Zeek-777BB4?&style=for-the-badge&logo=Zeek&logoColor=white" />
    <img src="https://img.shields.io/badge/-tcpdump-333333?&style=for-the-badge&logo=gnu-bash&logoColor=white" />
</div>

**Analyzing network traffic to detect and investigate security incidents:**
- Captured and analyzed SYN flood DoS attacks, documenting packet-level IOCs
- Built Wireshark display filters to isolate suspicious DNS queries, beaconing patterns, and cleartext credential exposure
- Configured Suricata IDS with custom alert rules for threat-specific traffic signatures
- Used Zeek to generate connection logs and extract metadata for timeline reconstruction
- Performed pcap analysis to support incident response documentation

---

### SIEM & Detection Platforms
<div>
    <img src="https://img.shields.io/badge/-Wazuh-3C99DC?&style=for-the-badge&logo=wazuh&logoColor=white" />
    <img src="https://img.shields.io/badge/-Azure_Sentinel-0078D4?&style=for-the-badge&logo=microsoft-azure&logoColor=white" />
</div>

**Deploying and configuring SIEM platforms for centralized security monitoring.**
- Deployed Wazuh for centralized log collection, alert generation, and endpoint visibility
- Building Azure Sentinel integrations for automated alert triage and threat hunting
- Configured alert rules and dashboards for security event monitoring
- Integrating threat intelligence feeds for automated IOC enrichment

---

### SOAR & Security Automation
<div>
    <img src="https://img.shields.io/badge/-Azure_Logic_Apps-0078D4?&style=for-the-badge&logo=microsoft-azure&logoColor=white" />
    <img src="https://img.shields.io/badge/-Azure_Functions-0062AD?&style=for-the-badge&logo=azure-functions&logoColor=white" />
    <img src="https://img.shields.io/badge/-GitHub_Actions-2088FF?&style=for-the-badge&logo=github-actions&logoColor=white" />
</div>

**Building automation workflows to reduce manual analyst workload.**
- Developing Logic Apps workflows for alert orchestration and automated response
- Building Azure Functions (Python) for threat intel enrichment
- Implementing GitHub Actions for detection rule CI/CD pipelines
- Automating IOC lookups via VirusTotal API integration

---

### Operating Systems & Command Line (Linux)
<div>
    <img src="https://img.shields.io/badge/-Linux-FCC624?&style=for-the-badge&logo=linux&logoColor=black" />
    <img src="https://img.shields.io/badge/-Bash-121011?&style=for-the-badge&logo=gnubash&logoColor=white" />
    <img src="https://img.shields.io/badge/-nano-4E9A06?&style=for-the-badge&logo=gnubash&logoColor=white" />
    <img src="https://img.shields.io/badge/-APT_Package_Manager-5E5E5E?&style=for-the-badge&logo=debian&logoColor=white" />
</div>

**Linux administration and security-focused command line operations:**
- Audited file permissions and ownership to identify misconfigurations and privilege issues
- Parsed authentication logs (`/var/log/auth.log`) to detect brute-force attempts and unauthorized access
- Built Bash pipelines with `grep`, `awk`, and `cut` for log filtering and IOC extraction
- Managed user permissions using `chmod`, `chown`, and `umask` following least privilege principles
- Installed and configured security tools (Suricata, tcpdump, Wazuh agents) from command line
---

### Encryption & Key Management
<div>
    <img src="https://img.shields.io/badge/-AES-000000?&style=for-the-badge&logo=verizon&logoColor=white" />
    <img src="https://img.shields.io/badge/-RSA-008000?&style=for-the-badge&logoColor=white" />
    <img src="https://img.shields.io/badge/-PKI-003366?&style=for-the-badge&logoColor=white" />
</div>

**Applied cryptography concepts in security analysis and tool configuration:**
- Analyzed TLS handshakes in packet captures to verify encryption implementation
- Configured HTTPS and certificate validation for security tool deployments
- Evaluated encryption strength in vulnerability assessments (key length, cipher suites)

---

### File & Log Management
<div>
    <img src="https://img.shields.io/badge/-grep-005F87?&style=for-the-badge&logo=gnubash&logoColor=white" />
    <img src="https://img.shields.io/badge/-Filesystem_Hierarchy-333333?&style=for-the-badge&logo=linux&logoColor=white" />
</div>

**Investigating security events through log analysis:**
- Built regex patterns with `grep` to detect failed login clusters, privilege escalation attempts, and suspicious cron activity
- Analyzed `/var/log/auth.log`, `syslog`, and application logs to reconstruct incident timelines
- Correlated log entries across multiple sources to identify lateral movement indicators
- Extracted IOCs from raw logs for threat intelligence enrichment

---

### Databases & Query Languages
<div>
    <img src="https://img.shields.io/badge/-SQL-4479A1?&style=for-the-badge&logo=postgresql&logoColor=white" />
    <img src="https://img.shields.io/badge/-KQL-0078D4?&style=for-the-badge&logo=microsoft-azure&logoColor=white" />
    <img src="https://img.shields.io/badge/-Relational_DBs-336791?&style=for-the-badge&logo=sqlite&logoColor=white" />
</div>

**Writing investigative queries for threat detection and log analysis:**
- Built detection queries for brute-force patterns, anomalous login times, and privilege escalation attempts
- Correlated events across authentication logs, network logs, and endpoint telemetry
- Identified failed login clusters and account lockout patterns indicative of credential attacks
- Developing KQL queries for Azure Sentinel threat hunting and custom detection rules

---

### Scripting & Detection Engineering
<div>
    <img src="https://img.shields.io/badge/-Python-3776AB?&style=for-the-badge&logo=python&logoColor=white" />
    <img src="https://img.shields.io/badge/-Bash-121011?&style=for-the-badge&logo=gnubash&logoColor=white" />
    <img src="https://img.shields.io/badge/-Sigma_Rules-FF6600?&style=for-the-badge&logoColor=white" />
</div>

**Building automation scripts and detection logic for security operations:**
- Writing Python scripts to automate IOC extraction and API lookups
- Integrating VirusTotal API for automated hash reputation checks
- Developing Sigma rules for cross-platform detection logic
- Building log parsing utilities for security event analysis
- Implementing detection-as-code workflows with version control

---

### Frameworks & Governance
<div>
    <img src="https://img.shields.io/badge/-NIST_CSF-802000?&style=for-the-badge&logo=gov.uk&logoColor=white" />
    <img src="https://img.shields.io/badge/-MITRE_ATT%26CK-ED1C24?&style=for-the-badge&logoColor=white" />
</div>

**Applied the NIST Cybersecurity Framework (CSF) in simulated security environments:**
- Understood and applied the five core functions: Identify, Protect, Detect, Respond, Recover
- Used NIST CSF to guide internal security audits
- Created and evaluated policies and procedures around asset management and data handling
- Practiced aligning findings to CSF categories when recommending security improvements
- Map detected activity to MITRE ATT&CK techniques for threat classification

---

## Certifications

<div>
    <img src="https://img.shields.io/badge/-Google_Cybersecurity_Certificate-34A853?&style=for-the-badge&logo=Google&logoColor=white" />
    <img src="https://img.shields.io/badge/-CompTIA_Security%2B_(In_Progress)-FF0000?&style=for-the-badge&logo=CompTIA&logoColor=white" />
</div>

---

## Education

**Santa Barbara City College**  
Data Science & Computer Science  

---

## Currently Working On

- CompTIA Security+ certification 

---

<p align="center">
  <i>Open to entry-level SOC Analyst opportunities</i>
</p>
