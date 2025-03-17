# 🏡 Home Lab Environment – Active Directory + SysAdmin + Security

## 🧠 Overview
This repository documents the setup and progression of my personal home lab environment, designed to simulate a real-world enterprise network. The goal is to develop core **System Administration skills** while building a foundation for **Cybersecurity and Blue Teaming**.

This lab integrates Windows Server, Active Directory, Linux systems, and a SIEM tool (Splunk), providing a versatile environment for hands-on learning.

## 🖥️ Virtual Machines in the Lab
| VM Name         | Purpose                                  |
|----------------|-------------------------------------------|
| **Windows Server 2022** | Domain Controller, AD DS, DNS, DHCP, GPO |
| **Windows 10**         | Client machine (joined to domain)   |
| **Ubuntu Server**      | Hosting Splunk (SIEM logging tool) |
| **Kali Linux**         | Testing / Penetration Testing Environment |

## 🔧 Tools & Platforms Used
- **VirtualBox** (Virtualization)
- **Windows Server 2022 Evaluation ISO**
- **Windows 10 ISO**
- **Ubuntu Server ISO**
- **Kali Linux ISO**
- **Splunk Free Edition**
- **PowerShell, Bash, GPO, Event Viewer**

## ✅ Current Features Implemented
- Active Directory Domain Setup on Server 2022
- Client join to domain (Windows 10)
- User and OU creation
- GPO configurations (basic)
- Password and account management tasks
- Splunk installation (in progress) on Ubuntu Server
- Lab designed for future use with Sysmon, Event Log forwarding, and threat monitoring

## 📈 Future Plans
- Build PowerShell automation scripts for admin tasks
- Configure log forwarding from Windows machines to Splunk
- Implement advanced GPOs (e.g., hardening policies)
- Simulate security incidents for blue team practice
- Monitor logs via Splunk dashboards

## 📁 Repository Structure (Recommended)
