# Wireless Security Protocols Notes

> **Google Cybersecurity Professional Certificate**  
> **Course 2 – Module 6**

---

# 📖 Overview

This lesson introduces the **IEEE 802.11 wireless networking standards (Wi-Fi)** and explains the evolution of wireless security protocols from **WEP** to **WPA**, **WPA2**, and **WPA3**.

The goal of these protocols is to protect wireless networks by providing authentication, encryption, and secure communication.

---

# 🎯 Learning Objectives

- Understand IEEE 802.11 (Wi-Fi)
- Learn the evolution of wireless security protocols
- Compare WEP, WPA, WPA2, and WPA3
- Understand the encryption methods used by each protocol
- Identify the most secure Wi-Fi protocol

---

# 🌐 IEEE 802.11 (Wi-Fi)

**IEEE 802.11** is a family of standards that defines communication for **Wireless Local Area Networks (WLANs)**.

It is commonly known as **Wi-Fi**.

The standards are maintained by the:

> **Institute of Electrical and Electronics Engineers (IEEE)**

---

## Purpose of IEEE 802.11

- Enables wireless communication
- Connects devices without physical cables
- Defines how wireless devices communicate
- Supports wireless Local Area Networks (LANs)

Examples include:

- Home Wi-Fi
- School networks
- Office wireless networks
- Public Wi-Fi hotspots

---

# 🔒 Evolution of Wireless Security

Wireless security has evolved to address vulnerabilities and improve encryption.

The major wireless security protocols are:

1. WEP
2. WPA
3. WPA2
4. WPA3

Each version improves security over its predecessor.

---

# 1. WEP (Wired Equivalent Privacy)

### Released

**1999**

### Purpose

Designed to provide wireless privacy comparable to wired networks.

### Characteristics

- First wireless security protocol
- Used encryption to protect wireless traffic

### Weaknesses

- Vulnerable to attacks
- Encryption can be broken by attackers
- Considered a **high-risk protocol**
- No longer recommended

---

# 2. WPA (Wi-Fi Protected Access)

### Released

**2003**

### Purpose

Developed to fix the security weaknesses found in WEP.

### Improvements

- Larger encryption keys
- Better authentication
- Stronger encryption

### Encryption Method

**TKIP**

(Temporal Key Integrity Protocol)

TKIP dynamically changes encryption keys to improve security over WEP.

---

# 3. WPA2

### Released

**2004**

### Purpose

Further strengthened wireless security by replacing WPA's encryption method.

### Improvements

- Stronger encryption
- Better authentication
- Improved overall security

### Encryption Standard

**AES**

(Advanced Encryption Standard)

### Authentication Protocol

**CCMP**

(Counter Mode Cipher Block Chaining Message Authentication Code Protocol)

### Benefits

- More secure than WPA
- Long-time industry standard
- Protects against many wireless attacks

---

# 4. WPA3

### Released

**2018**

### Purpose

Designed to address vulnerabilities that affected WPA2, including **KRACK attacks**.

### Authentication Method

**SAE**

(Simultaneous Authentication of Equals)

### Encryption

- **128-bit encryption** (Personal mode)
- **Optional 192-bit encryption** (Enterprise mode)

### Benefits

- Stronger authentication
- Better encryption
- Improved protection against password attacks
- More secure than WPA2

---

# 📊 Wireless Security Protocol Comparison

| Protocol | Release Year | Encryption / Authentication | Security Level |
|----------|--------------|-----------------------------|----------------|
| **WEP** | 1999 | Basic encryption | ❌ High Risk (Outdated) |
| **WPA** | 2003 | TKIP | ⚠ Better than WEP |
| **WPA2** | 2004 | AES + CCMP | ✅ Strong Security |
| **WPA3** | 2018 | SAE + 128/192-bit Encryption | ⭐ Most Secure |

---

# 🔑 Encryption Technologies

## TKIP

**Temporal Key Integrity Protocol**

Used by:

- WPA

Purpose:

- Dynamically changes encryption keys
- Improved WEP security

---

## AES

**Advanced Encryption Standard**

Used by:

- WPA2

Benefits:

- Strong encryption
- Fast
- Widely adopted
- Industry standard

---

## CCMP

**Counter Mode Cipher Block Chaining Message Authentication Code Protocol**

Used with:

- WPA2

Purpose:

- Authentication
- Data integrity
- Encryption

---

## SAE

**Simultaneous Authentication of Equals**

Used by:

- WPA3

Benefits:

- Strong authentication
- Better password protection
- Prevents many password guessing attacks

---

# 📈 Evolution Timeline

```text
1999
│
├── WEP
│     ↓ Vulnerable
│
2003
│
├── WPA
│     ↓ Uses TKIP
│
2004
│
├── WPA2
│     ↓ Uses AES + CCMP
│
2018
│
└── WPA3
      ↓ Uses SAE
      ↓ Strongest encryption
```

---

# 📚 Key Terms

| Term | Definition |
|------|------------|
| **IEEE 802.11** | Standards for wireless Local Area Networks (Wi-Fi) |
| **Wi-Fi** | Wireless networking technology based on IEEE 802.11 standards |
| **WEP** | First wireless security protocol; now considered insecure |
| **WPA** | Improved wireless security protocol using TKIP |
| **WPA2** | Wireless security protocol using AES and CCMP |
| **WPA3** | Latest wireless security protocol using SAE and stronger encryption |
| **TKIP** | Temporal Key Integrity Protocol used by WPA |
| **AES** | Advanced Encryption Standard used by WPA2 |
| **CCMP** | Authentication and encryption protocol used with WPA2 |
| **SAE** | Simultaneous Authentication of Equals used by WPA3 |

---

# 📝 Key Takeaways

- **IEEE 802.11** defines Wi-Fi communication standards.
- **WEP** was the first wireless security protocol but is now insecure.
- **WPA** improved security by introducing **TKIP**.
- **WPA2** strengthened Wi-Fi security with **AES** and **CCMP**.
- **WPA3** is the latest standard, using **SAE** and stronger encryption to provide the highest level of wireless security.

---

## ✅ Lesson Complete

✔ Learned about IEEE 802.11 (Wi-Fi)

✔ Compared WEP, WPA, WPA2, and WPA3

✔ Understood TKIP, AES, CCMP, and SAE

✔ Learned why WPA3 is the most secure wireless protocol