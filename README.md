# Enterprise Threat Hunting Lab using Wazuh SIEM
A hands-on enterprise threat hunting lab built using **Wazuh SIEM**, **Windows 11 Enterprise**, and **Sysmon** to simulate real-world endpoint monitoring and security operations.  

## 📌 Project Overview

This project demonstrates how to build a Security Operations Center (SOC) lab using **Wazuh SIEM**, **Windows 11 Enterprise**, and **Sysmon**. The lab collects Windows endpoint telemetry, monitors security events, detects suspicious activities, maps alerts to the MITRE ATT&CK framework, and provides centralized visibility through Wazuh dashboards.

### Objectives

- Monitor Windows endpoint activity
- Collect Windows Event Logs and Sysmon telemetry
- Detect suspicious processes and security events
- Perform threat hunting using Wazuh
- Analyze alerts using dashboards
- Perform vulnerability assessment
- Review security configuration compliance
- Map detections to the MITRE ATT&CK framework

## 🏗️ Lab Architecture

```
                     +----------------------+
                     | Windows 11 Endpoint  |
                     |      + Sysmon        |
                     +----------+-----------+
                                |
                           Wazuh Agent
                                |
                                v
                     +----------------------+
                     |    Wazuh Server      |
                     | Manager + Indexer    |
                     | OpenSearch Dashboard |
                     +----------+-----------+
                                |
                                v
                 Threat Hunting & Security Monitoring
```
## 🛠️ Technologies Used

| Technology | Purpose |
|------------|---------|
| Wazuh 4.12 | SIEM and Threat Detection |
| Windows 11 Enterprise | Monitored Endpoint |
| Sysmon | Advanced Windows Event Logging |
| OpenSearch Dashboards | Alert Visualization |
| Windows Event Logs | Security Event Collection |
| MITRE ATT&CK | Threat Classification |
