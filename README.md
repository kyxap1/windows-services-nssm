# windows-services-nssm
Run windows services with Non-Sucking Service Manager (NSSM)

## Install Chocolatey
[Chocolatey](https://chocolatey.org) is Windows package manager used to automate software installation.
```powershell
// Run this as Administrator from WindowsPoweShell terminal
Set-ExecutionPolicy Bypass -Scope Process -Force; [System.Net.ServicePointManager]::SecurityProtocol = [System.Net.ServicePointManager]::SecurityProtocol -bor 3072; iex ((New-Object System.Net.WebClient).DownloadString('https://chocolatey.org/install.ps1'))
```

## Install NSSM
[NSSM](https://nssm.cc) (Non-Sucking Service Manager) is the easiest way to run windows applications as service.
```cmd
choco install -y nssm
```
