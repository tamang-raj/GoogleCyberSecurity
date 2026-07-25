# Packet Sniffing


# 📦 What is Packet Sniffing?

Packet sniffing is the process of capturing and inspecting data packets as they travel across a network.

Packet sniffers may be:

- Software applications
- Hardware devices

They monitor network communications by capturing packets moving between devices.

---

# ⚙️ How Packet Sniffing Works

Every communication across a network is broken into small units called **packets**.

A packet sniffer captures these packets and allows them to be analyzed.

Captured information may include:

- Source IP address
- Destination IP address
- Protocol
- Packet contents
- Login credentials (if unencrypted)
- Messages
- Personal information

---

# 🎭 Passive Packet Sniffing

Passive packet sniffing involves observing network traffic without modifying it.

### Characteristics

- Reads packets in transit
- Does not alter network traffic
- Difficult to detect
- Common on shared networks

### Example

Reading data traveling across an unsecured Wi-Fi network without changing any information.

---

# ⚠️ Active Packet Sniffing

Active packet sniffing involves intercepting and manipulating network traffic.

### Characteristics

- Captures packets
- Modifies data
- Redirects traffic
- More complex than passive sniffing

### Possible Actions

- Redirect network traffic
- Modify transmitted information
- Inject malicious packets
- Perform man-in-the-middle style attacks

---

# 🔓 Risks of Packet Sniffing

Attackers may capture:

- Usernames
- Passwords
- Credit card numbers
- Banking information
- Personal messages
- Emails
- Authentication tokens
- Sensitive business data

If transmitted without encryption, this information may be exposed.

---

# 🛡️ Preventing Packet Sniffing

## 1. Use a VPN

A **Virtual Private Network (VPN)** encrypts network traffic before it is transmitted.

### Benefits

- Encrypts data
- Protects privacy
- Hides sensitive information
- Prevents unauthorized interception

---

## 2. Use HTTPS

Always access websites that use:

**HTTPS**

HTTPS protects communications by using:

- SSL (Secure Sockets Layer)
- TLS (Transport Layer Security)

### Benefits

- Encrypts transmitted data
- Prevents eavesdropping
- Protects login credentials
- Secures online transactions

---

## 3. Avoid Public Wi-Fi

Unsecured public Wi-Fi networks often do not encrypt traffic.

Risks include:

- Packet sniffing
- Credential theft
- Session hijacking
- Data interception

If public Wi-Fi must be used:

- Connect through a VPN
- Avoid accessing sensitive accounts
- Verify HTTPS is enabled

---

# 🔐 Best Practices

- Use VPNs on public networks
- Visit HTTPS-enabled websites
- Avoid unsecured Wi-Fi networks
- Keep devices updated
- Use strong authentication
- Encrypt sensitive communications

---

# 📊 Passive vs Active Packet Sniffing

| Feature | Passive | Active |
|---------|----------|---------|
| Reads packets | ✅ | ✅ |
| Modifies traffic | ❌ | ✅ |
| Redirects traffic | ❌ | ✅ |
| Hard to detect | ✅ | ❌ |
| Common on shared networks | ✅ | Sometimes |

---

# 📚 Key Terms

| Term | Definition |
|------|------------|
| **Packet Sniffing** | Capturing and analyzing network packets. |
| **Passive Packet Sniffing** | Observing packets without modifying them. |
| **Active Packet Sniffing** | Capturing and manipulating network traffic. |
| **VPN** | Encrypts network traffic to protect data in transit. |
| **HTTPS** | Secure version of HTTP that encrypts communication using SSL/TLS. |
| **SSL/TLS** | Security protocols that provide encrypted network communication. |

---

# 🎯 Key Takeaways

- Packet sniffing captures data traveling across a network.
- Both security professionals and attackers use packet sniffers.
- Passive packet sniffing only observes network traffic.
- Active packet sniffing captures and manipulates packets.
- VPNs encrypt traffic, making intercepted data unreadable.
- HTTPS protects web traffic using SSL/TLS encryption.
- Avoid unsecured public Wi-Fi whenever possible.

---

# 📝 Summary

Packet sniffing is a powerful network analysis technique used for monitoring and troubleshooting networks. However, attackers can exploit packet sniffing to steal sensitive information from unencrypted communications. Organizations reduce this risk by using encryption technologies such as **VPNs** and **HTTPS**, along with secure network practices like avoiding unsecured public Wi-Fi and protecting sensitive data during transmission.
