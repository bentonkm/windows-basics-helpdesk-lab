# Windows Basics — Help Desk Lab

## Project Goal

This project was created to build practical Windows troubleshooting skills for an entry-level IT Support / Help Desk role.

The project focuses on using built-in Windows tools to gather system information, investigate performance issues, understand user permissions, check Windows services, troubleshoot network connectivity, and document technical problems.

---

## What I Practiced

* Windows system information
* Hardware and software identification
* User accounts and permissions
* Task Manager
* Windows Services
* Command Prompt
* Network troubleshooting
* DNS troubleshooting
* Basic Windows troubleshooting
* IT support documentation
* Troubleshooting step by step

---

## Tools Used

* Windows 11
* Windows built-in troubleshooting tools
* System Information (`msinfo32`)
* Task Manager
* Command Prompt
* PowerShell
* GitHub

---

# Labs

## Lab 1 — System Information

### Objective

The objective of this lab was to gather information about the computer's hardware, operating system, and configuration.

### System Information

* Operating System: Windows 11 Pro
* Version: 10.0.26200
* Manufacturer: HP
* Model: HP EliteBook 840 G6
* System Type: x64-based PC
* Processor: Intel Core i7-8665U
* CPU Cores: 4
* Logical Processors: 8
* BIOS Mode: UEFI
* Secure Boot: On
* Installed RAM: 16 GB
* Graphics: Intel UHD Graphics 620
* Storage: 477 GB
* Windows Version: 25H2
* OS Build: 26200.9457
* Wi-Fi Adapter: Intel Wi-Fi 6 AX200
* Connection Type: 802.11n

### Task Manager

I opened Task Manager using `Ctrl + Shift + Esc` and reviewed the Processes and Performance tabs.

* CPU usage observed: 7–13%
* Memory usage observed: about 50%
* Disk usage observed: about 2–4%
* RAM: 16 GB DDR4
* CPU cores: 4
* Logical processors: 8
* Storage: 477 GB NVMe SSD
* Wi-Fi adapter: Intel Wi-Fi 6 AX200

### What I Learned

I learned how to use Windows System Information and Task Manager to quickly identify a computer's hardware and current system resource usage.

These tools are useful for IT support technicians when documenting a computer or investigating performance-related problems.

---

## Lab 2 — User Accounts & Permissions

### Objective

The objective of this lab was to identify the local Windows user account and understand its permission level.

### Findings

* Local user account: USER
* User group: Administrators
* Account privilege level: Administrator

### What I Learned

Windows user accounts can have different permission levels.

Administrator accounts have higher privileges and can perform system-level tasks. Understanding user permissions is important when troubleshooting access problems and managing Windows computers.

---

## Lab 3 — Task Manager

### Objective

The objective of this lab was to use Task Manager to examine how applications and background processes were using system resources.

### Findings

* CPU Usage: 5%
* Memory Usage: 53%
* Disk Usage: 3%
* Network Usage: 0%
* Firefox: 676.9 MB memory
* Brave Browser: 624.4 MB memory
* Google Chrome: 455.3 MB memory
* ChatGPT: 425.2 MB memory
* Background Processes: 93

### What I Did

I opened Windows Task Manager using `Ctrl + Shift + Esc` and reviewed the Processes tab.

I examined running applications and their CPU, memory, disk, and network usage.

### What I Learned

Task Manager can help an IT support technician identify applications that are using a large amount of CPU or memory.

This can be useful when investigating complaints such as:

* "My computer is slow."
* "An application is frozen."
* "My computer is using too much memory."
* "Something is making my computer run slowly."

---

## Lab 4 — Windows Services

### Objective

The objective of this lab was to inspect a Windows service and understand its status, startup type, and account.

### Windows Update Service

* Service: Windows Update
* Status: Stopped
* Startup Type: Manual (Triggered)
* Log On As: Local System

### What I Learned

Windows services run in the background and provide important operating system functions.

The Windows Update service helps Windows detect, download, and install updates.

I also learned that services can have different states and startup types. Checking services can be useful when troubleshooting Windows features that are not working correctly.

---

## Lab 5 — Network Troubleshooting

### Objective

The objective of this lab was to practice basic network troubleshooting using Windows Command Prompt.

### Tests Performed

#### `ipconfig`

Used to check the computer's network configuration.

#### `ping google.com`

Used to test connectivity to Google.

Result:

**Successful**

#### `ipconfig /flushdns`

Used to clear the computer's DNS cache.

Result:

**DNS cache successfully flushed.**

#### `nslookup google.com`

Used to test DNS resolution.

Result:

**Successfully resolved google.com to IP addresses.**

### What I Learned

I learned how to use basic Windows networking commands to investigate connectivity and DNS problems.

These commands provide a simple troubleshooting process for determining whether a problem is related to network configuration, Internet connectivity, or DNS resolution.

---

## Lab 6 — Network Troubleshooting Scenario

### Problem

A user reported that their computer was connected to Wi-Fi but websites were not loading.

### Troubleshooting Steps

#### Step 1 — Test the Local Network

I pinged the local router.

Result:

**4 packets sent, 4 packets received.**

This showed that the computer could communicate with the local network gateway.

#### Step 2 — Test Internet Connectivity

I pinged `google.com`.

Result:

**4 packets sent, 4 packets received.**

This showed that the computer could reach Google successfully.

#### Step 3 — Test DNS Resolution

I used:

`nslookup google.com`

Result:

**The domain was successfully resolved to IP addresses.**

### Conclusion

The computer was able to reach the local router, reach Google, and successfully resolve the domain name.

The basic network connection and DNS resolution were working correctly.

### What I Learned

I learned how to troubleshoot network connectivity step by step instead of assuming the problem was caused by one specific component.

The troubleshooting process involved checking:

1. Local network connectivity
2. Internet connectivity
3. DNS resolution

This helped me understand how different network troubleshooting commands can be used to narrow down a problem.

---

# Evidence

Screenshots from the labs are stored in the `evidence` folder.

The evidence files are PNG screenshots documenting the practical work completed during the project.

### Lab 1 Evidence

* `LAB 1 .png`
* `LAB1.2.png`
* `LAB1.3.png`
* `LAB 1.4.png`
* `LAB 1.5 .png`
* `LAB 1.6.png`

### Lab 3 Evidence

* `LAB 3.png`
* `LAB 3.1 ..png`
* `LAB 3.2 .png`
* `LAB 3.3..png`

### Lab 4 Evidence

* `LAB 4.png`

### Lab 5 Evidence

* `LAB 5.png`

### Lab 6 Evidence

* `LAB 6.png`

> Note: The screenshot filenames were kept as originally created during the labs. Some filenames contain spaces or additional periods, but all files are valid PNG image files.

---

# Skills Demonstrated

This project demonstrates beginner-level practical skills in:

* Windows system information gathering
* Hardware and software identification
* Task Manager
* User accounts and permissions
* Windows Services
* Command Prompt
* Network troubleshooting
* DNS troubleshooting
* Basic Windows administration
* Troubleshooting methodology
* Technical documentation
* Recording troubleshooting findings

---

# Troubleshooting Approach

One of the main skills practiced throughout this project was troubleshooting problems step by step.

Instead of immediately changing settings or guessing the cause of a problem, I practiced:

1. Identifying the problem
2. Gathering information
3. Running appropriate tests
4. Recording the results
5. Identifying what was working
6. Narrowing down the possible cause
7. Documenting the conclusion

This approach can be applied to many basic IT support situations.

---

# Final Summary

This project gave me hands-on experience with common Windows tools and basic IT support troubleshooting techniques.

I practiced gathering system information, reviewing system performance, understanding user permissions, inspecting Windows services, and troubleshooting network and DNS connectivity.

The project also helped me develop the habit of documenting:

* The reported problem
* Troubleshooting steps
* Test results
* Findings
* Conclusion
* Supporting evidence

These are foundational skills for an entry-level IT Support / Help Desk role.

---

## Project Status

**Completed — Labs 1–6**

**Project Type:** Beginner IT Support / Help Desk Portfolio Project
