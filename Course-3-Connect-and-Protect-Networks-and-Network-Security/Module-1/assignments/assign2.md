# Module 6 Quiz — TCP/IP, OSI Model, and Network Communication

> **Google Cybersecurity Professional Certificate**
> **Course 2 – Module 6 Quiz Notes**

---

## 📊 Quiz Score

**Score:** **5 / 5 (100%)** ✅

---

# Question 1

### ❓ Question

**What type of information is contained within the header of an IP packet?**

- A string of data indicating that the data transmission is complete
- ✅ **The sender's IP address, the destination's MAC address, and the protocol to use**
- An explanation of how the port number will be processed by the receiving device
- The message that needs to be transmitted to the receiving device

### ✅ Correct Answer

**The sender's IP address, the destination's MAC address, and the protocol to use**

### 💡 Explanation

An **IP packet header** contains important routing information that allows data to reach the correct destination, including:

- Source IP address
- Destination MAC address
- Protocol information

The actual message is stored in the **payload**, not the header.

---

# Question 2

### ❓ Question

**What characteristics do the TCP/IP and OSI models share?** *(Select all that apply.)*

- ✅ Both models illustrate network processes and protocols for data transmission between two or more systems.
- ✅ Both models define standards for networking and divide the network communication process into different layers.
- ❌ Both models have 7 layers.
- ✅ Both models include an application and a transport layer.

### ✅ Correct Answers

- Both models illustrate network processes and protocols for data transmission between two or more systems.
- Both models define standards for networking and divide the communication process into different layers.
- Both models include an application layer and a transport layer.

### 💡 Explanation

Both networking models:

- Explain how devices communicate.
- Organize communication into layers.
- Standardize network operations.

**Difference:**

| TCP/IP Model | OSI Model |
|--------------|-----------|
| 4 Layers | 7 Layers |

---

# Question 3

### ❓ Question

**What is the Transmission Control Protocol (TCP)?**

- A unique address that every device on a network is assigned
- A software application that organizes data
- ✅ **An internet communication convention**
- Guidelines for proper network operations

### ✅ Correct Answer

**An internet communication convention**

### 💡 Explanation

**TCP (Transmission Control Protocol)** is a communication protocol that:

- Establishes a connection between devices.
- Ensures reliable data transmission.
- Delivers data in the correct order.
- Detects and retransmits lost packets when necessary.

---

# Question 4

### ❓ Question

**Fill in the blank: A _____ is a software-based location that organizes the sending and receiving of data between devices on a network.**

- packet
- channel
- ✅ **port**
- segment

### ✅ Correct Answer

**Port**

### 💡 Explanation

A **port** is a software-based communication endpoint that allows network applications and services to send and receive data.

Ports help devices identify which application should process incoming network traffic.

Examples include:

- HTTP — Port 80
- HTTPS — Port 443
- FTP — Port 21

---

# Question 5

### ❓ Question

**Which layer of the TCP/IP model has protocols that organize file transfers and email services?**

- Internet layer
- Transport layer
- ✅ **Application layer**
- Network access layer

### ✅ Correct Answer

**Application layer**

### 💡 Explanation

The **Application layer** is responsible for network services used directly by applications.

It includes protocols for:

- File transfers
- Email services
- Web browsing
- Remote access

This layer determines how data interacts with receiving applications.

---

# 📚 Key Concepts Reviewed

- **IP Packet Header** → Contains addressing and protocol information.
- **TCP** → Reliable communication protocol for data transmission.
- **TCP/IP Model** → Four-layer networking model.
- **OSI Model** → Seven-layer networking model.
- **Port** → Software endpoint for network communication.
- **Application Layer** → Supports services such as email and file transfers.

---

## 🎉 Module 6 Quiz Complete

**Final Score:** **5 / 5 (100%)** ✅