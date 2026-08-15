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

Verification
The IT Organizational Unit was successfully created within the lab.local domain.
Verification
The IT Organizational Unit was successfully created within the lab.local domain.


```bash
New-ADOrganizationalUnit -Name "IT" -Path "DC=lab,DC=local"
```bash

