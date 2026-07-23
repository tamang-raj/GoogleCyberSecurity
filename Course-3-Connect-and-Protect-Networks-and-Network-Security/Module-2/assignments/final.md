# Module Quiz Notes: Network Protocols, Firewalls, VPNs & Proxy Servers

> **Google Cybersecurity Professional Certificate**  
> **Course 3 – Module 2 Quiz**

**Score:** **10/10 (100%)** 🎉

---

# Question 1

## What network protocol helps data get to the right place by determining the MAC address of the next router or device on its path?

- Hypertext Transfer Protocol Secure (HTTPS)
- Secure Sockets Layer/Transport Layer Security (SSL/TLS)
- ✅ **Address Resolution Protocol (ARP)**
- Transmission Control Protocol (TCP)

### Explanation

**Address Resolution Protocol (ARP)** translates an IP address into a MAC address, allowing devices to locate the next router or destination device on a local network.

---

# Question 2

## Fill in the blank:

The _______ maintains Wi-Fi standards.

- ✅ **IEEE 802.11**
- Transmission Control Protocol (TCP)
- Domain Name System (DNS)
- Wi-Fi Protected Access (WPA)

### Explanation

**IEEE 802.11** is the family of standards maintained by the Institute of Electrical and Electronics Engineers (IEEE) that defines wireless LAN (Wi-Fi) communications.

---

# Question 3

## Fill in the blank:

A ____ firewall operates based on predefined rules. It is not used to keep track of information from data packets.

- ✅ **Stateless**
- Stateful
- Cloud-based
- Next-Generation Firewall (NGFW)

### Explanation

A **Stateless Firewall**:

- Uses predefined filtering rules
- Inspects each packet independently
- Does **not** track active connections

---

# Question 4

## Which type of firewall can perform deep packet inspection and intrusion detection?

- Stateful Firewall
- Documented Firewall
- Stateless Firewall
- ✅ **Next-Generation Firewall (NGFW)**

### Explanation

A **Next-Generation Firewall (NGFW)** provides advanced security features such as:

- Deep Packet Inspection (DPI)
- Intrusion Detection and Prevention (IDS/IPS)
- Application awareness
- Threat intelligence integration

---

# Question 5

## How do VPNs preserve confidentiality?

- Monitor traffic to and from a network
- Use temporary memory to store data requested by external servers
- ✅ **Encrypt data in transit**
- Translate internet domain names to IP addresses

### Explanation

VPNs preserve confidentiality by:

- Encrypting network traffic
- Creating secure tunnels
- Preventing unauthorized users from reading transmitted data

---

# Question 6

## Fill in the blank:

VPN services perform _____ to protect sensitive data by wrapping it in other data packets.

- Network segmentation
- Packet sniffing
- ✅ **Encapsulation**
- Transmission control

### Explanation

**Encapsulation** wraps encrypted data inside another packet before transmission, creating a secure VPN tunnel.

---

# Question 7

## What network is part of the uncontrolled zone?

- Subnets
- Web servers
- Internal networks
- ✅ **Internet**

### Explanation

The **Uncontrolled Zone** refers to networks outside an organization's control, primarily the **Internet**.

---

# Question 8

## What network zone includes public-facing services such as web servers, proxy servers, and DNS servers?

- Restricted Zone
- ✅ **Demilitarized Zone (DMZ)**
- Uncontrolled Zone
- Virtual Private Network

### Explanation

The **Demilitarized Zone (DMZ)** hosts public-facing services while isolating them from the internal network to improve security.

Common DMZ services include:

- Web servers
- DNS servers
- Email servers
- Proxy servers

---

# Question 9

## A security analyst implements a proxy server to secure internal networks. What are some of the proxy server's primary functions? (Select three)

- Divide the network into segments to maintain privacy within corporate groups
- ✅ Temporarily stores data that is frequently requested by external servers
- ✅ Determine whether requests to connect to a website are allowed
- ✅ Use public IP addresses that are different from the rest of the private network

### Explanation

A **Proxy Server**:

- Caches frequently requested data
- Filters and approves requests
- Hides internal IP addresses using its own public IP
- Improves both security and performance

---

# Question 10

## Which statements accurately describe forward and reverse proxy servers? (Select three)

- ✅ Forward proxy servers receive outgoing traffic from users, approve it, then forward it to the internet.
- Reverse proxy servers work by hiding a user's IP address and approving all outgoing requests.
- ✅ Forward proxy servers regulate and restrict a person's access to the internet.
- ✅ Reverse proxy servers accept external traffic, approve it, then forward it to internal servers.

### Explanation

### Forward Proxy

- Sits between users and the internet
- Controls outgoing traffic
- Hides users' IP addresses

### Reverse Proxy

- Sits in front of internal servers
- Controls incoming internet traffic
- Protects internal resources from direct exposure

---

# Key Concepts Reviewed

| Concept | Description |
|----------|-------------|
| ARP | Resolves IP addresses into MAC addresses |
| IEEE 802.11 | Wi-Fi networking standard |
| Stateless Firewall | Uses predefined rules without tracking connections |
| NGFW | Performs deep packet inspection and intrusion detection |
| VPN | Encrypts data and protects privacy |
| Encapsulation | Wraps encrypted data inside another packet |
| Uncontrolled Zone | External network (Internet) |
| DMZ | Network zone containing public-facing services |
| Proxy Server | Filters requests and hides internal IP addresses |
| Forward Proxy | Controls users' internet access |
| Reverse Proxy | Protects internal servers from external traffic |

---

# Quick Revision

- ✅ ARP resolves IP addresses to MAC addresses.
- ✅ IEEE 802.11 defines Wi-Fi standards.
- ✅ Stateless firewalls inspect packets independently.
- ✅ NGFWs provide advanced threat detection through deep packet inspection.
- ✅ VPNs protect confidentiality using encryption and encapsulation.
- ✅ The Internet belongs to the uncontrolled zone.
- ✅ The DMZ hosts public-facing services like web and DNS servers.
- ✅ Proxy servers cache data, filter requests, and hide internal IP addresses.
- ✅ Forward proxies manage outgoing traffic; reverse proxies protect internal servers from incoming traffic.

---

# 🎯 Quiz Result

**Score:** **10/10 (100%)** ✅