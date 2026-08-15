# Windows Server 2022 Active Directory Domain Controller Lab

![Windows Server](https://img.shields.io/badge/Windows%20Server-2022-blue)
![Active Directory](https://img.shields.io/badge/Active%20Directory-AD%20DS-green)
![PowerShell](https://img.shields.io/badge/PowerShell-Administration-blue)
![VirtualBox](https://img.shields.io/badge/VirtualBox-Virtualization-orange)

## Project Overview

This project demonstrates the deployment and administration of a Windows Server 2022 Active Directory environment using Oracle VirtualBox.

The lab was designed to simulate a small enterprise IT infrastructure and provide practical experience in:

- Windows Server administration
- Active Directory
- DNS configuration
- User and group management
- PowerShell administration
- IT infrastructure management

## Lab Environment

| Component | Configuration |
| --- | --- |
| Server | DC01 |
| Operating System | Windows Server 2022 |
| Domain | lab.local |
| Server Role | Domain Controller |
| Virtualization | Oracle VirtualBox |
| IPv4 Address | 10.0.2.15 |
| Active Directory | AD DS |
| DNS | Windows DNS |
| Administrative Tool | PowerShell |

## Lab Architecture

```bash
            Internet
                |
            VirtualBox
                |
              DC01
      Windows Server 2022
                |
            10.0.2.15
                |
            lab.local
                |
      +---------+---------+
      |                   |
      IT             IT-Admins
      |
    jdoe
```

## Project Tasks

- Server deployment
- Network configuration
- Active Directory installation
- Organizational Unit creation
- User account management
- Security group configuration
- PowerShell administration
- Testing and verification

## Technologies

- Windows Server 2022
- Active Directory
- DNS
- PowerShell
- Oracle VirtualBox
