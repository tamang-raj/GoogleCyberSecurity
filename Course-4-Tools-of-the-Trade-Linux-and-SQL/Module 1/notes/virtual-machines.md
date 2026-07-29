# Virtual Machines (VMs)

A **Virtual Machine (VM)** is a software-based version of a physical computer. It simulates computer hardware, allowing multiple operating systems to run independently on a single physical machine.

---

# What is a Virtual Machine?

A virtual machine is created using virtualization software that emulates the hardware of a physical computer.

Each virtual machine:
- Has its own operating system.
- Runs its own applications.
- Functions independently of other virtual machines.
- Shares the physical computer's hardware resources.

This allows one physical computer to host multiple virtual computers simultaneously.

---

# How Virtual Machines Work

A physical computer provides resources such as:

- CPU
- Memory (RAM)
- Storage
- Network connectivity

These resources are shared among multiple virtual machines through virtualization software.

```text
                Physical Computer
        +----------------------------+
        | CPU | RAM | Storage | NIC  |
        +----------------------------+
                  │
             Hypervisor
      ┌─────────┼─────────┐
      │         │         │
+-------------+ +-------------+ +-------------+
| Virtual VM1 | | Virtual VM2 | | Virtual VM3 |
| Windows     | | Linux       | | Ubuntu      |
+-------------+ +-------------+ +-------------+
```

Each VM behaves like a completely separate computer, even though they all share the same physical hardware.

---

# Benefits of Virtual Machines

## 1. Security

Virtual machines provide an isolated environment, often called a **sandbox**.

Benefits include:

- Preventing software from affecting the host operating system.
- Isolating malware during analysis.
- Safely testing suspicious files or applications.
- Separating different workloads from one another.

If one virtual machine becomes compromised, the others usually remain unaffected.

---

## 2. Efficiency

Virtual machines make better use of hardware resources.

Advantages include:

- Running multiple operating systems on one computer.
- Quickly switching between different environments.
- Testing applications without needing additional hardware.
- Supporting cybersecurity labs and penetration testing.

This reduces hardware costs while improving flexibility.

---

# Hypervisors

A **hypervisor** is software that creates and manages virtual machines.

Its responsibilities include:

- Creating virtual machines.
- Allocating CPU, memory, storage, and networking resources.
- Managing communication between virtual and physical hardware.
- Ensuring each VM operates independently.

### Example Hypervisor

- **Kernel-based Virtual Machine (KVM)** – A popular Linux-based hypervisor that enables virtualization using the Linux kernel.

---

# Other Forms of Virtualization

Virtualization is not limited to virtual machines.

## Server Virtualization

A single physical server can be divided into multiple virtual servers.

Benefits include:

- Better hardware utilisation.
- Lower operating costs.
- Easier management.
- Improved scalability.

---

## Network Virtualization

Physical networking equipment can be divided into multiple virtual networks.

Benefits include:

- Improved network efficiency.
- Better isolation between environments.
- Simplified management.
- Increased flexibility for cloud and enterprise environments.

---

# Key Concepts

- A virtual machine is a software-based computer that simulates physical hardware.
- Multiple VMs can run simultaneously on one physical computer.
- Each VM has its own operating system and applications.
- Virtual machines provide secure, isolated environments for testing and analysis.
- A hypervisor manages virtual machines and allocates hardware resources.
- Virtualization also includes server virtualization and network virtualization.

---

# Key Takeaways

- Virtual machines allow multiple operating systems to run on a single physical computer.
- They improve security through isolation (sandboxing).
- They increase efficiency by making better use of hardware resources.
- Hypervisors, such as **Kernel-based Virtual Machine (KVM)**, create and manage virtual machines.
- Virtualization extends beyond VMs to include virtual servers and virtual networks.