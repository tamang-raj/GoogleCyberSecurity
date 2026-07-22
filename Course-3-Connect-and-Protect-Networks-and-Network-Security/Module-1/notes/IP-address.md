# IP Addresses and MAC Addresses

> **Google Cybersecurity Professional Certificate**
> **Course 2 – Module 6 Notes**

---

# 📖 Overview

This lesson explains how **IP addresses** and **MAC addresses** allow devices to communicate across a network. It also introduces the differences between **IPv4 and IPv6**, as well as **public and private IP addresses**.

---

# 🎯 Learning Objectives

- Understand what an IP address is
- Learn the differences between IPv4 and IPv6
- Distinguish between public and private IP addresses
- Understand what a MAC address is
- Learn how switches use MAC addresses to deliver data

---

# 🌐 What is an IP Address?

An **Internet Protocol (IP) address** is a **unique string of characters** that identifies a device's location on a network or the internet.

Think of an IP address like a **mailing address** for a house—it tells data where it should be delivered.

Every device connected to a network needs an IP address to communicate.

---

# 🌍 Types of IP Addresses

There are two main versions of IP addresses.

## IPv4

**IPv4 (Internet Protocol Version 4)** is the most commonly used IP addressing system.

### Characteristics

- Four groups of numbers
- Each group contains **1 to 3 digits**
- Groups are separated by periods (.)

### Example

```text
192.168.1.10
```

IPv4 provides a limited number of unique addresses.

---

## IPv6

**IPv6 (Internet Protocol Version 6)** was developed because the world is running out of available IPv4 addresses.

### Characteristics

- Uses **32 hexadecimal characters**
- Provides significantly more unique addresses
- Supports the growing number of internet-connected devices

### Example

```text
2001:0db8:85a3:0000:0000:8a2e:0370:7334
```

IPv6 ensures enough addresses are available for future devices and networks.

---

# 🌎 Public vs. Private IP Addresses

## Public IP Address

A **public IP address** is assigned by an **Internet Service Provider (ISP)**.

### Characteristics

- Used for communication outside the local network
- Shared by devices when accessing the internet
- Visible on the public internet

---

## Private IP Address

A **private IP address** is used within a **local network (LAN)**.

### Characteristics

- Enables communication between devices on the same network
- Not visible on the public internet
- Assigned within homes, schools, and organizations

Examples include communication between:

- Computers
- Printers
- Smartphones
- Servers

---

# 🖥️ What is a MAC Address?

A **Media Access Control (MAC) address** is a **unique alphanumeric identifier** assigned to a physical network device.

Unlike an IP address, a MAC address identifies the **hardware** itself.

Every network interface has its own MAC address.

---

# 🔀 How Switches Use MAC Addresses

Network **switches** use MAC addresses to ensure data reaches the correct device.

To do this, switches maintain a:

## MAC Address Table

A **MAC address table** acts like an address book.

It stores:

- Device MAC addresses
- The switch port where each device is connected

When data arrives, the switch checks the MAC address table and forwards the packet only to the intended device.

This improves:

- Network performance
- Security
- Communication efficiency

---

# 🔐 Why IP and MAC Addresses Matter

Security professionals use IP and MAC addresses to:

- Identify devices on a network
- Monitor network activity
- Investigate suspicious traffic
- Troubleshoot connectivity issues
- Track communication between systems

Understanding both addressing methods is essential for network security and incident response.

---

# 📚 Key Terms

| Term | Definition |
|------|------------|
| **IP Address** | A unique string of characters that identifies a device's location on a network or the internet |
| **IPv4** | Internet Protocol Version 4, consisting of four sets of numbers separated by periods |
| **IPv6** | Internet Protocol Version 6, using 32 hexadecimal characters to provide more addresses |
| **Public IP Address** | An IP address assigned by an ISP for communication over the internet |
| **Private IP Address** | An IP address used for communication within a local network |
| **MAC Address** | A unique alphanumeric identifier assigned to a physical network device |
| **MAC Address Table** | A table maintained by a switch that maps MAC addresses to connected devices |

---

# 📝 Key Takeaways

- An **IP address** identifies a device's location on a network.
- **IPv4** uses four groups of numbers separated by periods.
- **IPv6** uses 32 hexadecimal characters and supports many more devices.
- **Public IP addresses** are used for internet communication.
- **Private IP addresses** are used within local networks.
- A **MAC address** uniquely identifies a physical network device.
- **Switches** use **MAC address tables** to forward data to the correct device efficiently.

---

## ✅ Lesson Complete

✔ Learned the purpose of IP addresses

✔ Explored IPv4 and IPv6

✔ Distinguished between public and private IP addresses

✔ Understood MAC addresses

✔ Learned how switches use MAC address tables to direct network traffic