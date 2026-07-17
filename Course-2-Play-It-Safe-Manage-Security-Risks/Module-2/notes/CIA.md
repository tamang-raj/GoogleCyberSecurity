# CIA Triad (Confidentiality, Integrity, Availability)

## Overview

The **CIA Triad** is one of the most fundamental security models in cybersecurity. It serves as the foundation for protecting an organization's data, systems, and assets from threats, risks, and vulnerabilities.

The three core principles are:

- 🔒 Confidentiality
- ✅ Integrity
- ⚡ Availability

Security professionals use the CIA Triad to design, evaluate, and improve security policies and controls.

---

# CIA Triad

```text
          CIA TRIAD

        🔒 Confidentiality
               ▲
              / \
             /   \
            /     \
           /       \
   ✅ Integrity ---- ⚡ Availability
```

---

# 1. Confidentiality

## Definition

**Confidentiality** ensures that only **authorized users** can access sensitive information.

Information is shared on a **"need-to-know" basis**, preventing unauthorized access.

---

## Goal

Protect sensitive information from unauthorized disclosure.

---

## Examples

- Employee payroll records
- Customer personal information (PII)
- Credit card numbers
- Medical records
- Business secrets

---

## Security Controls Used

- Encryption
- Multi-Factor Authentication (MFA)
- Passwords
- Access control lists (ACLs)
- Biometrics
- Role-Based Access Control (RBAC)

---

## Example

Only HR employees can view employee salary information.

Everyone else is denied access.

---

# 2. Integrity

## Definition

**Integrity** ensures that data remains:

- Accurate
- Complete
- Authentic
- Reliable

Data should never be modified without authorization.

---

## Goal

Protect information from unauthorized changes.

---

## Security Controls Used

- Hashing
- Digital signatures
- Checksums
- Version control
- File integrity monitoring

---

## Example

A customer transfers **$500**.

The amount should never change to **$5,000** during processing.

---

# 3. Availability

## Definition

**Availability** ensures that authorized users can access data and systems whenever they need them.

Systems should remain operational even during failures or cyberattacks.

---

## Goal

Ensure continuous access to systems and information.

---

## Security Controls Used

- Data backups
- Disaster recovery plans
- Redundant servers
- UPS (Uninterruptible Power Supply)
- Load balancing
- System monitoring

---

## Example

Customers should be able to access online banking services 24/7.

---

# Real-World Banking Example

Banks rely on all three components of the CIA Triad.

## Confidentiality

Protect customer:

- Account information
- PINs
- Passwords
- Personal information

using:

- Encryption
- MFA
- Access controls

---

## Integrity

Ensure:

- Transactions are accurate
- Balances are correct
- Records are authentic

---

## Availability

Ensure customers can:

- Access ATMs
- Use mobile banking
- Log into online banking
- Transfer money anytime

---

# How the CIA Triad Works Together

```text
User Requests Data
        │
        ▼
Confidentiality
(Is the user authorized?)
        │
        ▼
Integrity
(Is the data accurate and trustworthy?)
        │
        ▼
Availability
(Can the data be accessed when needed?)
```

---

# CIA Triad vs Security Goals

| Principle | Primary Goal | Example |
|------------|--------------|---------|
| 🔒 Confidentiality | Prevent unauthorized access | Encryption, MFA |
| ✅ Integrity | Prevent unauthorized modification | Hashing, Digital Signatures |
| ⚡ Availability | Ensure reliable access | Backups, Redundant Servers |

---

# Threats to the CIA Triad

| CIA Component | Common Threats |
|--------------|----------------|
| Confidentiality | Phishing, Data breaches, Insider threats |
| Integrity | Malware, Unauthorized modifications, SQL injection |
| Availability | DDoS attacks, Hardware failure, Ransomware |

---

# Why the CIA Triad Matters

Security professionals use the CIA Triad to:

- Build secure systems
- Evaluate security controls
- Protect organizational assets
- Reduce cybersecurity risks
- Respond to security incidents
- Maintain customer trust

---

# Analyst's Role

As a cybersecurity analyst, you will use the CIA Triad to:

- Protect sensitive data
- Monitor systems for threats
- Verify data integrity
- Ensure systems remain available
- Respond to security incidents
- Reduce organizational risk

---

# Key Takeaways

- The CIA Triad is the foundation of cybersecurity.
- It consists of **Confidentiality, Integrity, and Availability**.
- Confidentiality protects data from unauthorized access.
- Integrity ensures data remains accurate and trustworthy.
- Availability ensures authorized users can access systems when needed.
- Effective cybersecurity requires balancing all three principles.

---

# Quick Revision

### 🔒 Confidentiality

- Need-to-know access
- Encryption
- Passwords
- MFA
- Access control

---

### ✅ Integrity

- Accurate data
- Authentic information
- Hashing
- Digital signatures
- File integrity monitoring

---

### ⚡ Availability

- Continuous access
- Backups
- Disaster recovery
- Redundant servers
- System monitoring

---

# Final Summary

The **CIA Triad** is the cornerstone of information security. Every cybersecurity strategy, framework, and control ultimately supports one or more of these three principles:

- **Confidentiality** protects sensitive information.
- **Integrity** ensures information remains accurate and trustworthy.
- **Availability** guarantees that authorized users can access information whenever they need it.

Together, these principles help organizations defend against cyber threats while maintaining secure, reliable, and resilient systems.