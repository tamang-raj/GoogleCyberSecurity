# Entry-Level Security Analyst Toolkit

Security analysts use a variety of technical tools to monitor systems, detect threats, investigate incidents, and protect organizational assets. Understanding these tools is a fundamental skill for anyone beginning a career in cybersecurity.

---

# Why Security Tools Matter

Organizations generate enormous amounts of security data every day.

Without specialized tools, security analysts would struggle to:

- Detect cyberattacks
- Investigate security incidents
- Identify vulnerabilities
- Monitor network activity
- Protect organizational assets

Security tools automate many of these tasks, allowing analysts to identify and respond to threats more efficiently.

---

# Security Information and Event Management (SIEM)

## What Is a SIEM?

A **Security Information and Event Management (SIEM)** system collects, organizes, and analyzes security logs from multiple devices and applications in real time.

Instead of manually reviewing thousands of log files, analysts use a SIEM dashboard to monitor an organization's entire environment.

---

## How SIEM Works

A SIEM system:

1. Collects logs from multiple systems.
2. Organizes and normalizes the data.
3. Correlates related security events.
4. Detects suspicious behavior.
5. Generates alerts for potential threats.

---

## What SIEM Tools Monitor

SIEM solutions can monitor:

- User logins
- Failed authentication attempts
- Firewall events
- Server activity
- Network devices
- Cloud services
- Applications
- Operating systems

---

## Benefits of SIEM

Security analysts use SIEM platforms to:

- Monitor critical activities
- Detect threats in real time
- Analyze filtered events and patterns
- Investigate security incidents
- Search for indicators of compromise (IOCs)
- Reduce manual log review
- Improve incident response

---

## SIEM Dashboards

Most SIEM tools display information through interactive dashboards.

Dashboards help analysts quickly identify:

- High-risk alerts
- Suspicious login attempts
- Malware activity
- Network anomalies
- Ongoing attacks

---

## SIEM Deployment Options

Organizations can deploy SIEM solutions:

### On-Premises

Installed and managed within the organization's own infrastructure.

### Cloud-Based

Hosted by cloud providers and accessed over the internet.

Cloud-based SIEM solutions are increasingly popular because they offer greater scalability and easier maintenance.

---

## Common SIEM Platforms

### Splunk

Features:

- Log collection
- Security dashboards
- Threat detection
- Search capabilities
- Reporting

---

### Google Chronicle

Features:

- Cloud-native architecture
- Threat hunting
- Large-scale log analysis
- Fast security investigations

---

# Network Protocol Analyzers (Packet Sniffers)

## Definition

A **network protocol analyzer**, also known as a **packet sniffer**, captures and analyzes data packets traveling across a network.

These tools allow analysts to inspect network communications in detail.

---

## What Packet Sniffers Capture

Packet analyzers record:

- Source IP addresses
- Destination IP addresses
- Network protocols
- Packet contents
- Connection information
- Timing information

---

## Uses

Security professionals use packet sniffers to:

- Monitor network traffic
- Detect malicious communications
- Investigate cyberattacks
- Troubleshoot network issues
- Analyze suspicious behavior

---

## Popular Packet Sniffers

### Wireshark

A graphical packet analysis tool widely used throughout the cybersecurity industry.

Capabilities include:

- Live packet capture
- Protocol analysis
- Traffic filtering
- Packet inspection

---

### tcpdump

A command-line packet analyzer commonly used on Linux and Unix systems.

Capabilities include:

- Packet capture
- Traffic filtering
- Lightweight network monitoring

---

# Playbooks

## What Is a Playbook?

A **playbook** is a documented guide that explains the operational actions security analysts should follow while performing security-related tasks.

Playbooks help ensure every incident is handled consistently and according to organizational procedures.

---

## Purpose of Playbooks

Playbooks help analysts:

- Follow standardized procedures
- Respond consistently
- Reduce mistakes
- Improve communication
- Document investigations
- Meet compliance requirements

---

## When Playbooks Are Used

Playbooks guide analysts:

- Before an incident
- During an incident
- After an incident

---

# Types of Playbooks

## Incident Response Playbook

Provides step-by-step instructions for responding to security incidents.

Typical steps include:

- Identify the incident
- Contain the threat
- Eradicate malicious activity
- Recover systems
- Document findings

---

## Chain of Custody Playbook

### Purpose

Documents who has possession of digital evidence throughout an investigation.

Maintaining a proper chain of custody ensures that evidence remains trustworthy and admissible if needed for legal proceedings.

---

### Information Recorded

A chain of custody typically includes:

- Evidence description
- Date and time collected
- Person collecting the evidence
- Storage location
- Every transfer of possession
- Final disposition

---

## Why Chain of Custody Matters

Proper documentation:

- Prevents evidence tampering
- Preserves evidence integrity
- Supports legal investigations
- Maintains accountability

---

# Fragile and Volatile Digital Evidence

## What Is Digital Evidence?

Digital evidence includes any information stored electronically that may help investigate a security incident.

Examples include:

- System logs
- Memory contents
- Network captures
- Emails
- Files
- Browser history

---

## Volatile Evidence

Some digital evidence exists only while a system is powered on.

Examples include:

- RAM contents
- Active network connections
- Running processes
- Logged-in users

This information disappears when a device shuts down.

---

## Order of Volatility

Security professionals collect evidence according to the **order of volatility**, meaning they preserve the most temporary data first.

Typical order:

1. CPU registers and cache
2. RAM (memory)
3. Running processes
4. Network connections
5. Temporary files
6. Hard drive data
7. Backup media

---

# Preserving Digital Evidence

The first priority during an investigation is preserving evidence.

Security analysts should:

- Avoid modifying original evidence.
- Create forensic copies.
- Perform analysis on copied data.
- Document every action taken.
- Store evidence securely.

Improper handling can permanently alter evidence, making it unreliable or unusable.

---

# Example Investigation Workflow

A suspicious login alert appears in the SIEM.

### Step 1

The analyst reviews SIEM logs to identify unusual activity.

### Step 2

Using Wireshark, the analyst captures network traffic to investigate communication with external systems.

### Step 3

The analyst follows the incident response playbook to contain the threat.

### Step 4

Digital evidence is collected according to the order of volatility.

### Step 5

The chain of custody playbook is completed to document every person who handles the evidence.

---

# Comparison of Common Security Tools

| Tool | Purpose |
|------|---------|
| **Logs** | Record events occurring on systems and networks |
| **SIEM** | Collect, organize, analyze, and alert on log data |
| **Packet Sniffer** | Capture and analyze network traffic |
| **Playbook** | Document procedures for handling security tasks |
| **Chain of Custody Playbook** | Track possession and handling of digital evidence |

---

# Key Takeaways

- **SIEM (Security Information and Event Management)** tools collect and analyze log data to detect threats and provide real-time alerts.
- SIEM platforms help analysts monitor critical activities, investigate incidents, and reduce the time spent reviewing logs manually.
- Popular SIEM platforms include **Splunk** and **Google Chronicle**.
- **Network protocol analyzers (packet sniffers)** such as **Wireshark** and **tcpdump** capture and analyze network traffic for troubleshooting and threat detection.
- **Playbooks** provide standardized procedures for responding to security incidents and performing operational tasks.
- The **Chain of Custody Playbook** ensures digital evidence is properly documented and protected throughout an investigation.
- **Volatile digital evidence** should be preserved immediately because it may disappear when a system powers off.
- Analysts should always preserve original evidence, create forensic copies, and conduct investigations using the copies to maintain evidence integrity.