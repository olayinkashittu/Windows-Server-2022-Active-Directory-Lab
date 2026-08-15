# Active Directory Installation

## Objective

Install Active Directory Domain Services.

## Tasks Completed

- Installed AD DS
- Promoted the server to a domain controller
- Created the lab.local domain

## PowerShell Verification

```bash
Get-WindowsFeature AD-Domain-Services
```

Expected result:

```bash
Installed : True
```
# Active Directory

## Domain

- Domain: lab.local
- Domain Controller: DC01

## Active Directory Services

- Active Directory Domain Services
- DNS
- Domain Controller

## Verification

```bash
Get-ADDomain
```

```bash
Get-ADForest
dcdiag
```bash

# Active Directory

## Objective

Install and configure Active Directory Domain Services on Windows Server 2022.

## Configuration

- Server: DC01
- Domain: lab.local
- Role: Domain Controller
- Active Directory Domain Services: Installed
- DNS: Configured

## Verification

Active Directory Domain Services was successfully installed and the server was promoted to a Domain Controller.

## PowerShell

```bash
Get-ADDomain
```

```bash
Get-ADForest
```

Result
The Windows Server 2022 system is operating as the Domain Controller for the lab.local domain.

