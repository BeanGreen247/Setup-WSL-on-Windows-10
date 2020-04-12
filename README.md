# WSL install guide

## Prerequisites
install C++ Runtime v11.0 framework package

https://www.microsoft.com/en-us/download/details.aspx?id=53340

install C++ Runtime v12 framework package

https://www.microsoft.com/en-us/download/details.aspx?id=53176

install C++ Runtime v14 framework package

https://www.microsoft.com/en-us/download/details.aspx?id=53175

## Distros
List of distros you can install

https://docs.microsoft.com/en-us/windows/wsl/install-manual

## WSL
Run Powershell as administrator and type this into Powershell
```
Enable-WindowsOptionalFeature -Online -FeatureName Microsoft-Windows-Subsystem-Linux
```
```
Invoke-WebRequest -Uri https://aka.ms/wsl-ubuntu-1804 -OutFile Ubuntu.appx -UseBasicParsing
```
```
Add-AppxPackage .\Ubuntu.appx
```
next run `Ubuntu 18.04` app from the star menu or by searching `ubuntu 18.04`

wait till it gets installed

then set up you username and password, it will ask you to retype your password to confirm it

then run 
```
sudo apt update
```
That is it you are all set.
