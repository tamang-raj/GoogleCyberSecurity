# Proxy Servers Notes

> **Google Cybersecurity Professional Certificate**  
> **Course 2 – Module 6**

---

# 📖 Overview

This lesson explains how **proxy servers** improve network security by acting as intermediaries between users and the internet. Proxy servers help protect internal networks by filtering traffic, hiding internal IP addresses, blocking malicious websites, and managing access to network resources.

---

# 🎯 Learning Objectives

- Understand what a proxy server is
- Learn how proxy servers improve security
- Understand the difference between public and private IP addresses
- Learn the different types of proxy servers
- Understand the roles of forward, reverse, and email proxy servers

---

# 🌐 What is a Proxy Server?

A **proxy server** is an intermediary that sits between a client and another server.

Instead of communicating directly with websites or internet services, client requests first go to the proxy server.

The proxy server then forwards the request to the destination server and returns the response to the client.

```text
Client
   │
   ▼
Proxy Server
   │
   ▼
Internet / Web Server
```

---

# Why Use a Proxy Server?

Organizations use proxy servers to:

- Add an extra layer of security
- Hide internal network information
- Filter internet traffic
- Block malicious websites
- Improve network performance
- Control user access

---

# Public and Private IP Addresses

A proxy server has its own **public IP address**, which is different from the organization's private network.

Instead of exposing the internal network:

```text
Internet
    │
    ▼
Public IP (Proxy Server)
    │
    ▼
Private Internal Network
```

This hides the internal network's IP addresses from external users and attackers.

---

# Security Benefits of Proxy Servers

## 1. Hide Internal Network Information

The proxy server masks the internal network's private IP addresses.

Benefits:

- Prevents attackers from directly seeing internal systems
- Adds another layer of protection
- Reduces exposure of confidential resources

---

## 2. Filter Web Traffic

Proxy servers can control which websites users are allowed to visit.

Examples:

- Block malicious websites
- Block phishing sites
- Restrict inappropriate content

---

## 3. Cache Frequently Requested Data

A proxy server stores frequently accessed data in temporary memory (cache).

Benefits:

- Faster responses
- Reduced server workload
- Less direct communication with internal servers
- Improved security

---

# Types of Proxy Servers

There are three main proxy server types covered in this lesson.

---

# 1. Forward Proxy Server

A **forward proxy** sits between internal users and the internet.

```text
User
   │
   ▼
Forward Proxy
   │
   ▼
Internet
```

### Functions

- Regulates internet access
- Restricts user activity
- Hides the user's IP address
- Approves outgoing requests

### Benefits

- Improves privacy
- Blocks unsafe websites
- Controls internet usage

---

# 2. Reverse Proxy Server

A **reverse proxy** sits in front of an organization's internal servers.

```text
Internet
    │
    ▼
Reverse Proxy
    │
    ▼
Internal Servers
```

### Functions

- Accepts incoming internet requests
- Filters external traffic
- Protects internal servers
- Approves requests before forwarding them

### Benefits

- Protects confidential data
- Prevents direct access to internal servers
- Adds another security layer

---

# 3. Email Proxy Server

An **email proxy server** protects an organization's email system.

### Functions

- Filters spam emails
- Verifies sender addresses
- Helps prevent phishing attacks

### Benefits

- Reduces spam
- Detects impersonation attempts
- Protects users from malicious emails

---

# Forward Proxy vs Reverse Proxy

| Forward Proxy | Reverse Proxy |
|---------------|---------------|
| Protects users | Protects servers |
| Controls outgoing traffic | Controls incoming traffic |
| Hides client IP addresses | Hides internal servers |
| Filters user internet access | Filters internet requests |

---

# Proxy Server Workflow

### Forward Proxy

```text
Employee
     │
     ▼
Forward Proxy
     │
     ▼
Internet
```

---

### Reverse Proxy

```text
Internet Users
       │
       ▼
Reverse Proxy
       │
       ▼
Internal Web Servers
```

---

# Responsibilities of Security Analysts

Security analysts use proxy servers to:

- Restrict unsafe websites
- Monitor internet traffic
- Protect internal servers
- Reduce phishing risks
- Configure access policies
- Improve overall network security

---

# Key Terms

| Term | Definition |
|------|------------|
| **Proxy Server** | An intermediary that forwards requests between clients and servers while providing security and filtering capabilities |
| **Forward Proxy** | A proxy server that regulates and restricts users' access to the internet by approving outgoing requests |
| **Reverse Proxy** | A proxy server that regulates and restricts internet access to internal servers by filtering incoming requests |
| **Email Proxy Server** | A proxy server that filters spam and verifies sender addresses to reduce phishing attacks |
| **Public IP Address** | The IP address visible on the internet, used by the proxy server |
| **Private IP Address** | An IP address used within an organization's internal network |
| **Cache** | Temporary storage used to keep frequently requested data for faster access |

---

# Key Takeaways

- A **proxy server** acts as an intermediary between clients and servers.
- Proxy servers improve security by **hiding internal network information** and **filtering traffic**.
- They can **block unsafe websites** and **cache frequently requested data** to improve performance and reduce direct communication with internal servers.
- A **forward proxy** protects users and manages outgoing internet access.
- A **reverse proxy** protects internal servers by filtering incoming internet traffic.
- An **email proxy server** filters spam and helps prevent phishing attacks.

---

## ✅ Lesson Complete

✔ Learned what a proxy server is

✔ Understood how proxy servers improve network security

✔ Learned the difference between forward and reverse proxy servers

✔ Explored email proxy servers and phishing protection

✔ Understood how proxy servers hide internal network information