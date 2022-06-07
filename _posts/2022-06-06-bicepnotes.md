---
title: Bicep Notes
date: 2022-06-05 12:00:00 -500
categories: [bicep]
tags: [notes bicep azure]
---


# Bicep Notes222333

**Links**

- [xxx](https://github.com)



**Commands**

```bicep


//Sample hello world
param yourName string
var hello = 'Hello World! - Hi'

output helloWorld string = '${hello} ${yourName}'



resource container 'Micrososoft.Storage/storageAccounts/blobServices/containers@2020-08-01-preview' = {
    name: '${stAcc.name}/default/${containerName}'
}
```