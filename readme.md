# PowerShell Basic
> Basics on PowerShell

## Basics
- You can download the latest powershell from the github Repo
- On powershell commands can be small case or upper case it doesn't matter
- You can also type `$` and then press tab commands will appear on your terminal
- Windows PowerShell ISE is the default interpreter for windows powershell

## PowerShell ISE
- To run the powershell ISE on start menu Type PowerShell ISE
- To run only selected script press F8 
- To run entire code press F5
```ps1
# To Get the services 
Get-Service

# To Get Specific Service
Get-Service -Name Service_Name
```
- Get help & examples
```
Get-Help Get-Service -Examples
```

## Commands 
```
# Check Version 
$psversiontable
$PSVersionTable

```