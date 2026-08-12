# Users and Groups

## Security Group

- Group: IT-Admins
- Type: Security Group
- Scope: Global

## User

- Username: jdoe
- Display Name: John Doe
- Domain: lab.local

## Verification

```powershell
Get-ADUser jdoe
Get-ADGroup "IT-Admins"

# Users and Groups

## Objective

Create and manage Active Directory users and security groups.

## User Created

- Full Name: John Doe
- Username: jdoe
- UPN: jdoe@lab.local
- OU: IT

## Group

- Group: IT-Admins
- Group Type: Security
- Group Scope: Global

## PowerShell

```powershell
New-ADUser

New-ADGroup

Get-ADUser jdoe

Verification
The user account jdoe was successfully created and verified in Active Directory.
