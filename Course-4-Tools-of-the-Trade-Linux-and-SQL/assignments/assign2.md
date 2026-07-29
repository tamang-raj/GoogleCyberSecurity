# Operating Systems Quiz Answers (Part 2)

## Question 1

**What is the job of a computer's operating system?**

- ✅ **Help other computer programs run efficiently**
- ❌ Turn on the computer
- ❌ Load the bootloader
- ❌ Allow users to specify tasks

**Explanation:**  
The primary job of an operating system is to manage computer hardware and system resources so that applications run efficiently.

---

## Question 2

**Fill in the blank: In order to carry out tasks on a computer, users directly interact with _____.**

- ❌ the CPU
- ❌ the BIOS
- ❌ task managers
- ✅ **applications**

**Explanation:**  
Users perform tasks by interacting with **applications**. The applications communicate with the operating system, which then manages the hardware needed to complete the task.

---

## Question 3

**The management of a computer's resources and memory is handled by an application.**

- ❌ True
- ✅ **False**

**Explanation:**  
Resource and memory management are responsibilities of the **operating system**, not individual applications. The OS allocates CPU time, memory, storage, and other resources where they are needed.

---

## Question 4

**Which of the following processes are part of starting an operating system?** *(Select all that apply.)*

- ✅ The bootloader starts the operating system.
- ✅ The BIOS or UEFI microchip loads the bootloader.
- ✅ Either the BIOS or UEFI microchip is activated when a user turns on a computer.
- ❌ The bootloader immediately launches when a user turns on a computer.

**Explanation:**  
The correct startup sequence is:

1. The computer is powered on.
2. **BIOS or UEFI** is activated.
3. BIOS/UEFI performs hardware checks.
4. BIOS/UEFI loads the **bootloader**.
5. The **bootloader** starts the operating system.

The bootloader does **not** launch immediately when the computer is turned on—it must first be loaded by the BIOS or UEFI.

---

# Boot Process Summary

```text
Power On
    ↓
BIOS / UEFI Starts
    ↓
Hardware Checks
    ↓
Bootloader Loaded
    ↓
Operating System Starts
```

---

# Answer Key

| Question | Correct Answer(s) |
|----------|--------------------|
| 1 | Help other computer programs run efficiently |
| 2 | Applications |
| 3 | False |
| 4 | The bootloader starts the operating system; The BIOS or UEFI microchip loads the bootloader; Either the BIOS or UEFI microchip is activated when a user turns on a computer |