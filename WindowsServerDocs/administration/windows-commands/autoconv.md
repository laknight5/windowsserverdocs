---
title: autoconv
description: Windows Commands topic for **autoconv**, which converts file allocation table (Fat) and Fat32 volumes to the NTFS file system.
ms.prod: windows-server
ms.technology: manage-windows-commands
ms.topic: article
ms.assetid: 17281e54-0b18-4e84-94ac-24586c82df4e
author: coreyp-at-msft
ms.author: coreyp
manager: dongill
ms.date: 10/16/2017
---

# autoconv

>Applies To: Windows Server (Semi-Annual Channel), Windows Server 2016, Windows Server 2012 R2, Windows Server 2012

Converts file allocation table (Fat) and Fat32 volumes to the NTFS file system, leaving existing files and directories intact at startup after **autochk** runs. volumes converted to the NTFS file system cannot be converted back to Fat or Fat32.

## Remarks

You cannot run **autoconv** on the command-line. This will only be run at startup, if set through **convert.exe**.

## Additional References

- [Command-Line Syntax Key](command-line-syntax-key.md)

- [autochk](autochk.md)

- [convert](convert.md)

- [Working with File Systems](https://go.microsoft.com/fwlink/?LinkId=4509)
