##  What is an Operating System?
```
An Operating System (OS) is system software that acts as an interface between the user and computer hardware.
It manages CPU, memory, storage, devices, and allows applications to run.

Examples: Linux, Windows, macOS, Unix
```
## Types of Operating Systems
```
1 Batch Operating System:
Jobs are collected and executed in batches
No user interaction during execution
Example: Payroll systems

2 Time-Sharing Operating System:
Multiple users share CPU time
Fast response time
Example: Linux, Unix

3 Distributed Operating System:
Multiple systems work together as one
Improves reliability and performance
Example: Cluster systems

4 Network Operating System:
Manages network resources
Used in client-server environments
Example: Linux Server, Windows Server

5 Real-Time Operating System (RTOS):
Processes data within strict time limits
Used in embedded and critical systems
Example: RTLinux, VxWorks
```
## What is a Server?
```
A server is a computer or system that provides services, resources, or data to other computers (clients) over a network.
Examples of Server Types:
Web Server – Hosts websites
File Server – Stores and shares files
Database Server – Manages databases
Application Server – Runs backend applications
```
```
💡Most production servers use Linux due to its stability, security, and zero licensing cost.
```
## Linux vs Windows

## Differences:

| Feature | Linux | Windows |
|---------|-------|---------|
| **Cost** | Free & Open Source | Paid |
| **Source Code** | Open | Closed |
| **Security** | Very strong | More malware-prone |
| **Performance** | Lightweight	| Resource heavy |
| **Customization**	| High	| Limited |
| **Stability** | Very stable | Needs frequent reboot |
| **Usage** | Servers, Cloud, DevOps | Desktop, Gaming |

## Desktop OS vs Server OS

## Differences:

| Feature | Desktop OS | Server OS |
|---------|-----------|----------|
| **Purpose** | Personal use | Provide services |
| **Users**	| Single / Few | Multiple users |
| **GUI** | Mandatory | Optional |
| **Performance** | Moderate | High & optimized |
| **Use Case** | Daily computing, office work | Hosting, networking, cloud |
| **Examples** | Ubuntu Desktop, Windows 11	| RHEL, Ubuntu Server |

# Linux Architecture
## Linux Architecture Diagram
![image alt](https://github.com/Ashu-1808/Linux/blob/d4f7c6abf5170ce2fe19b88ec3a5ccce49fc5c3f/linux-architecture.jpg)

Text Diagram (for reference):

|   User Applications  |
|----------------------|
|       Shell          |
| System Libraries     |
|       Kernel         |
|      Hardware        |


## Linux Architecture Components
```
a. Hardware:
Physical components like CPU, RAM, disk, network devices

b. Kernel:
Core of Linux OS
Manages:Process scheduling, Memory management, Device drivers, File systems

c. System Libraries:
Provide functions used by applications
Help applications interact with the kernel

d. Shell:
Command-line interface
Acts as a bridge between user and kernel
Examples: bash, sh, zsh

e. User Applications:
Software used by users
Examples: browsers, editors, servers
```

## Popular Linux Distributions:
```
1.Ubuntu – Beginner-friendly, desktop & server
2.Red Hat Enterprise Linux (RHEL) – Enterprise use
3.CentOS / Rocky Linux – RHEL-based free distros
4.Debian – Stable and secure
5.Kali Linux – Cybersecurity & penetration testing
6.Amazon Linux – Optimized for AWS
```
## Linux Directory Structure
```
Linux follows a hierarchical directory structure, starting from the root directory (/).
Every file and directory in Linux exists under /.
```
| Directory | One-Line Explanation                                          |
| --------- | ------------------------------------------------------------- |
| `/`       | Root directory; starting point of the entire Linux filesystem |
| `/bin`    | Essential user command binaries like `ls`, `cp`, `mv`         |
| `/sbin`   | System administration commands mainly for root user           |
| `/etc`    | System-wide configuration files                               |
| `/home`   | Home directories for normal users                             |
| `/root`   | Home directory of the root (administrator) user               |
| `/lib`    | Shared libraries required by essential system binaries        |
| `/lib64`  | 64-bit shared libraries                                       |
| `/boot`   | Boot loader and kernel files needed to start the system       |
| `/dev`    | Device files representing hardware components                 |
| `/proc`   | Virtual filesystem with process and kernel information        |
| `/sys`    | Kernel and hardware information interface                     |
| `/tmp`    | Temporary files, usually cleared on reboot                    |
| `/usr`    | User applications, commands, and libraries                    |
| `/var`    | Variable data like logs, mail, and spool files                |
| `/mnt`    | Temporary mount point for filesystems                         |
| `/media`  | Mount point for removable devices (USB, CD/DVD)               |
| `/opt`    | Optional or third-party software installations                |
| `/srv`    | Data served by system services (FTP, HTTP, etc.)              |
