# Network Security Review Notes

> **Google Cybersecurity Professional Certificate**  
> **Course 2 – Module 6**

---

# 📖 Overview

This review summarizes the key concepts covered in network security, including **network protocols, Wi-Fi security, firewalls, proxy servers, and Virtual Private Networks (VPNs).** These technologies work together to protect networks, devices, and data from unauthorized access and cyber threats.

---

# 🎯 Learning Objectives

- Review network protocols and their categories
- Understand Wi-Fi security protocols
- Review firewall types
- Understand proxy servers and Network Address Translation (NAT)
- Review how VPNs protect data

---

# 🌐 Network Protocols

A **network protocol** is a set of rules that defines how devices communicate over a network.

Protocols ensure that data is:

- Sent correctly
- Received correctly
- Delivered in the proper order
- Understood by different devices

---

## Categories of Network Protocols

### 1. Communication Protocols

Communication protocols handle the transmission of data between devices.

Examples:

- **TCP (Transmission Control Protocol)** – Reliable, connection-oriented communication
- **UDP (User Datagram Protocol)** – Faster, connectionless communication
- **SMTP (Simple Mail Transfer Protocol)** – Sends email

---

### 2. Management Protocols

Management protocols monitor, manage, and troubleshoot networks.

Example:

- **ICMP (Internet Control Message Protocol)** – Reports network errors and helps troubleshoot connectivity

---

### 3. Security Protocols

Security protocols protect data while it is being transmitted.

Examples:

- **IPSec (Internet Protocol Security)** – Secures IP communications
- **SSL/TLS (Secure Sockets Layer / Transport Layer Security)** – Encrypts data transmitted over networks

---

# Wi-Fi Security

Wireless networks use security protocols to protect communications.

## WEP (Wired Equivalent Privacy)

- Introduced in 1999
- First Wi-Fi security protocol
- Now considered insecure due to known vulnerabilities

---

## WPA (Wi-Fi Protected Access)

- Introduced in 2003
- Improved security over WEP
- Uses TKIP encryption

---

## WPA2

- Introduced in 2004
- Uses AES encryption
- Current standard in many wireless networks

---

## WPA3

- Introduced in 2018
- Protects against KRACK attacks
- Uses Simultaneous Authentication of Equals (SAE)
- Provides stronger encryption than WPA2

---

# Firewalls

A **firewall** monitors and filters network traffic based on security rules.

Its primary purpose is to block unauthorized or malicious traffic while allowing legitimate communications.

---

## Types of Firewalls

### Stateless Firewall

- Uses predefined rules
- Does not track previous network connections
- Less secure than stateful firewalls

---

### Stateful Firewall

- Tracks active network connections
- Filters traffic based on connection state and behavior
- Provides stronger protection

---

### Next-Generation Firewall (NGFW)

Provides advanced protection by including:

- Deep Packet Inspection (DPI)
- Intrusion Prevention
- Threat intelligence integration

---

# Proxy Servers

A **proxy server** acts as an intermediary between internal clients and external networks.

It provides an additional layer of security by filtering and forwarding network traffic.

---

## Network Address Translation (NAT)

Proxy servers use **Network Address Translation (NAT)** to hide internal IP addresses.

Benefits include:

- Protecting internal devices
- Concealing private network information
- Reducing exposure to external threats

---

## Forward Proxy

A **forward proxy** handles requests from internal users to external resources.

Functions:

- Filters outgoing traffic
- Hides users' IP addresses
- Controls internet access

---

## Reverse Proxy

A **reverse proxy** handles requests from external users to internal servers.

Functions:

- Filters incoming traffic
- Protects internal servers
- Prevents direct access to confidential resources

---

# Virtual Private Network (VPN)

A **Virtual Private Network (VPN)** protects communications over public networks.

VPNs encrypt data before transmission, making it unreadable to unauthorized users.

---

## VPN Features

### Encryption

Protects sensitive data while it travels across the internet.

---

### IP Address Masking

VPNs disguise a user's public IP address, improving privacy and making it more difficult to identify the user's location.

---

### Encapsulation

VPNs use **encapsulation** by wrapping encrypted data inside another data packet before transmission.

This protects the original data while it travels across public networks.

---

# Network Security Summary

| Technology | Primary Purpose |
|------------|-----------------|
| Network Protocols | Enable communication between devices |
| Communication Protocols | Transfer data across networks |
| Management Protocols | Monitor and troubleshoot networks |
| Security Protocols | Protect data during transmission |
| Firewall | Monitor and filter network traffic |
| Stateless Firewall | Filters traffic using predefined rules |
| Stateful Firewall | Tracks connections and filters traffic dynamically |
| Next-Generation Firewall (NGFW) | Provides advanced inspection and intrusion prevention |
| Proxy Server | Acts as an intermediary between clients and external networks |
| NAT | Hides internal IP addresses |
| Forward Proxy | Protects users and manages outgoing traffic |
| Reverse Proxy | Protects internal servers from external requests |
| VPN | Encrypts communications over public networks |
| Encapsulation | Wraps encrypted data inside another packet for secure transmission |

---

# Key Terms

| Term | Definition |
|------|------------|
| **Network Protocol** | A set of rules that governs communication between devices on a network |
| **Communication Protocol** | A protocol used to transfer data between devices |
| **Management Protocol** | A protocol used to monitor and manage network operations |
| **Security Protocol** | A protocol used to secure data during transmission |
| **Firewall** | A security device or software that filters network traffic |
| **Stateless Firewall** | A firewall that filters traffic using predefined rules without tracking connections |
| **Stateful Firewall** | A firewall that tracks network connections before allowing traffic |
| **Next-Generation Firewall (NGFW)** | An advanced firewall with deep packet inspection and intrusion prevention capabilities |
| **Proxy Server** | An intermediary server that filters and forwards network traffic |
| **Network Address Translation (NAT)** | A process that replaces private IP addresses with a public IP address |
| **Forward Proxy** | A proxy server that manages requests from internal users to external resources |
| **Reverse Proxy** | A proxy server that manages requests from external users to internal servers |
| **Virtual Private Network (VPN)** | A technology that encrypts network traffic and hides a user's IP address |
| **Encapsulation** | The process of wrapping encrypted data inside another packet before transmission |

---

# Key Takeaways

- **Network protocols** define how devices communicate and are grouped into **communication, management, and security protocols**.
- **Wi-Fi security** has evolved from **WEP** to **WPA**, **WPA2**, and **WPA3**, with each version providing stronger protection.
- **Firewalls** inspect and filter network traffic. **Stateless firewalls** rely on predefined rules, **stateful firewalls** track active connections, and **NGFWs** provide advanced threat protection.
- **Proxy servers** improve security by filtering traffic and using **Network Address Translation (NAT)** to conceal internal IP addresses. **Forward proxies** manage outgoing requests, while **reverse proxies** protect internal servers from incoming traffic.
- **VPNs** secure communications by **encrypting data**, **masking public IP addresses**, and using **encapsulation** to protect information sent across public networks.

---

## ✅ Module Review Complete

✔ Reviewed network protocols

✔ Reviewed Wi-Fi security standards

✔ Reviewed firewall technologies

✔ Reviewed proxy servers and NAT

✔ Reviewed VPNs and encapsulation

✔ Consolidated key concepts from the Network Security module