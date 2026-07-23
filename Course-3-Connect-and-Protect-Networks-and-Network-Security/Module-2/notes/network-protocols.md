# Network Protocols Notes

> **Google Cybersecurity Professional Certificate**  
> **Course 2 – Module 6**

---

# 📖 Overview

This lesson introduces **network protocols**, which are standardized rules that allow devices to communicate across networks. It covers the major communication, management, and security protocols used in networking, along with technologies such as **NAT**, **DHCP**, **ARP**, **SSH**, and email protocols.

---

# 🎯 Learning Objectives

- Understand what network protocols are
- Learn common communication protocols
- Explore management and security protocols
- Understand NAT, DHCP, and ARP
- Learn secure remote access protocols
- Understand common email protocols

---

# 🌐 What Are Network Protocols?

A **network protocol** is a set of rules that determines how devices communicate over a network.

Protocols define:

- How data is structured
- How data is transmitted
- The order in which data is delivered
- How devices identify one another

They act as a common language that allows different devices and operating systems to communicate.

---

# 📂 Categories of Network Protocols

Network protocols are grouped into three categories:

## 1. Communication Protocols

Used to transmit data between devices.

Examples:

- TCP
- UDP
- HTTP
- DNS

---

## 2. Management Protocols

Used to monitor, configure, and troubleshoot networks.

Examples:

- SNMP
- ICMP
- DHCP

---

## 3. Security Protocols

Used to protect data during transmission.

Examples:

- HTTPS
- SFTP
- SSH

---

# 📡 Communication Protocols

## TCP (Transmission Control Protocol)

TCP is a **connection-oriented communication protocol**.

### Features

- Establishes a connection before sending data
- Uses a handshake process
- Ensures reliable delivery
- Verifies that packets arrive correctly
- Retransmits lost packets

Common uses:

- Web browsing
- Email
- File transfers

---

## UDP (User Datagram Protocol)

UDP is a **connectionless communication protocol**.

### Features

- Faster than TCP
- Does not establish a connection
- Does not guarantee packet delivery
- Lower overhead

Often used for:

- Video streaming
- Voice calls
- Online gaming

---

## HTTP (Hypertext Transfer Protocol)

HTTP is used for communication between:

- Web browsers
- Web servers

HTTP sends data **without encryption**.

---

## HTTPS (Hypertext Transfer Protocol Secure)

HTTPS is the secure version of HTTP.

### Features

- Encrypts communication
- Uses SSL/TLS
- Protects sensitive information
- Prevents attackers from reading transmitted data

Used by:

- Banking websites
- Online shopping
- Login pages

---

## DNS (Domain Name System)

DNS translates:

```
www.example.com
```

into

```
192.168.1.1
```

Computers use IP addresses rather than domain names, making DNS the internet's "phonebook."

---

# 🔧 Management Protocols

## DHCP (Dynamic Host Configuration Protocol)

DHCP automatically assigns network settings to devices.

It provides:

- IP address
- Subnet mask
- Default gateway
- DNS server

Without DHCP, every device would need to be configured manually.

---

## SNMP (Simple Network Management Protocol)

SNMP is used to:

- Monitor network devices
- Manage routers
- Monitor switches
- Track printers and servers

It helps administrators monitor network performance.

---

## ICMP (Internet Control Message Protocol)

ICMP is used for:

- Error reporting
- Network diagnostics
- Connectivity testing

Example:

- **ping** command

---

# 🔐 Security Protocols

## HTTPS

Provides encrypted web communication using SSL/TLS.

---

## SFTP (Secure File Transfer Protocol)

Used to securely transfer files between computers.

Features:

- Encryption
- Authentication
- Secure file exchange

---

## SSH (Secure Shell)

SSH is a secure remote access protocol.

### Features

- Encrypted communication
- Remote administration
- Uses **TCP Port 22**

SSH replaces Telnet because it protects transmitted information.

---

## Telnet

Telnet is an older remote access protocol.

### Characteristics

- Sends information in plain text
- No encryption
- Insecure

Because of its security weaknesses, SSH is preferred.

---

# 🌍 Network Address Translation (NAT)

NAT allows multiple devices on a private network to share one public IP address.

### How NAT Works

Outgoing traffic:

- Private IP → Public IP

Incoming responses:

- Public IP → Private IP

Benefits:

- Conserves IPv4 addresses
- Hides internal network addresses

---

# 🖥️ Address Resolution Protocol (ARP)

ARP translates:

```
IP Address
        ↓
MAC Address
```

When a device knows another device's IP address but not its MAC address, ARP discovers the MAC address so communication can occur on the local network.

---

# 📧 Email Protocols

## POP (Post Office Protocol)

POP downloads emails from the server to the user's device.

Characteristics:

- Emails are typically stored locally
- Good for using one device

---

## IMAP (Internet Message Access Protocol)

IMAP keeps email on the server.

Benefits:

- Access emails from multiple devices
- Synchronizes messages
- Changes appear everywhere

---

## SMTP (Simple Mail Transfer Protocol)

SMTP is responsible for:

- Sending emails
- Routing outgoing mail
- Delivering messages to recipients

SMTP handles outgoing mail only.

---

# 🔄 Summary of Important Protocols

| Protocol | Purpose |
|----------|---------|
| TCP | Reliable communication |
| UDP | Fast communication without reliability checks |
| HTTP | Unencrypted web communication |
| HTTPS | Secure encrypted web communication |
| DNS | Converts domain names to IP addresses |
| DHCP | Automatically assigns IP addresses |
| ARP | Converts IP addresses to MAC addresses |
| SNMP | Monitors and manages network devices |
| ICMP | Reports network errors and tests connectivity |
| SSH | Secure remote access |
| Telnet | Insecure remote access |
| SFTP | Secure file transfer |
| POP | Downloads email to a local device |
| IMAP | Synchronizes email across devices |
| SMTP | Sends email |

---

# 📚 Key Terms

| Term | Definition |
|------|------------|
| **Network Protocol** | A set of rules governing communication between network devices |
| **TCP** | Reliable, connection-oriented communication protocol |
| **UDP** | Fast, connectionless communication protocol |
| **HTTPS** | Secure web communication using encryption |
| **DNS** | Converts domain names into IP addresses |
| **DHCP** | Automatically assigns IP addresses and network settings |
| **ARP** | Resolves IP addresses into MAC addresses |
| **NAT** | Allows multiple devices to share one public IP address |
| **SSH** | Secure remote login protocol |
| **Telnet** | Unencrypted remote login protocol |
| **POP** | Downloads emails from a server |
| **IMAP** | Synchronizes emails across devices |
| **SMTP** | Sends and routes outgoing emails |
| **SNMP** | Monitors and manages network devices |
| **ICMP** | Reports errors and tests network connectivity |

---

# 📝 Key Takeaways

- Network protocols define how devices communicate.
- Protocols are divided into **communication**, **management**, and **security** categories.
- **TCP** provides reliable communication, while **UDP** prioritizes speed.
- **HTTPS**, **SSH**, and **SFTP** secure data through encryption.
- **DNS** translates domain names into IP addresses.
- **DHCP** automatically assigns IP addresses and other network settings.
- **ARP** maps IP addresses to MAC addresses on local networks.
- **NAT** allows many private devices to share a single public IP address.
- **SMTP** sends emails, **POP** downloads emails, and **IMAP** synchronizes emails across multiple devices.

---

## ✅ Lesson Complete

✔ Learned what network protocols are

✔ Explored communication, management, and security protocols

✔ Understood NAT, DHCP, and ARP

✔ Learned secure remote access protocols

✔ Compared POP, IMAP, and SMTP email protocols