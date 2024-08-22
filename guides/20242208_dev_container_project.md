---
title: "How to Create a Dev Container Project"
description: "A brief description of what the guide covers. The description should be a maximum of 160 characters."
date: 2024-08-22
author: "Varun Seenivasan"
tags: ["Dev", "Container", "CLI"]
---

# How to Create a Dev Container Project

## Introduction

### Installation
To see all installation options go to the documentation for Daytona: 
https://www.daytona.io/docs/installation/installation/
#### Mac/Linux
Run the following curl command in order to install Daytona:

`curl -sfL https://download.daytona.io/daytona/install.sh | sudo bash && daytona server -y && daytona`
#### Windows
Run the following command in Windows Powershell

`$architecture = if ($env:PROCESSOR_ARCHITECTURE -eq "AMD64") { "amd64" } else { "arm64" }
md -Force "$Env:APPDATA\bin\daytona"; [System.Net.ServicePointManager]::SecurityProtocol = [System.Net.SecurityProtocolType]'Tls,Tls11,Tls12';
Invoke-WebRequest -URI "https://download.daytona.io/daytona/latest/daytona-windows-$architecture.exe" -OutFile "$Env:APPDATA\bin\daytona\daytona.exe";
$env:Path += ";" + $Env:APPDATA + "\bin\daytona"; [Environment]::SetEnvironmentVariable("Path", $env:Path, [System.EnvironmentVariableTarget]::User);
daytona serve;`
###

https://www.daytona.io/docs/reference/cli/

https://www.daytona.io/docs/usage/builders/#dev-container-builder


