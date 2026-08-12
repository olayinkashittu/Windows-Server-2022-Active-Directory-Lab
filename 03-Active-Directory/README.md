# Active Directory

## Domain

- Domain: lab.local
- Domain Controller: DC01

## Active Directory Services

- Active Directory Domain Services
- DNS
- Domain Controller

## Verification

```powershell
Get-ADDomain
Get-ADForest
dcdiag

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

```powershell
Get-ADDomain

Get-ADForest

Result
The Windows Server 2022 system is operating as the Domain Controller for the lab.local domain.

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

## PowerShell Commands

```powershell
Get-ADDomain
