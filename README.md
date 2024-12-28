# Welcome
Welcome to this project which contains almost everything for DevOps techstack either concepts or projects

## Requirement
Let's setup **chocolatey** package manager for our windows machine to download various softwares that we will be required during this journey. </br>
**Open powershell as administrator and run the following commands**
```powershell
Set-ExecutionPolicy Bypass -Scope Process -Force; [System.Net.ServicePointManager]::SecurityProtocol = [System.Net.ServicePointManager]::SecurityProtocol -bor 3072; iex ((New-Object System.Net.WebClient).DownloadString('https://community.chocolatey.org/install.ps1'))
```
Now run **choco or choco -?** to check the installation.
