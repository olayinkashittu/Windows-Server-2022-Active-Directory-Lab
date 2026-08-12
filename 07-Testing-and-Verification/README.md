# Testing and Verification

## Tests Performed

- Network configuration verification
- Active Directory domain verification
- Domain Controller verification
- DNS verification
- User account verification
- Active Directory health checks

## Commands

```powershell
Get-NetIPConfiguration

Get-ADDomain

Get-ADDomainController

Get-ADUser jdoe

dcdiag

# Testing and Verification

## Objective

Verify that the Active Directory environment is functioning correctly.

## Tests

### Domain Verification

```powershell
Get-ADDomain

Forest Verification

Get-ADForest

User Verification

Get-ADUser jdoe

Network Verification

Test-NetConnection 10.0.2.2

Active Directory Diagnostics

dcdiag

Result
The Active Directory domain controller and domain configuration were successfully verified.
