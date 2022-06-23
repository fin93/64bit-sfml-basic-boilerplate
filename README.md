# 64bit-sfml-basic-boilerplate

You need to have make, mingw 64 bit and g++ 
definitely should have chocolatey as it makes life easier 

open powershell as admin 

to install choco
```
Set-ExecutionPolicy Bypass -Scope Process -Force; [System.Net.ServicePointManager]::SecurityProtocol = [System.Net.ServicePointManager]::SecurityProtocol -bor 3072; iex ((New-Object System.Net.WebClient).DownloadString('https://community.chocolatey.org/install.ps1'))
```


```
choco install mingw
```
```
choco install make
```
in the main directory type ```make``` to build
