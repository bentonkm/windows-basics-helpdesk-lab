# Windows Basics — Help Desk Lab

## Project Goal

Build practical Windows troubleshooting skills for an entry-level IT Support / Help Desk role.

This project documents hands-on Windows tasks and basic troubleshooting techniques that an entry-level IT support technician may use when helping users.

## What I Practiced

* Windows system information
* User accounts and permissions
* Task Manager
* Windows Services
* Network troubleshooting
* Command Prompt troubleshooting
* Basic Windows troubleshooting
* Documenting IT support problems and solutions

## Tools Used

* Windows 11
* Windows built-in tools
* Command Prompt
* Task Manager
* System Information (`msinfo32`)
* PowerShell
* GitHub

---

# Labs

## Lab 1 — System Information

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

Task Manager helps IT support technicians identify applications and system resources that may be causing performance problems.

I also used the Windows System Information tool (`msinfo32`) to identify the computer's hardware and Windows configuration.

---

## Lab 2 — User Accounts & Permissions

### Findings

* Local user account: USER
* User group: Administrators
* The account has administrator privileges.

### What I Learned

Windows user accounts can have different permission levels. Administrator accounts have higher privileges and can perform system-level tasks.

Understanding user permissions is important when troubleshooting access problems and managing Windows computers.

---

## Lab 3 — Task Manager

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

I opened Windows Task Manager using `Ctrl + Shift + Esc` and reviewed the Processes tab to see how applications were using system resources.

### What I Learned

Task Manager can help an IT support technician identify applications using a large amount of CPU or memory when troubleshooting slow computer performance.

---

## Lab 4 — Windows Services

### Windows Update Service

* Status: Stopped
* Startup Type: Manual (Triggered)
* Log On As: Local System

### What I Learned

The Windows Update service helps detect, download, and install Windows and other program updates.

I learned that Windows services can have different states and startup types. IT support technicians can check services when troubleshooting Windows problems.

---

## Lab 5 — Network Troubleshooting

### Tests Performed

* `ipconfig` — checked network configuration.
* `ping google.com` — successful.
* `ipconfig /flushdns` — DNS cache successfully flushed.
* `nslookup google.com` — successfully resolved google.com to IP addresses.

### What I Learned

I practiced basic Windows network troubleshooting using Command Prompt.

These commands can help an IT support technician identify connectivity and DNS problems.

---

## Lab 6 — Troubleshooting Scenario

### Problem

A user reported that their computer was connected to Wi-Fi but websites were not loading.

### Troubleshooting Steps

1. Pinged the router — 4 packets sent, 4 received.
2. Pinged `google.com` — 4 packets sent, 4 received.
3. Used `nslookup google.com` — successfully resolved the domain.

### Conclusion

The computer was able to reach the local router, reach Google, and successfully resolve the domain name.

The basic network connection and DNS resolution were working correctly.

### What I Learned

I learned how to troubleshoot network connectivity step by step by checking the local network, Internet connectivity, and DNS resolution separately.

---

# Evidence

Screenshots from each lab are organized in the `evidence` folder.

* [Lab 1 Evidence](evidence/Lab%201/)
* [Lab 2 Evidence](evidence/Lab%202/)
* [Lab 3 Evidence](evidence/Lab%203/)
* [Lab 4 Evidence](evidence/Lab%204/)
* [Lab 5 Evidence](evidence/Lab%205/)
* [Lab 6 Evidence](evidence/Lab%206/)

---

# Skills Demonstrated

This project demonstrates beginner-level practical skills in:

* Windows system information gathering
* Hardware and software identification
* Task Manager usage
* User accounts and permissions
* Windows Services
* Command Prompt
* Basic network troubleshooting
* DNS troubleshooting
* Basic IT support documentation
* Troubleshooting methodology

---

# Final Summary

This project gave me hands-on practice with common Windows tools and basic IT support troubleshooting techniques.

I learned how to gather system information, review system performance, understand user permissions, inspect Windows services, and troubleshoot basic network and DNS problems.

The project also helped me practice documenting technical problems, troubleshooting steps, findings, and conclusions in a clear format.

## Project Status

**Completed — Labs 1–6**
