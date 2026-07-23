# Virtual Private Networks (VPNs) Notes

> **Google Cybersecurity Professional Certificate**  
> **Course 2 – Module 6**

---

# 📖 Overview

This lesson explains how **Virtual Private Networks (VPNs)** protect users' privacy and secure data transmitted over the internet. It covers why VPNs are necessary, how they work, and the concepts of **encryption**, **encapsulation**, and **encrypted tunnels**.

---

# 🎯 Learning Objectives

- Understand what a VPN is
- Learn why VPNs are important
- Understand how VPNs protect online privacy
- Learn about encryption and encapsulation
- Understand encrypted tunnels

---

# 🌐 What is a VPN?

A **Virtual Private Network (VPN)** is a service that creates a **secure, encrypted connection** between your device and the internet.

Its primary purpose is to:

- Protect your privacy
- Encrypt internet traffic
- Hide your public IP address
- Secure data transmitted over public networks

---

# Why Do We Need a VPN?

Whenever you connect to the internet, your **Internet Service Provider (ISP)** can see information about your internet activity.

This includes:

- Public IP address
- Websites you visit
- Network requests
- Physical location
- Other internet traffic metadata

Without protection, sensitive information could potentially be intercepted while traveling across the internet.

Examples of sensitive information include:

- Banking information
- Credit card numbers
- Personal data
- Login credentials

---

# How a VPN Works

Instead of connecting directly to a website:

```text
Your Device
      │
      ▼
Internet
      │
      ▼
Website
```

A VPN routes your connection through a VPN server:

```text
Your Device
      │
      ▼
Encrypted Tunnel
      │
      ▼
VPN Server
      │
      ▼
Internet
      │
      ▼
Website
```

The VPN server forwards your requests while protecting your identity.

---

# VPN Functions

A VPN provides several important security functions.

## 1. Changes Your Public IP Address

A VPN replaces your real public IP address with the VPN server's IP address.

Benefits:

- Hides your identity
- Makes tracking more difficult
- Improves online privacy

---

## 2. Hides Your Virtual Location

Since websites see the VPN server's IP address instead of yours, your apparent location changes.

Benefits:

- Greater privacy
- Reduced location tracking

---

## 3. Encrypts Your Data

VPNs encrypt data before it leaves your device.

Benefits:

- Maintains confidentiality
- Prevents unauthorized users from reading data
- Protects sensitive information while in transit

---

# Encryption

Encryption converts readable information into an unreadable format.

```text
Plaintext
      │
Encryption
      ▼
Ciphertext
```

Only someone with the correct cryptographic key can decrypt and read the data.

---

# Encapsulation

**Encapsulation** is the process of wrapping encrypted data inside additional data packets.

This allows:

- Routers to forward the packets correctly
- Sensitive information to remain encrypted and protected

---

# Encrypted Tunnel

A VPN creates an **encrypted tunnel** between your device and the VPN server.

Characteristics:

- Protects all transmitted data
- Prevents unauthorized interception
- Requires a cryptographic key to decrypt the information

This secure tunnel helps keep data confidential while it travels across the internet.

---

# Benefits of VPNs

- Encrypts internet traffic
- Protects sensitive information
- Hides your public IP address
- Conceals your virtual location
- Secures communication on public networks
- Improves online privacy

---

# VPN Workflow

```text
User Device
      │
Encrypt Data
      ▼
Encrypted Tunnel
      ▼
VPN Server
      ▼
Internet
      ▼
Destination Website
```

---

# Key Terms

| Term | Definition |
|------|------------|
| **Virtual Private Network (VPN)** | A service that creates a secure, encrypted connection over the internet |
| **Internet Service Provider (ISP)** | A company that provides internet access |
| **Public IP Address** | The address visible on the internet that identifies a network |
| **Encryption** | The process of converting readable data into an unreadable format |
| **Ciphertext** | Encrypted data that cannot be read without a decryption key |
| **Encapsulation** | Wrapping encrypted data inside additional data packets for transmission |
| **Encrypted Tunnel** | A secure, encrypted connection between a device and a VPN server |
| **Cryptographic Key** | A key used to encrypt and decrypt data |

---

# Key Takeaways

- A **VPN** creates a secure, encrypted connection between your device and the internet.
- VPNs **hide your public IP address** and **virtual location** to improve privacy.
- VPNs **encrypt data**, making it unreadable to unauthorized parties during transmission.
- **Encapsulation** wraps encrypted data inside additional packets for routing.
- An **encrypted tunnel** securely carries data between your device and the VPN server.

---

## ✅ Lesson Complete

✔ Learned what a VPN is

✔ Understood why VPNs are important

✔ Explored encryption and encapsulation

✔ Learned how encrypted tunnels protect data in transit

✔ Understood how VPNs enhance privacy and network security