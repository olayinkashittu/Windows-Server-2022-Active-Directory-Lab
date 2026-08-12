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
