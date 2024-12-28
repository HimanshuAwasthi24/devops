# Welcome
Welcome to this project which contains almost everything for DevOps techstack either concepts or projects

## Requirement
Let's setup **chocolatey** package manager for our windows machine to download various softwares that we will be required during this journey. </br>
**Open powershell as administrator and run the following commands**
```powershell
Set-ExecutionPolicy Bypass -Scope Process -Force; [System.Net.ServicePointManager]::SecurityProtocol = [System.Net.ServicePointManager]::SecurityProtocol -bor 3072; iex ((New-Object System.Net.WebClient).DownloadString('https://community.chocolatey.org/install.ps1'))
```
Now run **choco or choco -?** to check the installation.

## Softwares to be installed
**Again open powershell as administrator and run the following commands one by one**
```powershell
choco install virtualbox --version=7.1.4 -y
choco install vagrant --version=2.4.3 -y
choco install git -y
choco install corretto17jdk -y
choco install maven -y
choco install awscli -y
choco install intellijidea-community -y
choco install vscode -y
choco install sublimetext3 -y
```

## Directories
Now you are all set to follow the fanastic journey of learnig DevOps, Follow the directory structure sequentially to have full grasp over concepts and doing projects.</br>
[VM Setup](./vm-setup/) - Contains to process of setting up vm's manually and automatically
