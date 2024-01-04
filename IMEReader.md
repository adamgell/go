# install

```powershell
Powershell.exe
cd C:\ProgramData
Set-ExecutionPolicy bypass -Scope Process
Save-Script Get-IntuneManagementExtensionDiagnostics -Path ./
./Get-IntuneManagementExtensionDiagnostics.ps1
```




# install with graph

```powershell
Install-Module -Name Microsoft.Graph.Intune -Scope CurrentUser
Save-Script Get-IntuneManagementExtensionDiagnostics -Path ./
./Get-IntuneManagementExtensionDiagnostics.ps1
```


```powershell
powershell -ex bypass -command "
```
