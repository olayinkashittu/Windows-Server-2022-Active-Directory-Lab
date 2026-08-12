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
