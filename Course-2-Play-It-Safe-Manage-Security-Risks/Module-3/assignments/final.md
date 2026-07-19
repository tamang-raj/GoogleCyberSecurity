# Module 3 Practice Quiz — SIEM Tools

**Course:** Google Cybersecurity Professional Certificate  
**Course 2:** Play It Safe: Manage Security Risks  
**Module:** 3 – SIEM Tools

**Score:** **6.5 / 8 (81.25%)**

---

# Quiz Results

## Question 1

### Question
**Which of the following statements correctly describe logs? (Select three)**

- ❌ Actions such as using a username or password are recorded in a firewall log.
- ✅ Events related to websites, emails, or file shares are recorded in a server log.
- ✅ A network log is a record of all computers and devices that enter and leave a network.
- ✅ A log is a record of events that occur within an organization's systems and networks.

### ✔ Correct Answers

- Events related to websites, emails, or file shares are recorded in a **server log**.
- A **network log** records all computers and devices entering and leaving a network.
- A **log** is a record of events that occur within an organization's systems and networks.

### ❌ Mistake

**Selected:**
- Actions such as using a username or password are recorded in a firewall log.

**Why it's incorrect:**
Username and password requests are recorded in **server logs**, not firewall logs.

Firewall logs record:

- Incoming connections
- Outgoing connections
- Allowed traffic
- Blocked traffic
- Connection attempts

Server logs record:

- Login requests
- Username requests
- Password requests
- Website activity
- Email services
- File-sharing services

---

## Question 2

### Question
**What are some of the key benefits of SIEM tools? (Select three)**

- ❌ Automatic customization to changing security needs
- ✅ Minimize the number of logs to be manually reviewed
- ✅ Deliver automated alerts
- ✅ Increase efficiency

### ✔ Correct Answers

- Minimize manual log review
- Deliver automated alerts
- Increase efficiency

### Explanation

SIEM tools:

- Collect logs automatically
- Correlate events
- Generate alerts
- Reduce manual investigations
- Improve analyst productivity

---

## Question 3

### Question
**Fill in the blank: A security professional creates a dashboard that displays technical attributes about business operations called ______, such as incoming and outgoing network traffic.**

- ✅ Metrics
- Averages
- Logs
- SIEM tools

### ✔ Correct Answer

**Metrics**

### Explanation

Metrics are measurable values that monitor system performance.

Examples include:

- Response time
- Availability
- Failure rate
- Network traffic
- Login attempts

---

## Question 4

### Question
**A security team chooses to implement a SIEM tool that will be managed and maintained by the organization's IT department, rather than a third-party vendor. What type of tool are they using?**

- Cloud-hosted
- Department-hosted
- ✅ Self-hosted
- Hybrid

### ✔ Correct Answer

**Self-hosted**

### Explanation

A self-hosted SIEM:

- Runs on the organization's infrastructure.
- Is managed internally.
- Gives full control over security and data.

Example:

- Splunk Enterprise

---

## Question 5

### Question
**You are a security professional, and you want to save time by using a SIEM tool that will be managed by a provider and only be accessible through the internet. What type of tool do you choose?**

- ✅ Cloud-hosted
- IT-hosted
- Hybrid
- Self-hosted

### ✔ Correct Answer

**Cloud-hosted**

### Explanation

Cloud-hosted SIEM solutions:

- Are managed by vendors.
- Require little maintenance.
- Scale easily.
- Are accessed over the internet.

Examples:

- Splunk Cloud
- Microsoft Sentinel

---

## Question 6

### Question
**Fill in the blank: SIEM tools retain, analyze, and search an organization's _____ to provide security information and alerts.**

- Database
- Hardware
- ✅ Log data
- Cloud applications

### ✔ Correct Answer

**Log data**

### Explanation

SIEM platforms collect log data from:

- Firewalls
- Servers
- Networks
- Endpoints
- Applications
- Security devices

They analyze this information to detect threats and generate alerts.

---

## Question 7

### Question
**Which tool provides a comprehensive, visual summary of security-related data, including metrics?**

- ✅ SIEM
- Network protocol analyzer (packet sniffer)
- Command-line interface
- Playbook

### ✔ Correct Answer

**SIEM**

### Explanation

SIEM dashboards display:

- Charts
- Graphs
- Tables
- Alerts
- Trends
- Metrics

These dashboards help analysts quickly investigate suspicious activity.

---

## Question 8

### Question
**Fill in the blank: The wide exposure and immediate access to the source code of open-source tools makes it _____ likely that issues will occur.**

- Equally
- ❌ Less
- Very
- ✅ More

### ✔ Correct Answer

**More**

### ❌ Mistake

**Selected:** Less likely

### Why it's incorrect

Because the source code is publicly available, **more people can inspect it**, making it **more likely that bugs and vulnerabilities will be discovered quickly**. The broad exposure means issues are easier to identify and fix through community collaboration.

Although open-source software may initially have more visible issues due to transparency, those issues are often resolved faster than in proprietary software.

---

# Quiz Summary

| Question | Topic | Result |
|----------|-------|--------|
| Q1 | Types of Logs | ❌ (Missed one option) |
| Q2 | SIEM Benefits | ✅ |
| Q3 | Metrics | ✅ |
| Q4 | Self-hosted SIEM | ✅ |
| Q5 | Cloud-hosted SIEM | ✅ |
| Q6 | Log Data | ✅ |
| Q7 | SIEM Dashboards | ✅ |
| Q8 | Open-source Tools | ❌ |

---

# Mistakes to Remember

## ❌ Question 1

**Wrong:** Username/password actions are stored in firewall logs.

**Correct:** Username/password requests are stored in **server logs**.

---

## ❌ Question 8

**Wrong Answer:** Less likely

**Correct Answer:** More likely

**Reason:** Public access to the source code allows many developers and security researchers to inspect it, making vulnerabilities more likely to be found and fixed quickly.

---

# Final Score

**6.5 / 8 (81.25%)**