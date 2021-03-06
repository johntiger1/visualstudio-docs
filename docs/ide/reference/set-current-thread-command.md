---
title: "Set Current Thread Command | Microsoft Docs"
ms.custom: ""
ms.date: "11/04/2016"
ms.reviewer: ""
ms.suite: ""
ms.technology: 
  - "vs-ide-general"
ms.tgt_pltfrm: ""
ms.topic: "article"
f1_keywords: 
  - "debug.setcurrentthread"
helpviewer_keywords: 
  - "Set Current Thread command"
  - "Debug.SetCurrentThread command"
ms.assetid: 9917ed1d-6c30-4d94-b2f0-69acce74f1b2
caps.latest.revision: 11
author: "gewarren"
ms.author: "gewarren"
manager: "ghogen"
---
# Set Current Thread Command
Sets the specified thread as the current thread.  
  
## Syntax  
  
```  
Debug.SetCurrentThread index  
```  
  
## Arguments  
 `index`  
 Required. Selects a thread by its index.  
  
## Example  
  
```  
>Debug.SetCurrentThread 1  
```  
  
## See Also  
 [Visual Studio Commands](../../ide/reference/visual-studio-commands.md)   
 [Command Window](../../ide/reference/command-window.md)   
 [Find/Command Box](../../ide/find-command-box.md)   
 [Visual Studio Command Aliases](../../ide/reference/visual-studio-command-aliases.md)