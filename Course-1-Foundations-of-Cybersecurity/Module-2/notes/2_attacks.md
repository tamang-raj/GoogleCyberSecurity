# Common Types of Cyberattacks

Cyberattacks are different techniques used by threat actors to gain unauthorized access to systems, networks, or sensitive information. Understanding these attack types helps cybersecurity professionals recognize threats and implement effective defenses.

---

# Password Attacks

## Definition

A **password attack** is an attempt to gain unauthorized access to password-protected devices, systems, networks, or accounts.

Attackers try to discover or steal passwords in order to log in as legitimate users.

---

## Common Password Attack Methods

### Brute Force Attack

Attempts every possible password combination until the correct password is found.

**Characteristics:**

- Simple but time-consuming.
- More effective against weak passwords.
- Can often be prevented with account lockout policies and Multi-Factor Authentication (MFA).

---

### Dictionary Attack

Uses a predefined list of common passwords and words instead of trying every possible combination.

Examples:

- `password123`
- `welcome`
- `qwerty`
- `admin`

---

### Rainbow Table Attack

Uses precomputed tables of hashed passwords to quickly determine the original password from its hash.

**Defense:**

- Password salting
- Strong hashing algorithms
- Multi-Factor Authentication (MFA)

---

## Prevention

- Use long, complex passwords.
- Enable Multi-Factor Authentication (MFA).
- Avoid password reuse.
- Use password managers.
- Implement account lockout policies.

---

# Social Engineering

## Definition

**Social engineering** is a manipulation technique that exploits **human behavior** rather than technical vulnerabilities to gain private information, access, or valuables.

Instead of attacking computers directly, attackers trick people into helping them.

---

## Common Social Engineering Attacks

### Phishing

Fraudulent emails or messages designed to steal sensitive information or install malware.

---

### Spear Phishing

Highly targeted phishing attacks aimed at specific individuals or organizations.

---

### Business Email Compromise (BEC)

Attackers impersonate executives, vendors, or trusted contacts to steal money or confidential information.

---

### Vishing

Voice phishing conducted through phone calls.

---

### Smishing

Phishing conducted through SMS or text messages.

---

## Why Social Engineering Works

Attackers exploit human emotions such as:

- Trust
- Curiosity
- Fear
- Urgency
- Authority

---

## Prevention

- Verify suspicious requests.
- Never share passwords.
- Confirm requests through trusted channels.
- Complete regular security awareness training.

---

# Physical Attacks

## Definition

A **physical attack** targets an organization's physical environment to gain access to digital systems or sensitive information.

---

## Examples

### USB Baiting

Attackers leave infected USB drives where employees are likely to find them.

When plugged into a computer, the USB installs malware.

---

### Access Card Cloning

Attackers duplicate employee access cards to enter restricted areas.

---

### Device Theft

Stealing laptops, mobile devices, or storage media containing sensitive data.

---

### Tailgating

Following an authorized employee into a secure area without proper authorization.

---

## Prevention

- Restrict physical access.
- Encrypt devices.
- Require employee badges.
- Educate employees about USB baiting.
- Install surveillance systems.

---

# Adversarial Artificial Intelligence (AI)

## Definition

**Adversarial AI** is the use or manipulation of Artificial Intelligence (AI) and Machine Learning (ML) technologies to make cyberattacks more effective or evade detection.

---

## Goals

- Bypass AI-based security systems.
- Evade malware detection.
- Automate attacks.
- Increase attack accuracy.

---

## Examples

- AI-generated phishing emails.
- AI-assisted malware.
- Manipulated machine learning models.

---

## Prevention

- Train AI models using diverse datasets.
- Continuously update AI detection systems.
- Combine AI detection with human oversight.

---

# Supply-Chain Attacks

## Definition

A **supply-chain attack** targets trusted software, hardware, vendors, or service providers instead of attacking the intended victim directly.

Attackers compromise a trusted component before it reaches the target organization.

---

## Common Targets

- Software updates
- Third-party vendors
- Hardware manufacturers
- Cloud service providers
- Open-source software libraries

---

## Examples

- Malicious software updates.
- Compromised vendor systems.
- Infected hardware components.

---

## Prevention

- Verify software integrity.
- Assess vendor security practices.
- Monitor third-party access.
- Apply software updates promptly.
- Implement Zero Trust principles.

---

# Cryptographic Attacks

## Definition

A **cryptographic attack** attempts to compromise encrypted information or secure communications.

Attackers seek to discover encryption keys or exploit weaknesses in encryption algorithms.

---

## Common Types

### Brute Force Attack

Attempts every possible encryption key until the correct one is found.

---

### Cryptanalysis

Studies encryption methods to discover weaknesses.

---

### Man-in-the-Middle (MitM)

Intercepts encrypted communications between two parties.

---

## Prevention

- Use strong encryption algorithms.
- Protect encryption keys.
- Implement secure key management.
- Keep cryptographic software updated.

---

# Comparison of Common Cyberattacks

| Attack Type | Primary Target | Example |
|-------------|----------------|---------|
| **Password Attack** | User credentials | Brute force, dictionary attack |
| **Social Engineering** | People | Phishing, vishing, spear phishing |
| **Physical Attack** | Physical devices and facilities | USB baiting, tailgating |
| **Adversarial AI** | AI and ML systems | AI-generated phishing, AI evasion |
| **Supply-Chain Attack** | Vendors and trusted software | Compromised software updates |
| **Cryptographic Attack** | Encrypted data | Brute-force key attacks, cryptanalysis |

---

# Key Takeaways

- **Password attacks** attempt to compromise passwords through techniques such as brute-force, dictionary, or rainbow table attacks.
- **Social engineering** exploits human trust and behavior rather than technical vulnerabilities.
- **Physical attacks** target an organization's physical environment, including devices, access controls, and facilities.
- **Adversarial AI** uses artificial intelligence to improve attack effectiveness and evade detection.
- **Supply-chain attacks** compromise trusted vendors, software, or hardware to reach the final target.
- **Cryptographic attacks** attempt to break or bypass encryption to access protected information.
- Effective cybersecurity requires a layered approach that combines strong authentication, user awareness, physical security, secure software practices, and robust encryption.