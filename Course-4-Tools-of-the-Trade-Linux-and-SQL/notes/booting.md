# How Operating Systems Work

This section explains how an operating system (OS) works, including the **boot process** and how it acts as a bridge between applications and computer hardware.

---

# Booting the Computer

When a computer is powered on, it follows a sequence of steps to load the operating system.

## Boot Process

1. The computer is powered on.
2. A special firmware chip (**BIOS** or **UEFI**) starts running.
3. The firmware performs hardware checks and loads the **bootloader**.
4. The bootloader starts the operating system.
5. The operating system becomes ready for user interaction.

### Key Components

- **BIOS (Basic Input/Output System):** Traditional firmware that initializes hardware during startup.
- **UEFI (Unified Extensible Firmware Interface):** Modern replacement for BIOS with improved features and security.
- **Bootloader:** A program responsible for loading the operating system into memory.

---

# User Interaction with the Operating System

Users do not communicate directly with computer hardware.

Instead, the communication follows this path:

```text
User
   ↓
Application
   ↓
Operating System
   ↓
Hardware (CPU, Memory, Storage, etc.)
   ↑
Operating System
   ↑
Application
   ↑
User
```

### Process

1. The user interacts with an application.
2. The application sends a request to the operating system.
3. The operating system interprets the request.
4. The OS sends the request to the appropriate hardware component.
5. The hardware processes the request.
6. The result is returned through the OS to the application.
7. The application displays the result to the user.

---

# Example: Using a Calculator

Suppose a user wants to calculate **25 + 17**.

### Step-by-Step Process

1. The user opens the calculator application.
2. The user enters **25 + 17**.
3. The calculator application sends the request to the operating system.
4. The operating system forwards the calculation to the **Central Processing Unit (CPU)**.
5. The CPU performs the calculation.
6. The CPU returns the result (**42**) to the operating system.
7. The operating system sends the result back to the calculator application.
8. The calculator displays the answer to the user.

---

# Key Concepts

- The operating system acts as a bridge between applications and hardware.
- BIOS or UEFI initializes the computer during startup.
- The bootloader loads the operating system into memory.
- Applications rely on the operating system to communicate with hardware.
- The CPU performs processing tasks requested by applications through the operating system.

---

# Key Takeaways

- The boot process starts when the computer is powered on.
- BIOS or UEFI loads the bootloader.
- The bootloader loads the operating system.
- Users interact with applications, not directly with hardware.
- The operating system manages communication between applications and hardware.
- Hardware processes requests and returns results through the operating system.