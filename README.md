# Zoodify-Plugin

## Prerequisite
- Windows (Powershell, Babun, Hyper, etc.)
```powershell
PS C:\WINDOWS\system32> # Choose package manger of choice (Chocolatey, Scoop, Appget, etc.)
PS C:\WINDOWS\system32> Set-ExecutionPolicy Bypass -Scope Process -Force; iex ((New-Object System.Net.WebClient).DownloadString('https://chocolatey.org/install.ps1'))
PS C:\WINDOWS\system32> choco upgrade chocolatey
PS C:\WINDOWS\system32> choco install -y nodejs.install yarn
PS C:\WINDOWS\system32> choco install -y python2
PS C:\WINDOWS\system32> choco install -y jdk8 # jdk11
PS C:\WINDOWS\system32> refreshenv
```