# SOC Alerts & Active Directory Project

## Project Overview
This project focuses on integrating **SOC Alerts** with **Active Directory** to create an automated security monitoring and alerting system. The goal is to collect security logs, analyze them for potential threats, and send alerts to a central case management system for investigation.

## Tools & Technologies Used
- **Wazuh** (SIEM) – Security event and log analysis.
- **Splunk** – Log aggregation and monitoring.
- **TheHive** – Case management for incident tracking.
- **Ubuntu Server** – Hosting Splunk for log collection and analysis.
- **Active Directory** – User management and security auditing.

## Features
- Integrated **Wazuh** for security event detection and alerting.
- Configured **Splunk** to collect and visualize logs from an **Active Directory** environment.
- Set up **TheHive** for incident management and response coordination.
- **Real-time alerting** based on security events from Active Directory.

## Project Walkthrough
1. **Setup**:
   - Installed and configured **Wazuh** to monitor security logs.
   - Configured **Splunk** to ingest data from **Active Directory**.
   - Connected **TheHive** to handle incident cases.
2. **Security Event Detection**:
   - Monitored **Active Directory** activities using **Wazuh**.
   - Alerts generated for suspicious activities, such as unauthorized logins or privilege escalations.
3. **Incident Management**:
   - **TheHive** was used to create cases and track the progress of investigation and remediation.

## Screenshots
![SOC Alerts Screenshot](https://github.com/danielcarter7123/SOC-Alerts-Active-Directory-Project/blob/main/your-screenshot.png)

## Conclusion
This project demonstrates how integrating SIEM tools like **Wazuh** and **Splunk** with **Active Directory** can help monitor and respond to security incidents. It provides a solid foundation for building automated security monitoring solutions in enterprise environments.


