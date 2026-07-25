# Enterprise-Threat-Hunting-Lab-using-Wazuh-SIEM
A hands-on Enterprise Threat Hunting Lab built using Wazuh SIEM, Windows 11 Endpoint, and Sysmon for endpoint visibility and threat detection.  This project demonstrates endpoint monitoring, Windows event collection, MITRE ATT&CK mapping, vulnerability assessment, security configuration assessment, and threat hunting using Wazuh.  

# 📌 Project Overview

This lab simulates an enterprise SOC environment where a Windows endpoint is monitored by a Wazuh server.

The objective was to:

- Deploy Wazuh SIEM
- Register Windows Endpoint
- Install Sysmon
- Collect Windows Event Logs
- Monitor Security Events
- Perform Threat Hunting
- Detect Discovery Activities
- Detect Suspicious Processes
- Map Alerts to MITRE ATT&CK
- Analyze Endpoint Security
- Perform Vulnerability Assessment
- Perform Security Configuration Assessment

---

# 🏗️ Architecture

```
                 +------------------------+
                 |     Wazuh Server       |
                 |------------------------|
                 | Wazuh Manager          |
                 | Wazuh Indexer          |
                 | OpenSearch Dashboard   |
                 +-----------+------------+
                             |
                      Wazuh Agent
                             |
                +------------+------------+
                | Windows 11 Endpoint     |
                |-------------------------|
                | Sysmon                  |
                | Event Logs              |
                | Security Events         |
                +-------------------------+
```

---

# 🛠️ Technologies Used

- Wazuh SIEM v4.12
- Windows 11 Enterprise
- Ubuntu Server
- Sysmon
- Windows Event Logs
- OpenSearch Dashboard
- MITRE ATT&CK Framework
- CIS Benchmark
- Linux
- Command Prompt

---
# ⚙️ Lab Setup

## Wazuh Components

- Wazuh Manager
- Wazuh Indexer
- Wazuh Dashboard

## Endpoint

- Windows 11 Enterprise Evaluation
- Wazuh Agent
- Sysmon Installed
# 🔍 Threat Hunting Activities

The following detections were successfully monitored:

✅ Suspicious svchost.exe Process

✅ Discovery Activity Executed

✅ Windows Process Creation Events

✅ Windows Event ID Monitoring

✅ Endpoint Activity Monitoring

---
# 🧠 MITRE ATT&CK Coverage

The lab generated detections mapped to MITRE ATT&CK techniques including:

- Discovery
- Privilege Escalation
- Defense Evasion
- Persistence
- Lateral Movement

---
# 🛡️ Security Features

- Endpoint Monitoring
- Process Monitoring
- Event Collection
- Windows Security Logging
- Vulnerability Detection
- Security Configuration Assessment
- MITRE ATT&CK Mapping
- Compliance Dashboard

---
# 🧪 Validation Commands

The following Windows commands were executed to validate endpoint information.

```powershell
whoami
hostname
ipconfig /all
tasklist
net user
systeminfo
```

---

# 📈 Results

Successfully deployed an enterprise-grade SIEM environment capable of:

- Collecting Windows Security Events
- Monitoring Endpoint Activities
- Detecting Suspicious Processes
- Detecting Discovery Activities
- Mapping alerts to MITRE ATT&CK
- Assessing Endpoint Vulnerabilities
- Evaluating Security Configuration Compliance
- Performing Threat Hunting using Wazuh

---

# 🚀 Skills Demonstrated

- Security Information and Event Management (SIEM)
- Threat Hunting
- Endpoint Detection
- Windows Security
- Wazuh Administration
- Sysmon
- Linux Administration
- Windows Event Analysis
- MITRE ATT&CK
- Vulnerability Assessment
- Security Configuration Assessment
- Incident Detection

---

# 👩‍💻 Author

Nabila

Cybersecurity Enthusiast | SOC Analyst Aspirant
