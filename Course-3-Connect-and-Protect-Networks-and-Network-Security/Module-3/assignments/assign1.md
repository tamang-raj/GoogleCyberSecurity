```markdown
# README.md

# Network Security Assessment Notes (Part 2)

This document contains practice questions, selected answers, feedback, and scores from a network security assessment.

---

## Question 1

**Question:**

What type of attack uses multiple devices or servers in different locations to flood the target network with unwanted traffic?

**Options:**

- Tailgating attack
- Distributed Denial of Service (DDoS) attack ✅
- Denial of Service (DoS) attack
- Phishing attack

**Result:**

- **Correct**
- **Score:** 1 / 1

**Explanation:**

A **Distributed Denial of Service (DDoS)** attack uses multiple compromised devices or servers from different locations to flood a target network with unwanted traffic, overwhelming its resources.

---

## Question 2

**Question:**

What type of attack poses as a TCP connection and floods a server with packets simulating the first step of the TCP handshake?

**Options:**

- SYN-ACK flood attack
- ICMP flood
- SYN flood attack ✅
- On-path attack

**Result:**

- **Correct**
- **Score:** 1 / 1

**Explanation:**

A **SYN flood attack** simulates the first step of the TCP three-way handshake by sending numerous SYN packets without completing the connection. This overwhelms the server and prevents legitimate connections.

---

## Question 3

**Question:**

Fill in the blank:

> The Denial of Service (DoS) attack _____ is caused when a hacker sends a system an ICMP packet that is bigger than 64 KB.

**Options:**

- SYN flood
- On-path
- Ping of Death ✅
- ICMP flood

**Result:**

- **Correct**
- **Score:** 1 / 1

**Explanation:**

The **Ping of Death** is a DoS attack in which an attacker sends an oversized ICMP packet (larger than 64 KB), potentially causing the target system to crash or become unstable.

---

## Question 4

**Question:**

Which types of attacks take advantage of communication protocols by sending an overwhelming number of requests to a server? *(Select all that apply.)*

**Options:**

- Tailgating attack
- ICMP flood attack ✅
- TCP connection attack ✅
- SYN flood attack ✅

**Result:**

- **Partially Correct**
- **Score:** 0.8 / 1

**Explanation:**

The attacks that exploit communication protocols by overwhelming a server with requests include:

- **ICMP flood attack**
- **TCP connection attack**
- **SYN flood attack**

A **tailgating attack** is a physical security attack and is unrelated to network communication protocols.

---

## Assessment Summary

| Question | Result |
|----------|--------|
| Question 1 | ✅ Correct |
| Question 2 | ✅ Correct |
| Question 3 | ✅ Correct |
| Question 4 | 🟡 Partially Correct |

**Current Score:** **3.8 / 4**
```
