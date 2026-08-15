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

```bash
Get-ADUser jdoe
Get-ADGroup "IT-Admins"
```

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

```bash
New-ADUser
```

```bash
New-ADGroup
```

```bash
Get-ADUser jdoe
```

Verification
The user account jdoe was successfully created and verified in Active Directory.

# Organizational Units

## Objective

Create an Organizational Unit for user administration.

## Tasks Completed

- Created an Organizational Unit named IT

## PowerShell Command

```bash
New-ADOrganizationalUnit -Name "IT"
```

## Verification

```bash
Get-ADOrganizationalUnit -Filter *
```
## Organizational Units

## IT Organizational Unit

An Organizational Unit named `IT` was created within the `lab.local` domain.

## PowerShell

```bash
New-ADOrganizationalUnit -Name "IT" -Path "DC=lab,DC=local"
```

## Organizational Units

## Objective

Create and organize Active Directory objects using Organizational Units.

## OU Created

- OU Name: IT
- Domain: lab.local

## PowerShell

### Verification
The IT Organizational Unit was successfully created within the lab.local domain.
