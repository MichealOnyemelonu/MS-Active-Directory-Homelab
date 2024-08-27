# Home Lab Setup Scripts

These two scripts allow for an easy and automated way to set up a home lab quickly!

## DC_Script_Setup.ps1

### Description:

- Configures a Windows domain controller via PowerShell script.
- Updates the IP address and Hostname, creates a Scheduled Task, and Restarts the OS.
- Installs Active Directory and DNS, creates a Scheduled Task, and Restarts the OS.
- Installs DHCP and Restarts the OS.

### How-to Run:

1. Place `DC_Script_Setup.ps1` on the root of the `C:\` drive.
2. Open `PowerShell.exe` or `Cmd.exe` and run this code: > powershell.exe -ExecutionPolicy Bypass .\DC_Script_Setup.ps1 -one


*Tested on Windows Server 2016*

## Client_Script_Setup.ps1

### Description:

- Configures a Windows domain controller via PowerShell script.
- Configures IP address and Hostname, Joins host to the domain, and Restarts the OS.

### How-to Run:

1. Open `PowerShell.exe` or `Cmd.exe` and run this code:> powershell.exe -ExecutionPolicy Bypass .\Client_Setup_Script.exe


*Tested on Windows 10 Enterprise*
