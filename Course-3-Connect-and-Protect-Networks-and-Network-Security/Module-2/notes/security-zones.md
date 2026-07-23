# Security Zones Notes

> **Google Cybersecurity Professional Certificate**  
> **Course 2 – Module 6**

---

# 📖 Overview

This lesson explains **security zones**, a network security strategy that divides a network into separate segments to protect sensitive systems and data. Security zones create multiple layers of defense by controlling how traffic flows between different parts of a network.

---

# 🎯 Learning Objectives

- Understand what security zones are
- Learn why network segmentation is important
- Identify different security zones
- Understand the purpose of a DMZ
- Learn how firewalls protect security zones
- Understand access control policies

---

# 🌐 What are Security Zones?

A **security zone** is a segment of a network that has its own security rules and access permissions.

Security zones separate different parts of a network to:

- Improve security
- Limit unauthorized access
- Prevent attacks from spreading
- Protect sensitive systems and data

Instead of treating the entire network as one large area, organizations divide it into smaller, controlled sections.

---

# Why Use Security Zones?

Security zones help organizations:

- Isolate sensitive systems
- Control user access
- Reduce attack surfaces
- Contain security incidents
- Protect confidential information

If one zone is compromised, the attacker cannot easily move into other protected zones.

---

# Example

### Hotel Network

A hotel typically separates:

- **Public Wi-Fi** → Guests
- **Private Network** → Hotel staff

Guests cannot access the hotel's internal systems because they are placed in different security zones.

---

### University Network

A university may have separate subnets for:

- Students
- Faculty
- Administration
- Research Labs

Each group has different access permissions.

---

# Types of Security Zones

There are two primary categories of security zones.

---

## 1. Uncontrolled Zone

The **uncontrolled zone** refers to any network outside an organization's control.

### Example

- Internet

Characteristics:

- Public
- Untrusted
- High security risk
- Anyone can attempt to connect

---

## 2. Controlled Zone

The **controlled zone** is the organization's protected network.

Characteristics:

- Managed by the organization
- Protected by firewalls
- Contains multiple security zones
- Only authorized access is allowed

The controlled zone contains:

- DMZ
- Internal Network
- Restricted Zone

---

# Demilitarized Zone (DMZ)

The **Demilitarized Zone (DMZ)** is the outer layer of the controlled network.

It contains systems that must communicate with the public internet while remaining isolated from the internal network.

### Common Services in a DMZ

- Web servers
- Proxy servers
- DNS servers
- Email servers
- File servers

---

## Purpose of the DMZ

The DMZ:

- Serves public users
- Protects the internal network
- Acts as a network perimeter
- Reduces the impact of attacks

If a public web server is compromised, attackers still face another layer of protection before reaching internal systems.

---

# Internal Network

The **internal network** contains an organization's private resources.

Examples:

- Internal applications
- Employee workstations
- Database servers
- Business systems

Characteristics:

- Not directly accessible from the internet
- Protected by firewalls
- Accessible only by authorized users

---

# Restricted Zone

The **restricted zone** is the most secure part of the network.

It contains highly confidential or sensitive information.

Examples:

- Financial records
- Customer information
- Healthcare records
- Payroll systems
- Executive information

Only privileged employees can access this zone.

---

# Security Zone Architecture

```text
                Internet
          (Uncontrolled Zone)
                    │
                    ▼
            Firewall #1
                    │
                    ▼
      Demilitarized Zone (DMZ)
     ┌─────────────────────────┐
     │ Web Server              │
     │ DNS Server              │
     │ Email Server            │
     │ Proxy Server            │
     └─────────────────────────┘
                    │
            Firewall #2
                    │
                    ▼
          Internal Network
                    │
                    ▼
          Restricted Zone
```

---

# Firewalls and Security Zones

Ideally, the DMZ is protected by **two firewalls**.

## Firewall #1

Located between:

```
Internet
      │
Firewall
      │
DMZ
```

Purpose:

- Filters internet traffic
- Blocks unauthorized access
- Allows only approved traffic into the DMZ

---

## Firewall #2

Located between:

```
DMZ
   │
Firewall
   │
Internal Network
```

Purpose:

- Protects the internal network
- Prevents attackers from moving deeper into the network
- Creates an additional security layer

---

# Defense in Depth

Using multiple firewalls creates **Defense in Depth**.

Benefits:

- Multiple security layers
- Reduced attack success
- Better protection of sensitive systems
- Improved incident containment

---

# Access Control Policies

Security analysts configure firewall rules known as **access control policies**.

These policies determine:

- Who can connect
- Which IP addresses are allowed
- Which ports are open
- Which services are accessible

Only authorized traffic is allowed into protected zones.

---

# Responsibilities of Security Analysts

Security analysts help protect security zones by:

- Managing firewall rules
- Configuring access control policies
- Restricting unauthorized IP addresses
- Allowing only approved ports
- Monitoring network traffic
- Protecting sensitive internal systems

---

# Security Zone Summary

| Zone | Purpose | Example |
|------|---------|----------|
| **Uncontrolled Zone** | External public network | Internet |
| **Controlled Zone** | Protected organizational network | Company network |
| **DMZ** | Hosts public-facing services | Web, DNS, Email servers |
| **Internal Network** | Private organizational resources | Employee systems, databases |
| **Restricted Zone** | Highly confidential information | Payroll, financial records |

---

# Key Terms

| Term | Definition |
|------|------------|
| **Security Zone** | A segmented part of a network with specific security rules and access permissions |
| **Uncontrolled Zone** | Any network outside the organization's control, such as the internet |
| **Controlled Zone** | The protected internal network managed by an organization |
| **Demilitarized Zone (DMZ)** | A network segment that hosts public-facing services while protecting the internal network |
| **Internal Network** | The organization's private network containing internal systems and resources |
| **Restricted Zone** | A highly secured network area containing confidential information |
| **Firewall** | A security device or software that filters network traffic |
| **Access Control Policy** | Firewall rules that determine which users, IP addresses, ports, and services are allowed access |
| **Defense in Depth** | A layered security approach using multiple security controls to protect systems |

---

# Key Takeaways

- Security zones divide networks into separate segments with different security rules.
- The **uncontrolled zone** is the public internet.
- The **controlled zone** contains protected internal network segments.
- The **DMZ** hosts public-facing services while isolating them from internal systems.
- The **internal network** stores private organizational resources.
- The **restricted zone** contains the most sensitive information and is accessible only to privileged users.
- Firewalls and access control policies regulate traffic between zones and provide layered protection.

---

## ✅ Lesson Complete

✔ Learned about security zones

✔ Understood controlled and uncontrolled zones

✔ Explored the DMZ and its purpose

✔ Learned how firewalls protect network segments

✔ Understood access control policies and defense in depth