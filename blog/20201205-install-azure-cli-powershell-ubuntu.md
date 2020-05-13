---
title: Install Azure CLI and Powershell on Ubuntu
path: /azure-ubuntu
date: 2019-03-07
summary: Learn how to install easily Azure CLI and Powershell on Ubuntu.
tags: ['azure', 'cli', powershell]
---

## Azure CLI

```shell
sudo apt-get update
sudo apt-get install ca-certificates curl apt-transport-https lsb-release gnupg
curl -sL https://packages.microsoft.com/keys/microsoft.asc | gpg --dearmor | sudo tee /etc/apt/trusted.gpg.d/microsoft.asc.gpg > /dev/null
AZ_REPO=$(lsb_release -cs) echo  "deb [arch=amd64] https://packages.microsoft.com/repos/azure-cli/ $AZ_REPO main" | sudo tee /etc/apt/sources.list.d/azure-cli.list
sudo apt-get update sudo apt-get install azure-cli
az  login
# Put your credentials
az account list
```

## Azure Power Shell

First you need to install Power Shell core

```shell
sudo snap install powershell --classic
# open powershell
pwsh
$PSVersionTable.PSVersion
```

Install AZ modules in powershell

```powershell
#On powershell
PS /home/rafael> Install-Module -Name Az -AllowClobber
PS /home/rafael> Connect-AzAccount
WARNING: To sign in, use a web browser to open the page https://microsoft.com/devicelogin and enter the code BRNLELLJN to authenticate.
```
