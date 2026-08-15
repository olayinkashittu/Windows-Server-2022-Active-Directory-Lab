# Network Configuration

## Objective

Configure networking for the domain controller.

## Tasks Completed

- Configured a static IPv4 address
- Assigned the IP address 10.0.2.15
- Verified network connectivity

## Verification

### PowerShell command:

```bash
ipconfig
```

Expected result:

```bash
IPv4 Address: 10.0.2.15
```
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

```bash
Get-NetIPConfiguration
```

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

```bash
Get-NetIPConfiguration
```
Test-NetConnection 10.0.2.2

### Verification
Network connectivity was tested using PowerShell before proceeding with Active Directory configuration.

# Network Configuration

## Objective

Configure and verify the network settings for the Windows Server 2022 Domain Controller.

## Server Configuration

- Server Name: DC01
- Operating System: Windows Server 2022
- Virtualization: Oracle VirtualBox
- Network Adapter: Intel PRO/1000 MT Desktop Adapter

## Network Settings

- IPv4 Address: 10.0.2.15
- Prefix Length: 24
- Default Gateway: 10.0.2.2
- DNS Server: 10.0.2.3
- Domain: lab.local
