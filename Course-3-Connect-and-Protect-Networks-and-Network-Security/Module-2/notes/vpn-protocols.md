# Virtual Private Networks (VPNs)

> **Google Cybersecurity Professional Certificate**  
> **Course 2 – Network Security**

---

# 📖 Overview

This lesson explains what a **Virtual Private Network (VPN)** is, how it works, the different types of VPNs, and the protocols used to create secure connections.

VPNs improve privacy and security by encrypting data and masking public IP addresses when communicating over public networks.

---

# 🎯 Learning Objectives

- Understand what a VPN is
- Learn how VPNs work
- Differentiate between Remote Access VPNs and Site-to-Site VPNs
- Understand VPN tunnels
- Compare WireGuard and IPSec VPN protocols

---

# 🌐 What is a VPN?

A **Virtual Private Network (VPN)** is a network security service that:

- Masks a user's public IP address
- Encrypts network traffic
- Protects data on public networks
- Creates a secure connection between devices and the internet

VPNs improve:

- Privacy
- Confidentiality
- Security

---

# How a VPN Works

Without a VPN:

```text
Device ───────────► Internet
(Public IP visible)
```

With a VPN:

```text
Device
    │
    ▼
Encrypted Tunnel
    │
    ▼
VPN Server
    │
    ▼
Internet
```

The VPN server acts as a gateway between the user's device and the internet.

---

# VPN Features

## 1. Encryption

VPNs encrypt data before transmission.

Benefits:

- Protects sensitive information
- Prevents unauthorized access
- Maintains confidentiality

---

## 2. IP Address Masking

VPNs hide the user's real public IP address.

Benefits:

- Improves privacy
- Conceals geographic location
- Reduces tracking

---

## 3. Secure Tunnel

VPNs create a secure virtual tunnel between devices and VPN servers.

Benefits:

- Protects data during transmission
- Secures communications over public networks

---

# Types of VPNs

---

## 1. Remote Access VPN

A **Remote Access VPN** connects an individual device to a VPN server.

```text
Laptop
   │
   ▼
VPN Server
   │
   ▼
Internet
```

### Common Uses

- Remote work
- Public Wi-Fi protection
- Secure internet browsing

### Features

- Encrypts data
- Hides IP addresses
- Protects individual users

---

## 2. Site-to-Site VPN

A **Site-to-Site VPN** securely connects multiple networks.

```text
Office A
     │
Encrypted Tunnel
     │
Office B
```

### Common Uses

- Connecting branch offices
- Extending organizational networks
- Secure communication between locations

### Features

- Connects entire networks
- Often uses IPSec
- Common in businesses

---

# VPN Protocols

VPN protocols define how VPN connections are established and secured.

---

## WireGuard

**WireGuard** is a modern VPN protocol.

### Characteristics

- Open-source
- High-speed
- Lightweight
- Uses advanced encryption
- Fewer lines of code

### Benefits

- Faster performance
- Simpler design
- Easier maintenance

---

## IPSec (Internet Protocol Security)

**IPSec** is a well-established VPN protocol.

### Characteristics

- Older protocol
- Widely supported
- Extensively tested
- More complex

### Common Uses

- Site-to-Site VPNs
- Enterprise networks

### Benefits

- Strong security
- Broad compatibility
- Proven reliability

---

# WireGuard vs IPSec

| Feature | WireGuard | IPSec |
|----------|------------|--------|
| Age | Newer | Older |
| Source Code | Open-source | Standardized protocol |
| Complexity | Simpler | More complex |
| Performance | Faster | Good performance |
| Code Size | Smaller | Larger |
| Compatibility | Growing support | Widely supported |
| Common Use | Remote access VPNs | Site-to-Site VPNs |

---

# VPN Summary

| Concept | Description |
|----------|-------------|
| VPN | Encrypts traffic and masks IP addresses |
| VPN Tunnel | Secure virtual connection |
| Remote Access VPN | Connects users to VPN servers |
| Site-to-Site VPN | Connects networks together |
| WireGuard | Modern, fast VPN protocol |
| IPSec | Established VPN security protocol |

---

# Key Terms

| Term | Definition |
|--------|------------|
| **Virtual Private Network (VPN)** | A service that encrypts data and masks public IP addresses |
| **Remote Access VPN** | A VPN connecting individual devices to a VPN server |
| **Site-to-Site VPN** | A VPN connecting multiple networks |
| **VPN Tunnel** | An encrypted communication path |
| **WireGuard** | A modern, open-source VPN protocol |
| **IPSec** | A protocol used to secure IP communications |

---

# Key Takeaways

- VPNs improve privacy by **encrypting traffic** and **hiding public IP addresses**.
- VPNs create **secure virtual tunnels** between devices and the internet.
- **Remote Access VPNs** protect individual users.
- **Site-to-Site VPNs** connect organizational networks.
- **WireGuard** is modern, lightweight, and fast.
- **IPSec** is widely supported and commonly used in enterprise environments.

---

## ✅ Lesson Complete

✔ Learned how VPNs work

✔ Understood VPN tunnels

✔ Compared Remote Access and Site-to-Site VPNs

✔ Compared WireGuard and IPSec