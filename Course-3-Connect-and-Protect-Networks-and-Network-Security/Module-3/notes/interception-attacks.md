# Interception Attacks: Packet Sniffing & IP Spoofing

> **Google Cybersecurity Professional Certificate**  
> **Course 3 – Connect and Protect: Networks and Network Security**

![Topic](https://img.shields.io/badge/Topic-Interception%20Attacks-blue)
![Module](https://img.shields.io/badge/Module-3-success)
![Status](https://img.shields.io/badge/Notes-Complete-brightgreen)

---

# 📖 Overview

Interception attacks occur when a malicious actor secretly captures, monitors, or manipulates data as it travels across a network. Two of the most common interception attacks are **packet sniffing** and **IP spoofing**.

Attackers use these techniques to steal sensitive information, impersonate trusted devices, redirect network traffic, or launch denial-of-service attacks. Cybersecurity professionals defend against these threats using encryption, firewalls, network monitoring, and layered security controls.

---

# 🎯 Learning Objectives

After studying this topic, I can:

- Explain interception attacks
- Describe packet sniffing
- Understand Network Interface Card (NIC) promiscuous mode
- Explain IP spoofing
- Identify on-path (Man-in-the-Middle) attacks
- Understand Smurf attacks
- Explain how DoS attacks relate to IP spoofing
- Apply defensive strategies against interception attacks

---

# 🕵️ What Are Interception Attacks?

An **interception attack** occurs when an attacker secretly captures or manipulates data while it is traveling across a network.

The primary goal is to:

- Steal sensitive information
- Monitor communications
- Impersonate trusted systems
- Redirect network traffic
- Disrupt normal operations

---

# 📦 Packet Sniffing

Packet sniffing is the process of capturing and inspecting network packets as they travel across a network.

Although packet sniffing is commonly used by network administrators for troubleshooting, attackers use it to steal confidential information.

Captured information may include:

- Usernames
- Passwords
- Emails
- Financial information
- Authentication tokens
- IP addresses
- MAC addresses

---

# 💻 Network Interface Card (NIC)

A **Network Interface Card (NIC)** is the hardware component that allows a computer to communicate over a network.

Normally, a NIC only accepts packets addressed to its own MAC address.

---

## Promiscuous Mode

A NIC can be configured to operate in **promiscuous mode**.

In this mode, the NIC accepts **all network packets**, regardless of their destination.

### Why attackers use it

- Monitor all network traffic
- Capture sensitive information
- Collect IP addresses
- Collect MAC addresses
- Prepare for IP spoofing attacks

---

# 🛠️ Packet Sniffing Tools

One common packet-sniffing tool is:

- **Wireshark**

Attackers may use Wireshark to:

- Capture traffic
- Store packets
- Analyze communications
- Gather IP and MAC addresses

Security professionals also use Wireshark for legitimate troubleshooting and incident investigations.

---

# 🎭 IP Spoofing

IP spoofing occurs when an attacker impersonates another device by forging its IP address.

After collecting information through packet sniffing, attackers can pretend to be trusted devices.

### Objectives

- Bypass firewall rules
- Gain unauthorized access
- Hide their identity
- Launch additional attacks

---

# 🚨 On-Path (Man-in-the-Middle) Attack

An **On-path attack**, also known as a **Man-in-the-Middle (MitM)** attack, occurs when an attacker secretly places themselves between two trusted devices.

### The attacker can

- Intercept communications
- Read sensitive information
- Modify transmitted data
- Redirect traffic
- Impersonate either device

### Information at risk

- Usernames
- Passwords
- Personal information
- Banking details
- Business communications

---

# 🌐 DNS Redirection

During an on-path attack, attackers may redirect DNS requests.

Instead of sending users to the legitimate website, they are redirected to a malicious website designed to steal credentials or distribute malware.

---

# 💥 Smurf Attack

A **Smurf attack** combines **IP spoofing** with a **Denial of Service (DoS)** attack.

### How it works

1. The attacker spoofs the victim's IP address.
2. Broadcast requests are sent across the network.
3. Multiple devices respond simultaneously.
4. All responses are directed to the victim.
5. The victim's system becomes overwhelmed.

### Goal

Cause a denial of service by flooding the victim with network traffic.

---

# 🚫 Denial of Service (DoS)

A **Denial of Service (DoS)** attack prevents legitimate users from accessing systems or services.

Unlike interception attacks that focus on stealing information, DoS attacks focus on disrupting availability.

Attackers continuously send large numbers of packets until the target becomes overloaded or crashes.

Many DoS attacks use forged IP addresses to make blocking the attacker more difficult.

---

# 🛡️ Defending Against Interception Attacks

## Encryption

Encrypting data prevents attackers from reading intercepted communications.

Examples include:

- HTTPS
- TLS
- SSL
- VPNs

---

## Firewalls

Firewalls help defend against IP spoofing by:

- Rejecting unauthorized IP packets
- Filtering suspicious traffic
- Blocking spoofed addresses
- Monitoring abnormal network activity

---

## Defense-in-Depth

**Defense-in-depth** uses multiple security controls together rather than relying on a single solution.

Examples include:

- Encryption
- Firewalls
- Intrusion detection systems
- Network monitoring
- Secure authentication
- VPNs

---

# 📊 Packet Sniffing vs IP Spoofing

| Packet Sniffing | IP Spoofing |
|-----------------|-------------|
| Captures network traffic | Forges IP addresses |
| Reads transmitted data | Impersonates trusted devices |
| Collects IP and MAC addresses | Uses stolen addresses |
| Often the first stage of an attack | Often follows packet sniffing |

---

# 📚 Key Terms

| Term | Definition |
|------|------------|
| **Interception Attack** | An attack that captures or manipulates data while it is being transmitted across a network. |
| **Packet Sniffing** | Capturing and analyzing network packets. |
| **NIC (Network Interface Card)** | Hardware that enables network communication. |
| **Promiscuous Mode** | A NIC setting that captures all network traffic. |
| **Wireshark** | A popular network protocol analyzer used to capture and inspect packets. |
| **IP Spoofing** | Forging the source IP address to impersonate another device. |
| **On-Path (MitM) Attack** | An attacker intercepts communication between two trusted devices. |
| **Smurf Attack** | A DoS attack that combines IP spoofing with broadcast traffic to overwhelm a victim. |
| **Defense-in-Depth** | Using multiple layers of security controls to protect systems and networks. |

---

# 🎯 Key Takeaways

- Interception attacks target data while it is in transit.
- Packet sniffing captures and analyzes network traffic.
- Promiscuous mode allows a NIC to capture all packets on a network.
- Wireshark is commonly used for packet analysis by both defenders and attackers.
- IP spoofing disguises an attacker's identity by forging IP addresses.
- On-path attacks intercept communications between trusted devices.
- Smurf attacks combine IP spoofing with DoS techniques.
- Encryption, firewalls, and defense-in-depth significantly reduce the risk of interception attacks.

---

# 📝 Summary

Interception attacks are among the most common network threats faced by organizations. Attackers often begin with **packet sniffing** to collect sensitive information such as IP addresses, MAC addresses, usernames, and passwords. They may then use **IP spoofing** to impersonate trusted systems or perform **on-path attacks** and **Smurf attacks**. Security professionals defend against these threats through **encryption**, **firewalls**, **network monitoring**, and a **defense-in-depth** strategy that combines multiple security controls to protect data, systems, and users.
