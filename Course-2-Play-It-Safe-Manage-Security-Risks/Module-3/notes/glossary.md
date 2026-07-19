# Security Information and Event Management (SIEM) Tools
## Google Cybersecurity Professional Certificate
### Course 2 - Module 3 Notes

---

# 📚 Module Overview

This module introduces **Security Information and Event Management (SIEM)** tools and explains how cybersecurity analysts use log data to detect, investigate, and respond to security incidents. It also covers SIEM dashboards, popular SIEM platforms, and the future of security monitoring with automation and AI.

---

# 🎯 Learning Objectives

By completing this module, I learned how to:

- Understand what logs are and why they are important.
- Identify common log sources.
- Explain how SIEM tools collect and analyze logs.
- Understand SIEM dashboards and their metrics.
- Compare different SIEM platforms.
- Differentiate between open-source and proprietary security tools.
- Explore the future of SIEM with cloud computing, AI, and SOAR.

---

# 📖 Common Log Sources

## Firewall Logs
- Record incoming and outgoing network connections.
- Monitor blocked and allowed traffic.
- Detect suspicious connection attempts.

### Example
```
Incoming connection from 192.168.1.15
Action: Blocked
Port: 22
```

---

## Network Logs

Track:

- Devices joining the network
- Devices leaving the network
- Internal communications
- Network services

Used to identify:

- Unauthorized devices
- Unusual network activity
- Potential attacks

---

## Server Logs

Record events related to servers, including:

- Website access
- Email services
- File sharing
- Login attempts
- Password requests

Useful for:

- Monitoring authentication
- Detecting failed logins
- Investigating security incidents

---

# What is SIEM?

**Security Information and Event Management (SIEM)** is a platform that collects, analyzes, and correlates security logs from multiple systems to detect and respond to threats.

## SIEM Features

- Centralized log collection
- Real-time monitoring
- Event correlation
- Automated alerts
- Faster investigations
- Reduced manual work

---

# How SIEM Works

```
Devices
     │
     ▼
Generate Logs
     │
     ▼
SIEM Collects Logs
     │
     ▼
Indexes & Correlates Events
     │
     ▼
Detects Threats
     │
     ▼
Creates Alerts
     │
     ▼
Security Analyst Investigates
```

---

# SIEM Dashboards

SIEM dashboards provide visual representations of security data.

Instead of reading thousands of logs manually, analysts can quickly view:

- Charts
- Graphs
- Tables
- Alerts
- Trends
- Metrics

---

## Dashboard Benefits

- Faster investigations
- Easier visualization
- Trend identification
- Real-time monitoring
- Improved incident response

---

## Dashboard Metrics

Common metrics include:

- Response Time
- Failure Rate
- Availability
- Number of Alerts
- Failed Login Attempts
- Active Threats

---

# Example Investigation

Suppose an employee account shows:

- Login from Nepal
- Five minutes later login from Germany

The SIEM dashboard immediately highlights:

- Login locations
- Login times
- Device information
- Timeline

This helps analysts quickly identify suspicious activity.

---

# Future of SIEM

Modern SIEM platforms are becoming more powerful through:

## Cloud Computing

Benefits:

- Scalability
- Flexibility
- Lower infrastructure costs

---

## Artificial Intelligence (AI)

AI improves:

- Threat detection
- Pattern recognition
- Risk analysis
- Alert prioritization

---

## Machine Learning (ML)

ML enables SIEM to:

- Learn normal behavior
- Detect anomalies
- Improve detection accuracy over time

---

## Internet of Things (IoT)

As IoT devices increase:

- More logs are generated.
- SIEM platforms must handle larger datasets.
- Better monitoring becomes essential.

---

## SOAR

**Security Orchestration, Automation, and Response (SOAR)** automates repetitive security tasks.

Examples:

- Isolating infected devices
- Blocking malicious IPs
- Opening incident tickets
- Sending alerts
- Executing response playbooks

Benefits:

- Faster response
- Less manual effort
- Improved efficiency

---

# Types of SIEM Tools

## Self-hosted SIEM

Installed and managed by the organization.

### Advantages

- Full control
- Better data privacy
- Customizable

### Disadvantages

- Higher cost
- Requires maintenance
- Infrastructure responsibility

---

## Cloud-hosted SIEM

Managed by the service provider.

### Advantages

- Easy deployment
- Lower maintenance
- Automatic updates
- Scalable

### Disadvantages

- Less infrastructure control
- Internet dependency

---

# Popular SIEM Platforms

## Splunk Enterprise

Type:
- Self-hosted

Features:

- Log retention
- Search capabilities
- Data analysis
- Real-time alerts

---

## Splunk Cloud

Type:
- Cloud-hosted

Features:

- Log collection
- Monitoring
- Searching
- Cloud scalability

Ideal for:

- Hybrid environments
- Cloud-first organizations

---

## Google Chronicle

Type:
- Cloud-native

Features:

- Massive log storage
- Fast searching
- Security analytics
- Threat detection

Advantages:

- Built on Google Cloud
- High scalability
- Fast investigations

---

# Open-source vs Proprietary Tools

## Open-source Tools

Characteristics:

- Free
- Community-developed
- Customizable
- Transparent source code

Examples:

- Linux
- Suricata

### Advantages

- Cost-effective
- Flexible
- Community support
- Rapid vulnerability fixes

---

## Proprietary Tools

Characteristics:

- Paid
- Commercial support
- Closed source

Examples:

- Splunk
- Google Chronicle (Google SecOps)

### Advantages

- Vendor support
- Regular updates
- Enterprise features

---

# SIEM Dashboards

## Splunk Security Posture Dashboard

Used by:

Security Operations Centers (SOC)

Displays:

- Security events
- Trends
- Threat activity
- Alerts

Purpose:

Real-time security monitoring.

---

## Splunk Risk Analysis Dashboard

Shows risk scores for:

- Users
- Devices
- IP addresses

Helps prioritize:

- High-risk assets
- Threat investigations

---

## Chronicle Enterprise Insights Dashboard

Displays:

- Recent alerts
- Suspicious domains
- Indicators of Compromise (IoCs)
- Confidence scores
- Severity levels

---

## Chronicle User Sign-in Overview Dashboard

Monitors:

- User login behavior
- Login locations
- Authentication trends

Useful for detecting:

- Account compromise
- Impossible travel
- Suspicious sign-ins

---

# Key Terms

| Term | Definition |
|------|------------|
| Log | Record of events occurring within systems |
| SIEM | Platform that collects and analyzes security logs |
| SOAR | Automation platform for incident response |
| Chronicle | Google's cloud-native SIEM |
| Splunk Enterprise | Self-hosted SIEM |
| Splunk Cloud | Cloud-hosted SIEM |
| Metrics | Performance indicators like response time and failure rate |
| Incident Response | Process of identifying, containing, and recovering from attacks |
| Playbook | Manual describing operational response procedures |
| Operating System (OS) | Interface between hardware and the user |

---

# Key Takeaways

- Logs provide valuable security evidence.
- Firewall, network, and server logs are essential for investigations.
- SIEM platforms centralize and analyze security logs.
- Dashboards enable faster threat detection.
- Splunk and Chronicle are widely used SIEM solutions.
- Open-source tools are not inherently less secure than proprietary tools.
- Cloud computing, AI, ML, IoT, and SOAR are shaping the future of SIEM.
- Automation improves incident response while reducing manual workload.

---

# Module Summary

This module introduced the fundamentals of Security Information and Event Management (SIEM). I learned how organizations collect and analyze logs using SIEM platforms, explored common tools such as Splunk Enterprise, Splunk Cloud, and Google Chronicle, and understood how dashboards help analysts monitor threats in real time. I also learned about the growing role of cloud computing, AI, machine learning, IoT, and SOAR in modern cybersecurity operations, making threat detection and incident response faster, smarter, and more efficient.