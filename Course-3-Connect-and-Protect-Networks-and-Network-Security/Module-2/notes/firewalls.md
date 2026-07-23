# Firewalls & Proxy Servers Notes

> **Google Cybersecurity Professional Certificate**  
> **Course 2 – Module 6**

---

# 📖 Overview

This lesson introduces **firewalls**, one of the most important network security controls used to protect systems from unauthorized access and cyber threats. It also explains different firewall types, how they operate, and the role of **proxy servers** in improving network security and privacy.

---

# 🎯 Learning Objectives

- Understand what a firewall is
- Learn the different types of firewalls
- Compare stateless and stateful firewalls
- Understand Next-Generation Firewalls (NGFWs)
- Learn how cloud firewalls work
- Understand the purpose of proxy servers

---

# 🔥 What is a Firewall?

A **firewall** is a network security device or software that monitors, filters, and controls incoming and outgoing network traffic based on predefined security rules.

### Primary Purpose

- Prevent unauthorized access
- Block malicious traffic
- Allow legitimate communication
- Protect networks and devices from cyber attacks

---

# 🖥️ Types of Firewalls

## 1. Hardware Firewall

A **hardware firewall** is a physical device placed between a network and the internet.

### Characteristics

- Inspects data packets before they enter the network
- Protects all connected devices
- Commonly used by businesses
- Serves as the first line of defense

### Advantages

- High performance
- Protects an entire network
- Difficult for attackers to bypass

---

## 2. Software Firewall

A **software firewall** is installed on a computer or server.

### Characteristics

- Runs as software
- Protects a single computer or server
- Filters incoming and outgoing traffic

### Advantages

- Easy to configure
- Individual device protection
- Can enforce application-specific rules

---

## 3. Cloud Firewall (Firewall as a Service - FaaS)

A **cloud-based firewall** is provided by a Cloud Service Provider (CSP).

### Characteristics

- Hosted in the cloud
- Protects cloud resources
- Can also secure on-premises networks
- Configured through cloud management platforms

### Advantages

- Highly scalable
- Easy deployment
- No physical hardware required
- Protects hybrid cloud environments

---

# Firewall Operation Types

Firewalls inspect network traffic in different ways.

---

## Stateless Firewall

A **stateless firewall** filters traffic using predefined rules.

### Characteristics

- Examines each packet independently
- Does not remember previous packets
- Does not track active connections

### Advantages

- Fast
- Low resource usage

### Disadvantages

- Less secure
- Cannot detect complex attacks
- Limited context for traffic analysis

---

## Stateful Firewall

A **stateful firewall** monitors active network connections.

### Characteristics

- Tracks connection state
- Remembers previous packets
- Makes filtering decisions using packet history

### Advantages

- More secure
- Better threat detection
- Filters suspicious traffic intelligently

---

## Next-Generation Firewall (NGFW)

A **Next-Generation Firewall (NGFW)** provides advanced protection beyond traditional firewalls.

### Features

- Stateful inspection
- Deep Packet Inspection (DPI)
- Intrusion Prevention System (IPS)
- Application awareness
- Threat intelligence integration
- Malware detection

### Benefits

- Detects sophisticated attacks
- Blocks advanced threats
- Improved visibility into network traffic
- Can integrate with cloud-based threat intelligence services

---

# Deep Packet Inspection (DPI)

NGFWs perform **Deep Packet Inspection**, allowing them to inspect not only packet headers but also packet contents.

This enables them to:

- Detect malware
- Block malicious applications
- Identify suspicious behavior
- Improve network security

---

# Intrusion Prevention

Many NGFWs include an **Intrusion Prevention System (IPS)**.

An IPS can:

- Detect malicious activity
- Block attacks automatically
- Prevent exploitation attempts
- Reduce security risks

---

# Cloud-Based Threat Intelligence

Modern NGFWs can connect to cloud threat intelligence services.

Benefits include:

- Real-time threat updates
- Recognition of newly discovered malware
- Automatic policy updates
- Improved protection against emerging cyber threats

---

# Proxy Servers

A **proxy server** acts as an intermediary between a client device and the internet.

Instead of communicating directly with a website:

```
User
   ↓
Proxy Server
   ↓
Internet
```

The proxy receives requests from the user and forwards them to the destination.

---

## Benefits of Proxy Servers

- Hide internal IP addresses
- Improve user privacy
- Filter web traffic
- Block malicious websites
- Monitor internet activity
- Improve security

---

# Firewall Comparison

| Firewall Type | Description | Security Level |
|---------------|-------------|----------------|
| Hardware Firewall | Physical network security device | ⭐⭐⭐⭐ |
| Software Firewall | Installed on individual computers or servers | ⭐⭐⭐ |
| Cloud Firewall (FaaS) | Cloud-hosted firewall service | ⭐⭐⭐⭐ |
| Stateless Firewall | Filters packets independently using rules | ⭐⭐ |
| Stateful Firewall | Tracks active connections and packet history | ⭐⭐⭐⭐ |
| Next-Generation Firewall (NGFW) | Advanced firewall with DPI and intrusion prevention | ⭐⭐⭐⭐⭐ |

---

# Comparison: Stateless vs Stateful Firewalls

| Feature | Stateless | Stateful |
|---------|-----------|-----------|
| Tracks Connections | ❌ No | ✅ Yes |
| Stores Session Information | ❌ No | ✅ Yes |
| Security | Lower | Higher |
| Performance | Faster | Slightly Slower |
| Detects Complex Threats | ❌ Limited | ✅ Better |

---

# Key Terms

| Term | Definition |
|------|------------|
| **Firewall** | A security device or software that filters network traffic |
| **Hardware Firewall** | A physical firewall protecting an entire network |
| **Software Firewall** | Firewall software installed on a computer or server |
| **Cloud Firewall (FaaS)** | Firewall service hosted by a cloud provider |
| **Stateless Firewall** | Filters packets without remembering previous traffic |
| **Stateful Firewall** | Tracks active connections to make smarter filtering decisions |
| **Next-Generation Firewall (NGFW)** | Advanced firewall with deep packet inspection and intrusion prevention |
| **Deep Packet Inspection (DPI)** | Examines both packet headers and contents |
| **Intrusion Prevention System (IPS)** | Detects and blocks malicious activity automatically |
| **Proxy Server** | An intermediary server that forwards requests between clients and the internet |

---

# Key Takeaways

- A **firewall** filters network traffic based on security rules.
- **Hardware firewalls** protect entire networks.
- **Software firewalls** protect individual devices or servers.
- **Cloud firewalls (FaaS)** secure cloud and hybrid environments.
- **Stateless firewalls** inspect packets independently and provide basic protection.
- **Stateful firewalls** track active connections, making them more secure.
- **Next-Generation Firewalls (NGFWs)** add advanced features like **Deep Packet Inspection (DPI)**, **Intrusion Prevention Systems (IPS)**, and cloud threat intelligence.
- **Proxy servers** improve privacy and security by acting as intermediaries between users and the internet.

---

## ✅ Lesson Complete

✔ Learned about firewall types

✔ Compared stateless and stateful firewalls

✔ Explored Next-Generation Firewalls (NGFWs)

✔ Understood Deep Packet Inspection (DPI)

✔ Learned the role of proxy servers in network security