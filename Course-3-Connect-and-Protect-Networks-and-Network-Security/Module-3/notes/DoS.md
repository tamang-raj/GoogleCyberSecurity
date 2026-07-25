# Denial of Service (DoS) Attacks

> **Google Cybersecurity Professional Certificate**  
> **Course 3 – Module 3**

![Course](https://img.shields.io/badge/Course-Google%20Cybersecurity-blue)
![Module](https://img.shields.io/badge/Module-3-success)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)
![Notes](https://img.shields.io/badge/Type-Study%20Notes-orange)

---

# 📖 Overview

This lesson introduces **Denial of Service (DoS) attacks**, one of the most common network attacks used to disrupt business operations. It explains how attackers overload systems with malicious traffic, the difference between DoS and Distributed Denial of Service (DDoS) attacks, and common network-level DoS attack techniques.

---

# 🎯 Learning Objectives

After completing this lesson, you should be able to:

- Define a Denial of Service (DoS) attack.
- Explain the purpose of a DoS attack.
- Distinguish between DoS and DDoS attacks.
- Identify common network-level DoS attacks.
- Understand the impact of DoS attacks on organizations.

---

# 🚨 What is a Denial of Service (DoS) Attack?

A **Denial of Service (DoS) attack** is a cyberattack that attempts to make a network, server, or online service unavailable by overwhelming it with excessive traffic.

The goal is to prevent legitimate users from accessing the targeted system.

---

# 🎯 Objective of a DoS Attack

Attackers launch DoS attacks to:

- Overload servers
- Exhaust network resources
- Disrupt normal business operations
- Prevent legitimate users from accessing services

---

# 💥 Impact of DoS Attacks

A successful DoS attack can cause:

- 💰 Financial losses
- ⏳ Wasted time and productivity
- 🌐 Service outages
- ⚠️ Increased exposure to additional security threats
- 📉 Disruption of normal business operations

---

# 🌍 Distributed Denial of Service (DDoS)

A **Distributed Denial of Service (DDoS)** attack is a more powerful version of a DoS attack.

Instead of using a single device, attackers use **multiple devices or servers from different locations** to flood a target with unwanted traffic.

Because traffic originates from many different systems, DDoS attacks are more difficult to stop and are more likely to overwhelm the target.

### Characteristics

- Uses multiple attacking devices
- Traffic originates from different locations
- Generates significantly more malicious traffic
- Higher chance of disrupting services

---

# ⚔️ Common Network-Level DoS Attacks

## 1. SYN Flood Attack

A **SYN Flood** attack exploits the **TCP three-way handshake** used to establish network connections.

### How it Works

- The attacker sends a large number of SYN packets.
- The server attempts to respond to each request.
- Available connection ports become exhausted.
- The server becomes overwhelmed and eventually crashes.

### Result

- Legitimate users cannot establish new connections.
- Network services become unavailable.

---

## 2. ICMP Flood Attack

An **ICMP Flood** attack repeatedly sends Internet Control Message Protocol (ICMP) packets to a target server.

### How it Works

- Large numbers of ICMP packets are sent.
- The server responds to each request.
- Incoming and outgoing bandwidth becomes saturated.
- Network resources are exhausted.

### Result

- Available bandwidth is consumed.
- The server becomes unresponsive or crashes.

---

## 3. Ping of Death Attack

A **Ping of Death** attack targets vulnerable systems by sending an oversized ICMP packet.

### How it Works

- The attacker sends an ICMP packet larger than **64 kilobytes**.
- The oversized packet exceeds what the system can properly process.
- The vulnerable system becomes overloaded.

### Result

- System crash
- Service interruption
- Denial of service

---

# 📊 DoS vs. DDoS

| Feature | DoS | DDoS |
|---------|-----|-------|
| Number of attacking devices | One | Multiple |
| Traffic source | Single location | Multiple locations |
| Attack strength | Lower | Higher |
| Difficulty to stop | Easier | More difficult |

---

# 🔑 Key Concepts

| Concept | Description |
|---------|-------------|
| DoS Attack | Floods a server or network with traffic to make it unavailable |
| DDoS Attack | Uses multiple devices to overwhelm a target |
| SYN Flood | Exploits the TCP connection handshake |
| ICMP Flood | Sends excessive ICMP packets to consume bandwidth |
| Ping of Death | Sends oversized ICMP packets to crash vulnerable systems |

---

# 📝 Summary

Denial of Service (DoS) attacks attempt to make systems unavailable by flooding them with excessive traffic. A more advanced form, the Distributed Denial of Service (DDoS) attack, uses multiple devices from different locations to increase the effectiveness of the attack.

Common network-level DoS attacks include **SYN Flood attacks**, which exploit the TCP handshake process; **ICMP Flood attacks**, which consume network bandwidth by generating excessive ICMP traffic; and **Ping of Death attacks**, which send oversized ICMP packets to overwhelm vulnerable systems.

Understanding these attacks helps cybersecurity professionals detect unusual network activity and implement appropriate defensive measures.

---

# 📌 Key Takeaways

- DoS attacks overwhelm networks or servers with excessive traffic.
- The goal is to prevent legitimate users from accessing services.
- DDoS attacks use multiple devices, making them more powerful than DoS attacks.
- SYN Flood attacks exploit the TCP connection handshake.
- ICMP Flood attacks consume network bandwidth with repeated ICMP packets.
- Ping of Death attacks send oversized ICMP packets to crash vulnerable systems.
- DoS attacks can cause financial losses, downtime, and operational disruption.

---

## 📖 Module Information

- **Course:** Google Cybersecurity Professional Certificate
- **Course Number:** Course 3
- **Module:** Module 3
- **Topic:** Denial of Service (DoS) Attacks
- **Status:** ✅ Completed