# Users and Groups

## Objective

Create and manage Active Directory users and groups.

## Tasks Completed

- Created the IT-Admins security group
- Created the jdoe user account
- Created the jsmith user account
- Added jsmith to the IT-Admins group

## Create a User

```bash
New-ADUser -Name "John Doe"
```

## Create a Security Group

```bash
New-ADGroup -Name "IT-Admins"
```

## Add a User to a Group

```bash
Add-ADGroupMember -Identity IT-Admins -Members jsmith
```
