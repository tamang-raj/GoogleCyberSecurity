---

# Network Segmentation

**Network segmentation** is the practice of dividing a network into smaller, isolated sections to improve performance, management, and security.

Subnetting is one of the primary methods used to achieve network segmentation.

## Benefits of Network Segmentation

- Improves network performance by reducing unnecessary traffic
- Enhances security by isolating sensitive systems
- Helps prevent attackers from moving freely across a network
- Makes network management easier
- Supports the creation of security zones

---

# Network Segmentation Example

Instead of:

```text
One Large Network

Finance
HR
Engineering
Servers
Guest Wi-Fi
```

Organizations create separate network segments:

```text
Company Network

├── Finance Subnet
├── HR Subnet
├── Engineering Subnet
├── Server Subnet
└── Guest Wi-Fi Subnet
```

Each segment can have its own:

- Firewall rules
- Access permissions
- Security policies

This limits unauthorized access and reduces the impact of a security incident.

---

# Network Segmentation vs. Subnetting

| Network Segmentation | Subnetting |
|----------------------|------------|
| A security strategy that divides a network into isolated segments | A networking technique used to divide a network into smaller logical subnetworks |
| Improves security and management | Improves efficiency, routing, and security |
| Can use firewalls, VLANs, and subnetting | Uses IP addressing and CIDR notation |
| Supports security zones | Creates the subnetworks used for segmentation |

> **Key Point:** In this course, subnetting is introduced as a way to implement **network segmentation**, helping organizations improve both network performance and security.