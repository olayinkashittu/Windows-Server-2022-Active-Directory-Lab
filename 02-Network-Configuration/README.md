# Network Configuration

## Network Settings

| Setting | Value |
|---|---|
| Server | DC01 |
| IPv4 Address | 10.0.2.15 |
| Prefix Length | 24 |
| Default Gateway | 10.0.2.2 |

## Verification

The network configuration was verified using PowerShell.

```powershell
Get-NetIPConfiguration

# Network Configuration

## Objective

Configure and verify the network settings for the Windows Server 2022 Domain Controller.

## Server

- Server Name: DC01
- Operating System: Windows Server 2022
- Virtualization: Oracle VirtualBox
- Network Adapter: Intel PRO/1000 MT Desktop Adapter

## Network Configuration

- IPv4 Address: 10.0.2.15
- Prefix Length: 24
- Default Gateway: 10.0.2.2
- DNS Server: 10.0.2.3
- Domain: lab.local

## PowerShell Commands

```powershell
Get-NetIPConfiguration

Test-NetConnection 10.0.2.2

Verification
Network connectivity was tested using PowerShell before proceeding with Active Directory configuration.
