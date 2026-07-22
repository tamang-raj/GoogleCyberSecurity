# OSI Network Layer (Layer 3) and IP Packet Structure

> **Google Cybersecurity Professional Certificate**
> **Course 2 – Module 6 Notes**

---

# 📖 Overview

This lesson focuses on the **Network Layer (Layer 3)** of the **OSI model**, which is responsible for **addressing**, **routing**, and **delivering data packets** across networks. It also introduces the structure of **IPv4 packets**, compares **IPv4 and IPv6**, and explains how routers use IP addresses to forward data.

---

# 🎯 Learning Objectives

- Understand the purpose of the OSI Network Layer
- Learn how routers forward data packets
- Explore the structure of an IPv4 packet
- Understand important IPv4 header fields
- Compare IPv4 and IPv6 packet formats

---

# 🌐 OSI Network Layer (Layer 3)

The **Network Layer** is **Layer 3** of the **OSI model**.

Its primary responsibility is to **organize the addressing and delivery of data packets** from the source device to the destination device.

The Network Layer ensures that data reaches the correct destination, even if it must travel across multiple networks.

---

# 🚀 Responsibilities of the Network Layer

The Network Layer is responsible for:

- Addressing data packets
- Routing packets between networks
- Delivering packets to the correct destination
- Working with routers to determine the best path

Each packet contains a **destination IP address**, allowing routers to determine where the packet should be sent.

---

# 🔀 Role of Routers

Routers operate at the **Network Layer (Layer 3)**.

Their job is to examine the **destination IP address** inside each packet's header and determine the best route to forward the packet toward its destination.

---

# 📦 IPv4 Packet Structure

An **IPv4 packet** consists of two main parts:

## 1. Header

The **header** contains routing and control information needed to deliver the packet.

Header size:

- **20 to 60 bytes**

Information stored in the header includes:

- Source IP address
- Destination IP address
- Protocol information
- Packet size
- Other routing and control fields

---

## 2. Data Section (Payload)

The **data section** contains the actual information being transmitted between devices.

Examples include:

- Files
- Emails
- Web pages
- Messages

---

# 🏷️ Important IPv4 Header Fields

## Source IP Address

Identifies the device that sent the packet.

---

## Destination IP Address

Identifies the device that should receive the packet.

Routers use this address to determine where the packet should be forwarded.

---

## Protocol

Specifies which communication protocol should process the packet.

---

## Time To Live (TTL)

**Time To Live (TTL)** prevents packets from being forwarded indefinitely.

Each router decreases the TTL value.

When the TTL reaches zero, the packet is discarded.

---

## Identification

Used to identify fragmented packets so they can be correctly reassembled at the destination.

---

## Flags

Provide information about packet fragmentation.

They indicate whether fragmentation is allowed and whether additional fragments follow.

---

## Header Checksum

Used to detect errors in the packet header during transmission.

If the checksum is invalid, the packet may be discarded.

---

# 🌍 IPv4 vs IPv6

IPv6 was created because the available IPv4 address space became exhausted.

---

## IPv4

Characteristics:

- Uses **4-byte addresses**
- Written in **decimal notation**
- Limited number of available addresses
- More complex packet header

Example:

```text
192.168.1.100
```

---

## IPv6

Characteristics:

- Uses **16-byte addresses**
- Written in **hexadecimal notation**
- Provides a vastly larger address space
- Uses a simpler packet header

Example:

```text
2001:0db8:85a3:0000:0000:8a2e:0370:7334
```

---

# 🔄 Differences Between IPv4 and IPv6 Headers

Compared to IPv4, IPv6:

- Uses a simpler header format
- Removes fields such as:
  - IHL
  - Identification
  - Flags
- Introduces a **Flow Label** field

---

## Flow Label

The **Flow Label** is an IPv6 header field used to identify packets that require special handling during transmission.

It helps improve the management of specific network traffic flows.

---

# 🔐 Why the Network Layer Matters

Understanding the Network Layer helps security professionals:

- Trace network communication
- Analyze packet routing
- Troubleshoot connectivity problems
- Investigate suspicious traffic
- Detect malicious network activity

Knowledge of packet headers is essential for packet analysis and incident investigations.

---

# 📚 Key Terms

| Term | Definition |
|------|------------|
| **Network Layer** | Layer 3 of the OSI model responsible for addressing and routing data packets |
| **Router** | A network device that forwards packets based on destination IP addresses |
| **IPv4 Packet** | A packet consisting of a header and a data (payload) section |
| **Header** | The part of a packet containing addressing and routing information |
| **Payload (Data Section)** | The actual information being transmitted |
| **TTL (Time To Live)** | A header field that prevents packets from circulating indefinitely |
| **Identification** | A field used to identify fragmented packets |
| **Flags** | Header fields used for packet fragmentation control |
| **Header Checksum** | A field used to detect errors in the IPv4 header |
| **Flow Label** | An IPv6 field used for special packet handling |

---

# 📝 Key Takeaways

- The **Network Layer (Layer 3)** handles **addressing**, **routing**, and **packet delivery**.
- Routers examine the **destination IP address** to determine where packets should be sent.
- An **IPv4 packet** consists of a **header** and a **data (payload)** section.
- Important IPv4 header fields include:
  - Source IP Address
  - Destination IP Address
  - Protocol
  - Time To Live (TTL)
  - Identification
  - Flags
  - Header Checksum
- **IPv6** provides a much larger address space and uses a simpler header than IPv4.
- IPv6 introduces the **Flow Label** field for special packet handling.

---

## ✅ Lesson Complete

✔ Learned the role of the OSI Network Layer (Layer 3)

✔ Understood how routers forward packets

✔ Explored the structure of IPv4 packets

✔ Learned key IPv4 header fields

✔ Compared IPv4 and IPv6 packet formats