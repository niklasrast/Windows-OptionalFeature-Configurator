# SCRIPT NAME

This repo contains powershell scripts to configure optional windows 10 features on your client.

## Install Defender Application Guard:
```powershell
PowerShell.exe -ExecutionPolicy Bypass -Command .\Defender Application Guard 1.0.0\INSTALL-DefenderApplicationGuard.ps1 -install
```

## Install Hyper-V:
```powershell
PowerShell.exe -ExecutionPolicy Bypass -Command .\Hyper-V 1.0.0\INSTALL-HYPERV.ps1 -install
```

## Install RSAT:
```powershell
PowerShell.exe -ExecutionPolicy Bypass -Command .\RSAT 1.0.0\INSTALL-RSAT-Online.ps1 -install
```

## Install Subsystem for Linux:
```powershell
PowerShell.exe -ExecutionPolicy Bypass -Command .\Subsystem for Linux 1.0.0\INSTALL-SubsystemForLinux.ps1 -install
```

## Install Windows Sandbox:
```powershell
PowerShell.exe -ExecutionPolicy Bypass -Command .\Windows Sandbox 1.0.0\INSTALL-WindowsSandbox.ps1 -install
```

### Parameter definitions:
- -install configures the optional windows feature 
- -uninstall removes the optional windows feature
 
## Logfiles:
The scripts create a logfile with the name of the .ps1 script in the folder C:\Windows\Logs.

## Requirements:
- PowerShell 5.0
- Windows 10

Created by @niklasrast 