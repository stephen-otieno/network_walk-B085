<div align="center">

# 🔐 Cybersecurity Lab Environment Setup

**Building an isolated virtual laboratory for cybersecurity learning, penetration testing, and ethical hacking practice**

</div>

<p align="center">
<img src="https://img.shields.io/badge/Skill-Cybersecurity-C00000?style=flat-square"/>
<img src="https://img.shields.io/badge/VirtualBox-v7.2-0070C0?style=flat-square"/>
<img src="https://img.shields.io/badge/Kali%20Linux-v2026.1-E87500?style=flat-square"/>
<img src="https://img.shields.io/badge/Host-Ubuntu-404040?style=flat-square"/>
<img src="https://img.shields.io/badge/Network-NAT%20Network-238F89?style=flat-square"/>
<img src="https://img.shields.io/badge/GitHub-Repository-000000?style=flat-square"/>
<img src="https://img.shields.io/badge/Ethical%20Hacking-C00000?style=flat-square"/>
</p>


---

# 📌 Project Overview

This project focuses on creating a controlled cybersecurity laboratory environment using **VirtualBox** and **Kali Linux**.

The purpose of this laboratory is to provide a safe environment where cybersecurity concepts such as:

- Network reconnaissance
- Vulnerability assessment
- Packet analysis
- Penetration testing
- Security tool experimentation

can be practiced without affecting production systems.

The laboratory uses a private **NAT Network** configuration that allows virtual machines to communicate with each other while maintaining controlled external connectivity.

---

# 🎯 Objectives

The objectives of this laboratory setup are:

- Install and configure VirtualBox.
- Import Kali Linux as a virtual machine.
- Configure a dedicated NAT Network.
- Configure Kali Linux networking.
- Verify connectivity between virtual machines.
- Configure shared folders.
- Install required cybersecurity tools.
- Create a clean snapshot for recovery.
- Document the complete setup process.

---

# 🛡️ Purpose of the Lab

This laboratory provides an isolated environment for cybersecurity education.

The environment can be used for:

- Network scanning
- Vulnerability testing
- Linux security practice
- Packet capture and analysis
- Web security testing
- Ethical hacking exercises


⚠️ **Important:**  
All activities performed in this laboratory must only target systems owned by the user or systems where permission has been granted.

---

# 🏗️ Lab Architecture


![Cybersecurity Lab Architecture](screenshots/1-virtualbox-kali.png)


Future cybersecurity projects can introduce additional virtual machines such as:

- Vulnerable web servers
- Windows target machines
- Security monitoring systems
- Intentionally vulnerable applications

---

# ⚙️ Lab Configuration


| Component | Configuration |
|-----------|--------------|
| Host Operating System | Ubuntu |
| Host RAM | 16 GB |
| Processor | Intel Core i5 |
| Hypervisor | VirtualBox 7.2 |
| Security Operating System | Kali Linux 2026.1 |
| Kali Installation Method | Pre-built VirtualBox Image |
| Kali Username | kali |
| Kali RAM Allocation | 6.7 GB |
| Kali CPU Allocation | 2 CPUs |
| Network Type | NAT Network |
| Network Range | 10.0.0.0/24 |
| Kali IP Address | 10.0.2.15 |
| Shared Folder | /media/sf_VM_Shared |

---

# 🪜 Lab Setup Procedure


## Step 1: Install VirtualBox

VirtualBox 7.2 was installed on the Ubuntu host machine.

VirtualBox provides the virtualization platform required to run Kali Linux.

---

## Step 2: Import Kali Linux Virtual Machine

A pre-built Kali Linux VirtualBox image was downloaded and imported.

The VM was configured with:

```text
Operating System:
Kali Linux 2026.1

RAM:
6.7 GB

Processors:
2 CPUs
