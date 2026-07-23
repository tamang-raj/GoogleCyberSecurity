# Subnetting Notes

> **Google Cybersecurity Professional Certificate**  
> **Course 2 – Module 6**

---

# 📖 Overview

This lesson introduces **subnetting**, a networking technique used to divide a large network into smaller, logical subnetworks (subnets). Subnetting improves **network performance, efficiency, and security** by organizing devices into smaller groups and reducing unnecessary network traffic.

---

# 🎯 Learning Objectives

- Understand what subnetting is
- Learn why subnetting is used
- Understand Classless Inter-Domain Routing (CIDR)
- Learn how subnetting improves security
- Understand the relationship between subnetting and security zones

---

# 🌐 What is Subnetting?

**Subnetting** is the process of dividing a large network into **smaller logical networks**, called **subnets**.

Think of subnetting as creating **"networks within a network."**

Instead of having one large network where every device communicates together, subnetting groups devices into smaller sections.

---

# Why Use Subnetting?

Organizations use subnetting to:

- Improve network performance
- Reduce unnecessary network traffic
- Increase efficiency
- Improve security
- Organize devices into logical groups
- Create isolated network segments

---

# Example

Without subnetting:

```text
One Large Network

PC1
PC2
PC3
Printer
Server
Finance
HR
Marketing
Guest Wi-Fi

(All devices share the same network)
```

With subnetting:

```text
Main Network

├── Finance Subnet
├── HR Subnet
├── Marketing Subnet
├── Server Subnet
└── Guest Wi-Fi Subnet
```

Each subnet operates independently while remaining part of the larger network.

---

# Benefits of Subnetting

## 1. Improved Network Efficiency

Devices on the **same subnet** can communicate directly without unnecessary traffic across the entire network.

Benefits include:

- Faster communication
- Reduced congestion
- Better bandwidth utilization

---

## 2. Better Network Performance

Smaller subnetworks reduce the amount of broadcast traffic.

This results in:

- Faster data transmission
- Less network congestion
- Improved overall performance

---

## 3. Improved Security

Subnetting separates groups of devices into isolated networks.

Examples:

- Finance department
- Human Resources
- Engineering
- Guest Wi-Fi

This isolation limits unauthorized access and reduces the spread of security incidents.

---

## 4. Supports Security Zones

Subnetting can be used to create **security zones** within an organization.

For example:

```text
Organization Network

├── Public Subnet
├── DMZ
├── Employee Network
├── Finance Network
└── Restricted Network
```

Each subnet can have different security rules and access permissions.

---

# Classless Inter-Domain Routing (CIDR)

**CIDR (Classless Inter-Domain Routing)** is the modern method used to assign subnet masks to IP addresses.

It replaced the older **classful addressing system**.

CIDR makes IP address allocation more flexible and efficient.

---

# CIDR Notation

CIDR uses an **IP network prefix** written after the IP address.

Example:

```text
192.168.1.0/24
```

The **"/24"** identifies the subnet.

Another example:

```text
10.0.0.0/16
```

The number after the slash (**/**) indicates the network prefix length.

---

# Benefits of CIDR

According to the lesson, CIDR:

- Replaced classful addressing
- Expands the number of available IPv4 addresses
- Simplifies routing
- Provides flexible subnet creation

---

# Security Benefits of Subnetting

Subnetting improves security by:

- Creating isolated subnetworks
- Supporting security zones
- Reducing unnecessary communication
- Improving routing efficiency
- Working together with firewalls

Organizations can isolate sensitive systems without requesting additional IP addresses from their Internet Service Provider (ISP).

---

# Subnetting and Firewalls

Firewalls can be configured to control communication between subnets.

Example:

```text
Finance Subnet
        │
     Firewall
        │
HR Subnet
```

Only authorized traffic is allowed between subnetworks.

---

# Subnetting Summary

| Feature | Benefit |
|---------|----------|
| Smaller subnetworks | Better organization |
| Direct communication | Improved efficiency |
| Reduced traffic | Better performance |
| Isolated networks | Improved security |
| CIDR | Flexible IP addressing |
| Security zones | Stronger access control |

---

# Key Terms

| Term | Definition |
|------|------------|
| **Subnetting** | Dividing a network into smaller logical subnetworks (subnets) |
| **Subnet** | A smaller network created from a larger network |
| **CIDR (Classless Inter-Domain Routing)** | A modern method for assigning subnet masks using IP prefixes |
| **IP Network Prefix** | The number after the slash (/) in CIDR notation that identifies the subnet |
| **Security Zone** | A protected segment of a network with specific access rules |
| **Firewall** | A security control that filters traffic between networks or subnets |

---

# Key Takeaways

- **Subnetting** creates smaller, logical subnetworks within a larger network.
- Devices on the **same subnet** communicate more efficiently.
- Subnetting improves **network performance** by reducing unnecessary traffic.
- It also improves **security** by isolating groups of devices and supporting **security zones**.
- **CIDR (Classless Inter-Domain Routing)** is the modern method for assigning subnet masks and uses an IP network prefix (such as **/24**) to identify subnets.
- Firewalls and routing rules can be used with subnetting to control communication between subnetworks.

---

## ✅ Lesson Complete

✔ Learned what subnetting is

✔ Understood the benefits of subnetting

✔ Learned about CIDR notation

✔ Explored how subnetting improves network security

✔ Understood the relationship between subnetting, security zones, and firewalls