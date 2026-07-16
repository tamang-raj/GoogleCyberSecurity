# Risk Management, Threats, Risks, and Vulnerabilities

## Overview

Organizations use **risk management** to protect valuable assets from cyber threats. These assets can be **digital** (such as customer data and databases) or **physical** (such as servers and networking equipment). Security professionals identify risks, evaluate vulnerabilities, and apply appropriate strategies to minimize the impact of potential attacks.

---

# Organizational Assets

Assets are anything valuable to an organization.

### Digital Assets
- Personally Identifiable Information (PII)
- Customer databases
- Intellectual property
- Financial records
- Applications
- Cloud resources

### Physical Assets
- Servers
- Computers
- Networking devices
- Data centers
- Office facilities

Protecting these assets is the primary goal of cybersecurity.

---

# Risk Management Strategies

Organizations use several strategies to handle cybersecurity risks.

## 1. Risk Acceptance

The organization acknowledges the risk and chooses to accept it because the impact is low or the cost of fixing it outweighs the benefit.

**Example:**
- Using an older internal application with minimal security risk.

---

## 2. Risk Avoidance

The organization eliminates the activity or technology that creates the risk.

**Example:**
- Discontinuing an insecure legacy application.

---

## 3. Risk Transference

The organization transfers the financial or operational impact of a risk to another party.

**Examples:**
- Purchasing cyber insurance
- Outsourcing cloud infrastructure to a managed security provider

---

## 4. Risk Mitigation

The organization reduces the likelihood or impact of a risk by implementing security controls.

**Examples:**
- Multi-Factor Authentication (MFA)
- Firewalls
- Employee security awareness training
- Encryption
- Regular software updates

---

# Common Threats

A **threat** is any event or circumstance that can negatively impact an organization's assets.

## Insider Threats

Threats originating from people inside the organization.

Examples include:
- Current employees
- Former employees
- Contractors
- Vendors
- Trusted partners

Insiders may intentionally or accidentally expose sensitive information.

---

## Advanced Persistent Threats (APTs)

An **Advanced Persistent Threat (APT)** is a sophisticated cyberattack where attackers gain unauthorized access and remain undetected for an extended period.

### Characteristics
- Long-term access
- Stealthy behavior
- Targets sensitive information
- Often conducted by organized groups or nation-state actors

---

# Understanding Risk

A **risk** is anything that can affect the **Confidentiality, Integrity, or Availability (CIA)** of an organization's assets.

## Common Types of Risk

### External Risk
Risks originating outside the organization.

**Examples**
- Hackers
- Malware
- Phishing attacks
- Ransomware

---

### Internal Risk
Risks caused by individuals within the organization.

**Examples**
- Human error
- Insider attacks
- Misconfigured systems

---

### Legacy System Risk

Older systems that no longer receive security updates or patches.

**Examples**
- Unsupported operating systems
- Outdated software
- Legacy hardware

---

### Multiparty Risk

Risks introduced through third-party organizations or vendors.

**Examples**
- Cloud service providers
- Business partners
- Software suppliers
- Managed service providers

---

# Understanding Vulnerabilities

A **vulnerability** is a weakness that a threat actor can exploit to compromise a system.

## Examples of Major Vulnerabilities

### ProxyLogon
A group of vulnerabilities affecting Microsoft Exchange Server that allows attackers to execute remote code and gain unauthorized access.

---

### ZeroLogon

A critical vulnerability in Microsoft's Netlogon authentication protocol that enables attackers to gain domain administrator privileges.

---

### Log4Shell

A severe vulnerability in the Log4j Java logging library that allows attackers to execute arbitrary code remotely.

---

### PetitPotam

A Windows vulnerability that can force authentication requests, enabling attackers to steal credentials or escalate privileges.

---

# Relationship Between Threats, Risks, and Vulnerabilities

```text
Threat
   +
Vulnerability
   ↓
Risk
   ↓
Security Controls
   ↓
Reduced Risk
```

A risk exists when a **threat** can exploit a **vulnerability**.

---

# Key Takeaways

- Organizations protect both **digital** and **physical** assets.
- Four common risk management strategies are:
  1. Acceptance
  2. Avoidance
  3. Transference
  4. Mitigation
- **Threats** are events that can damage organizational assets.
- **Insider threats** and **Advanced Persistent Threats (APTs)** are common cybersecurity threats.
- **Risks** can be external, internal, legacy system-related, or multiparty.
- **Vulnerabilities** are weaknesses that attackers exploit.
- Examples of major vulnerabilities include **ProxyLogon**, **ZeroLogon**, **Log4Shell**, and **PetitPotam**.
- Effective cybersecurity combines risk management strategies with security controls to reduce organizational risk.