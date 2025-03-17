🖥️ Active Directory Lab – Fundamentals (Server Academy)

📚 Overview

This lab was completed as part of the Active Directory Fundamentals course by Server Academy. It was designed to provide hands-on experience with key Active Directory tasks and user management in a Windows Server environment.

🔧 Tools Used

VirtualBox (Virtualization Platform)

Windows Server 2019 Evaluation ISO

Windows 10 ISO (Client VM)

Server Academy Lab Materials

🏗️ Lab Setup

DC01 – Windows Server 2019 Domain Controller with Active Directory Domain Services (AD DS), DNS, and DHCP

CLIENT01 – Windows 10 machine joined to the domain

✅ Tasks Performed

Created new Active Directory users

2 users under the Domain Users OU

1 user under the Domain Admins OU

Reset user passwords

Unlocked locked user accounts

Created and deleted Organizational Units (OUs)

Created a Disabled Users OU

Deleted two pre-existing OUs

Disabled a terminated user's account and moved them to the Disabled Users OU

📝 Lessons Learned

User account creation and organizational placement in Active Directory

Password management and account recovery procedures

Organizational Unit (OU) management for user segregation

How to disable and organize terminated user accounts following standard IT practices

💡 Next Steps / Improvements

Create Group Policies (GPOs) for user restrictions and settings

Automate user creation and password resets using PowerShell

Practice more complex OU structures and AD delegation

Set up a file server and apply NTFS permissions

🏡 Expanded Home Lab Environment

To further build out this environment and strengthen both system administration and security foundations, additional virtual machines have been added:

🖥️ Virtual Machines in the Lab

VM Name

Purpose

Windows Server 2022

Domain Controller, AD DS, DNS, DHCP, GPO

Windows 10

Client machine (joined to domain)

Ubuntu Server

Hosting Splunk (SIEM logging tool)

Kali Linux

Testing / Penetration Testing Environment

🔧 Additional Tools & Platforms

Windows Server 2022 ISO

Ubuntu Server ISO

Kali Linux ISO

Splunk Free Edition

PowerShell, Bash, GPO, Event Viewer

✅ Additional Features Implemented / In Progress

Active Directory Domain Setup on Server 2022

Client domain join (Windows 10)

GPO configurations

User and OU management

Splunk installation on Ubuntu Server (in progress)

📈 Future Plans

Log forwarding from Windows to Splunk

PowerShell scripting for automation

Advanced GPO configurations

Simulated security incident response via logs and monitoring

📁 Project Source

The initial portion of this project was based on practical labs from Server Academy. Subsequent configurations and experiments are self-directed, following various community guides, documentation, and hands-on exploration for continuous learning and skill development.
