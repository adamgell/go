# install

Powershell.exe
cd C:\ProgramData
Set-ExecutionPolicy bypass -Scope Process
Save-Script Get-IntuneManagementExtensionDiagnostics -Path ./
./Get-IntuneManagementExtensionDiagnostics.ps1

# -Online when you need to get displayNames to Powershell scripts
./Get-IntuneManagementExtensionDiagnostics.ps1 -Online

# install with graph

Install-Module -Name Microsoft.Graph.Intune -Scope CurrentUser
Save-Script Get-IntuneManagementExtensionDiagnostics -Path ./
./Get-IntuneManagementExtensionDiagnostics.ps1
