# Network Attacks: Packet Sniffing, IP Spoofing & Denial of Service (DoS)


# 🌐 Why Network Security Matters

Every device connected to a network communicates by exchanging data packets.

If attackers can intercept or manipulate these packets, they may be able to:

- Steal usernames and passwords
- Access confidential information
- Impersonate trusted systems
- Interrupt business operations
- Damage an organization's reputation
- Cause financial losses

---

# 📦 Packet Sniffing

## What is Packet Sniffing?

**Packet sniffing** is the process of capturing and inspecting data packets traveling across a network.

Although network administrators use packet sniffing for troubleshooting, attackers use it to steal confidential information.

### Information attackers may capture

- Usernames
- Passwords
- Email messages
- Banking information
- IP addresses
- MAC addresses
- Authentication tokens

---

## Types of Packet Sniffing

### Passive Packet Sniffing

Passive packet sniffing involves monitoring network traffic without modifying it.

**Characteristics**

- Reads network traffic
- Does not alter packets
- Common on hub-based networks

---

### Active Packet Sniffing

Active packet sniffing captures and manipulates packets while they are in transit.

**Characteristics**

- Reads traffic
- Alters packets
- Redirects communications
- Often used in Man-in-the-Middle attacks

---

# 🌐 Network Interface Card (NIC)

A **Network Interface Card (NIC)** allows a computer to communicate over a network.

Normally, a NIC only accepts packets addressed to its own MAC address.

## Promiscuous Mode

When configured in **promiscuous mode**, the NIC accepts every packet on the network.

This enables attackers to capture all available network traffic.

---

# 🛠️ Packet Analysis Tool

A commonly used packet analyzer is:

- **Wireshark**

Uses include:

- Monitoring network traffic
- Troubleshooting connectivity issues
- Detecting suspicious activity
- Investigating security incidents

---

# 🎭 IP Spoofing

## What is IP Spoofing?

**IP spoofing** is a network attack where the attacker changes the source IP address of a packet to impersonate a trusted system.

Instead of revealing their real identity, attackers send packets using forged IP addresses.

### Objectives

- Bypass firewalls
- Gain unauthorized access
- Hide attacker identity
- Launch additional attacks

---

# 🔁 Replay Attack

A **Replay Attack** occurs when an attacker captures a legitimate packet and sends it again later.

### Objectives

- Impersonate authorized users
- Cause communication problems
- Bypass authentication mechanisms

---

# 🔄 On-Path Attack (Man-in-the-Middle)

An **On-path attack** occurs when an attacker secretly positions themselves between two communicating devices.

The attacker can:

- Read confidential information
- Modify messages
- Redirect traffic
- Capture credentials
- Hijack sessions

---

# 💥 Smurf Attack

A **Smurf Attack** combines **IP spoofing** with a **Denial of Service attack**.

### How it works

1. The attacker spoofs the victim's IP address.
2. Broadcast ICMP requests are sent across the network.
3. Multiple devices reply to the victim.
4. The victim becomes overwhelmed with network traffic.

---

# 🚫 Denial of Service (DoS)

## What is a DoS Attack?

A **Denial of Service (DoS)** attack floods a server or network with excessive traffic until legitimate users can no longer access it.

### Characteristics

- Single attacking device
- Overloads server resources
- Disrupts business operations

---

# 🌍 Distributed Denial of Service (DDoS)

A **Distributed Denial of Service (DDoS)** attack uses multiple compromised devices to flood a target.

Instead of one attacker,

Thousands of infected computers attack simultaneously.

### Advantages for attackers

- More difficult to block
- Greater attack volume
- Higher success rate

---

# 🤖 Botnet

A **Botnet** is a collection of malware-infected computers controlled by a single attacker.

The attacker controlling the botnet is called the **Bot-Herder**.

Victims are often unaware their computers are participating in attacks.

---

# 🌐 Internet Control Message Protocol (ICMP)

ICMP is a network protocol used to report network communication errors.

It is also used by the **ping** command to test connectivity between devices.

---

# 🌊 ICMP Flood Attack

An **ICMP Flood** attack repeatedly sends ICMP request packets to a server.

The server continuously responds until its resources become exhausted.

---

# 🤝 SYN Flood Attack

A **SYN Flood** exploits the TCP three-way handshake.

### Normal TCP Handshake

1. SYN
2. SYN-ACK
3. ACK

Connection established.

### During an Attack

The attacker repeatedly sends SYN packets but never completes the connection.

The server waits for responses until all available connections are consumed.

---

# 💀 Ping of Death

A **Ping of Death** attack sends an oversized ICMP packet larger than **64 KB**.

Older or vulnerable systems may become unstable or crash after receiving these malformed packets.

---

# 🛡️ Defending Against Network Attacks

Security professionals use multiple layers of protection.

## Encryption

Encryption protects data while it travels across networks.

Examples include:

- HTTPS
- SSL/TLS
- VPNs

---

## Firewalls

Firewalls help prevent attacks by:

- Filtering suspicious traffic
- Blocking spoofed IP addresses
- Rejecting unauthorized packets
- Monitoring unusual activity

---

## Defense-in-Depth

Defense-in-depth combines multiple security controls.

Examples include:

- Firewalls
- VPNs
- Encryption
- Intrusion Detection Systems (IDS)
- Intrusion Prevention Systems (IPS)
- Network monitoring
- Security Information and Event Management (SIEM)

---

# 📊 Attack Comparison

| Attack | Purpose | Characteristics |
|---------|---------|----------------|
| Passive Packet Sniffing | Capture traffic | Reads packets only |
| Active Packet Sniffing | Capture & modify traffic | Manipulates packets |
| IP Spoofing | Impersonation | Uses fake IP address |
| Replay Attack | Reuse captured packets | Sends intercepted packets later |
| On-Path Attack | Intercept communication | Reads or modifies data |
| DoS | Overload server | Single attacker |
| DDoS | Overload server | Multiple attackers (Botnet) |
| ICMP Flood | Exhaust bandwidth | Continuous ICMP requests |
| SYN Flood | Exploit TCP handshake | Incomplete TCP connections |
| Ping of Death | Crash vulnerable systems | Oversized ICMP packet |
| Smurf Attack | Flood victim | IP spoofing + ICMP |

---

# 📚 Key Terms

| Term | Definition |
|------|------------|
| **Packet Sniffing** | Capturing and inspecting network packets. |
| **Passive Packet Sniffing** | Monitoring traffic without modifying packets. |
| **Active Packet Sniffing** | Capturing and manipulating packets during transmission. |
| **IP Spoofing** | Forging the source IP address to impersonate another device. |
| **Replay Attack** | Resending intercepted packets at a later time. |
| **On-Path Attack** | Intercepting communication between trusted devices. |
| **DoS Attack** | Flooding a server using one attacking device. |
| **DDoS Attack** | Flooding a server using many compromised devices. |
| **Botnet** | A group of infected computers controlled by one attacker. |
| **ICMP Flood** | Repeated ICMP requests that overwhelm a server. |
| **SYN Flood** | Abuse of the TCP handshake to exhaust server resources. |
| **Ping of Death** | Oversized ICMP packet that crashes vulnerable systems. |
| **Smurf Attack** | A DoS attack using IP spoofing and ICMP broadcasts. |

---

# 🎯 Key Takeaways

- Packet sniffing captures network traffic and may expose sensitive information.
- Passive sniffing only observes traffic, while active sniffing also modifies it.
- IP spoofing disguises an attacker's identity by forging IP addresses.
- Replay attacks reuse captured packets to impersonate legitimate users.
- On-path attacks intercept communications between trusted systems.
- DoS attacks use one attacker, while DDoS attacks use many compromised devices (botnets).
- Common DoS attacks include SYN Flood, ICMP Flood, Ping of Death, and Smurf attacks.
- Encryption, firewalls, VPNs, SIEM solutions, and defense-in-depth significantly reduce the risk of network attacks.

---

# 📝 Summary

Understanding common network attacks is essential for every cybersecurity professional. Techniques such as **packet sniffing**, **IP spoofing**, **replay attacks**, and **on-path attacks** are often used to steal information or impersonate trusted systems. Attackers may also launch **Denial of Service (DoS)** and **Distributed Denial of Service (DDoS)** attacks to disrupt network availability using methods like **SYN Floods**, **ICMP Floods**, **Ping of Death**, and **Smurf attacks**. Organizations defend against these threats through **encryption**, **firewalls**, **VPNs**, **continuous monitoring**, and a **defense-in-depth** security strategy.
