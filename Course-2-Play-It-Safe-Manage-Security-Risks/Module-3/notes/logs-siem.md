# Common Log Sources and SIEM Tools

## 📖 Overview
This lesson introduces the importance of log analysis in cybersecurity. Security analysts rely on logs to detect threats, investigate incidents, and monitor the health of an organization's systems. It also explains how Security Information and Event Management (SIEM) tools simplify log collection and analysis.

---

# Common Log Sources

## 🔥 Firewall Logs
Firewall logs record network traffic that attempts to enter or leave an organization's network.

### They include:
- Incoming connection attempts
- Outgoing network traffic
- Allowed and blocked connections
- Source and destination IP addresses
- Connection status

### Purpose
- Detect unauthorized access attempts
- Monitor suspicious network activity
- Identify blocked attacks

---

## 🌐 Network Logs
Network logs record activity across an organization's network.

### They track:
- Devices connecting to the network
- Devices leaving the network
- Communication between internal devices
- Connections to services and applications

### Purpose
- Monitor network traffic
- Detect unusual device behavior
- Identify compromised systems

---

## 🖥️ Server Logs
Server logs record events occurring on servers.

### Examples include:
- Website activity
- Email server events
- File sharing activity
- Login attempts
- Password requests
- Service errors

### Purpose
- Troubleshoot server issues
- Detect unauthorized logins
- Monitor service availability

---

# Security Information and Event Management (SIEM)

## What is SIEM?

**Security Information and Event Management (SIEM)** is a security solution that collects, stores, analyzes, and monitors log data from multiple systems in one centralized location.

Instead of manually checking thousands of logs, analysts use SIEM tools to automatically process and analyze security events.

---

## Functions of a SIEM Tool

### 📥 Log Collection
Collects logs from:
- Firewalls
- Servers
- Applications
- Endpoints
- Network devices

---

### 📂 Centralized Storage
Stores logs in one location for easier investigation.

---

### 🔍 Log Analysis
Analyzes log data to identify:
- Suspicious activity
- Security incidents
- Patterns
- Threats

---

### ⚡ Real-Time Monitoring
Continuously monitors events across the organization.

---

### 🚨 Automated Alerts
Automatically notifies security teams when suspicious behavior is detected.

Examples:
- Multiple failed login attempts
- Malware detection
- Unusual network traffic
- Privilege escalation

---

### 📊 Event Correlation
Combines related events from different log sources to identify larger security incidents.

---

# Benefits of SIEM

- Centralizes security logs
- Saves analysts time
- Detects threats faster
- Provides real-time visibility
- Automates security monitoring
- Reduces manual log review
- Improves incident response

---

# Workflow

```
Systems & Devices
      │
      ▼
 Generate Logs
      │
      ▼
 SIEM Collects Logs
      │
      ▼
Indexes & Stores Data
      │
      ▼
Analyzes Events
      │
      ▼
Detects Threats
      │
      ▼
Sends Alerts
      │
      ▼
Security Analyst Investigates
```

---

# Key Terms

| Term | Definition |
|------|------------|
| **Log** | A record of events occurring within a system. |
| **Firewall Log** | Records allowed and blocked network connections. |
| **Network Log** | Tracks devices and communications across a network. |
| **Server Log** | Records server-related activities like logins and services. |
| **SIEM** | Security Information and Event Management; collects and analyzes logs for security monitoring. |
| **Real-Time Monitoring** | Continuous observation of security events as they happen. |
| **Automated Alert** | A notification generated automatically when suspicious activity is detected. |

---

# Key Takeaways

- Logs provide evidence of activity occurring on systems and networks.
- Firewall logs monitor incoming and outgoing network traffic.
- Network logs track devices and communications.
- Server logs record server events such as logins and service activity.
- SIEM tools centralize log collection from multiple sources.
- SIEM analyzes logs automatically, detects threats, and generates real-time alerts.
- Using SIEM significantly reduces manual effort and improves security monitoring.

---

## 🎯 Summary

Understanding log sources is a fundamental skill for cybersecurity analysts. Firewall, network, and server logs provide valuable insights into system activity, while SIEM tools collect, analyze, and correlate these logs to detect threats efficiently. By automating monitoring and alerting, SIEM enables faster incident detection and response, making it an essential component of modern cybersecurity operations.