---
title: Running Docker in a Hyper-V VM
date: 2022-06-06 12:00:00 -500
categories: [config]
tags: [hyper-v docker]
---

# PowerShell command to allow Docker to run in a Hyper-V VM


```powershell
Set-VMProcessor -VMName Dev-DOCKER-Win -ExposeVirtualizationExtensions $true
```
