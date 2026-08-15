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

