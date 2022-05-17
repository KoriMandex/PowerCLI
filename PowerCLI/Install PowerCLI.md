# Kori Hanes
# 13MAY2022

https://adamtheautomator.com/powercli-tutorial/

# My PowerShellGet module in powershell was updated and the new version was installed incorrectly to my OneDrive path, essentially breaking PowerShellGet, making it impossible to install any new modules. See link below. I deleted the old PowerShellGet module and relocated updated module to correct path.

https://stackoverflow.com/questions/65482945/corrupt-packagemanager-unable-to-find-module-providers-powershellget

# When installing PowerCLI: If using the download method, be sure to install all modules in the C:\Program Files\WindowsPowerShell\Modules directory. Do NOT create a seperate directory for PowerCLI.


# Test modules are installed.

Get-Module -ListAvailable VMware*

# Output:

PS C:\Users\hanes.kori\OneDrive - Mandex, Inc\Documents\Projects\PowerCLI> Get-Module -ListAvailable VMware*


    Directory: C:\Program Files\WindowsPowerShell\Modules


ModuleType Version    Name                                ExportedCommands
---------- -------    ----                                ----------------
Manifest   12.6.0.... VMware.PowerCLI
Script     12.6.0.... VMware.PowerCLI.Sdk
Script     12.6.0.... VMware.PowerCLI.Sdk.Types
Script     12.6.0.... VMware.PowerCLI.VCenter             {Get-VIMachineCertificate, Get-VITrustedCertificate, Remove-VITrustedCer... 
Script     12.6.0.... VMware.PowerCLI.VCenter.Types.Ap...
Script     12.6.0.... VMware.PowerCLI.VCenter.Types.Ce...
