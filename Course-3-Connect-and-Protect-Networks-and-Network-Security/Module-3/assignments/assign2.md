
# Network Security Assessment Notes

This document contains practice questions, selected answers, feedback, and scores from a network security assessment.

---

## Question 1

**Question:**

Passive packet sniffing involves data packets being manipulated while in transit, which may include injecting internet protocols to redirect the packets to unintended ports or changing the information the packet contains.

**Options:**

- True
- False ✅

**Result:**

- **Correct**
- **Score:** 1 / 1

**Explanation:**

Active packet sniffing is a type of attack that involves data packets being manipulated while in transit. This can include injecting internet protocols to redirect the packets to unintended ports or changing the information the packet contains.

Passive packet sniffing is a type of attack where data packets are only read while in transit.

---

## Question 2

**Question:**

Fill in the blank:

> A security analyst can protect against malicious packet sniffing by _____ to encrypt data as it travels across a network.

**Options:**

- Using free public Wi-Fi
- Using only websites with HTTP at the beginning of their domain addresses
- Using a VPN ✅
- Using a network hub

**Result:**

- **Correct**
- **Score:** 1 / 1

**Explanation:**

A security analyst can protect against malicious packet sniffing by using a **VPN** to encrypt data as it travels across a network.

A VPN is a network security service that changes a public IP address and hides a virtual location to keep data private when using a public network.

---

## Question 3

**Question:**

Which type of attack involves an attacker changing the source IP of a data packet to impersonate an authorized system and gain access to the network?

**Options:**

- IP spoofing ✅
- On-path attack
- Ping of death
- Replay attack

**Result:**

- **Correct**
- **Score:** 1 / 1

**Explanation:**

**IP spoofing** involves an attacker changing the source IP address of a data packet to impersonate an authorized system and gain unauthorized access to a network.

---

## Question 4

**Question:**

Which of the following statements accurately describes a smurf attack?

**Options:**

- A network attack performed when an attacker intercepts a data packet in transit and delays it or repeats it at another time
- A DoS attack performed by an attacker repeatedly sending ICMP packets to a network server
- A DoS attack caused when a hacker sends an oversized ICMP packet that exceeds the maximum packet size
- A network attack performed when an attacker sniffs an authorized user's IP address and floods it with packets ✅

**Result:**

- **Incorrect**
- **Score:** 0 / 1

**Explanation:**

A **smurf attack** is a network attack performed when an attacker spoofs an authorized user's IP address and floods it with ICMP packets.

It combines:

- **Distributed Denial-of-Service (DDoS)**
- **IP Spoofing**

---

## Assessment Summary

| Question | Result |
|----------|--------|
| Question 1 | ✅ Correct |
| Question 2 | ✅ Correct |
| Question 3 | ✅ Correct |
| Question 4 | ❌ Incorrect |

**Current Score:** **3 / 4**