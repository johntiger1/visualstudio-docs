---
title: "Directory Status Code Enumerator | Microsoft Docs"
ms.custom: ""
ms.date: "11/04/2016"
ms.reviewer: ""
ms.suite: ""
ms.technology: 
  - "vs-ide-sdk"
ms.tgt_pltfrm: ""
ms.topic: "article"
helpviewer_keywords: 
  - "directory status code enumerator"
  - "source control plug-ins, directory status enumeration"
ms.assetid: 616026b5-f529-40ef-90c1-1836e116d797
caps.latest.revision: 13
ms.author: "gregvanl"
manager: "ghogen"
---
# Directory Status Code Enumerator
The `SccDirStatus` enumerator contains named constant values that specify the state of a directory in the source control system. This enumeration is used by the [SccDirQueryInfo](../extensibility/sccdirqueryinfo-function.md). This was introduced in version 1.2 of the Source Control Plug-in API.  
  
## Syntax  
  
```  
enum SccDirStatus {  
   SCC_DIRSTATUS_INVALID       = -1L,  
   SCC_DIRSTATUS_NOTCONTROLLED = 0x0000L,  
   SCC_DIRSTATUS_CONTROLLED    = 0x0001L,  
   SCC_DIRSTATUS_EMPTYPROJ     = 0x0002L  
};  
```  
  
## Members  
 SCC_DIRSTATUS_INVALID  
 Status could not be obtained; do not rely on it.  
  
 SCC_DIRSTATUS_NOTCONTROLLED  
 Directory is not under source control.  
  
 SCC_DIRSTATUS_CONTROLLED  
 Directory is under source control.  
  
 SCC_DIRSTATUS_EMPTYPROJ  
 Project corresponding to this directory is empty.  
  
## See Also  
 [Source Control Plug-ins](../extensibility/source-control-plug-ins.md)   
 [SccDirQueryInfo](../extensibility/sccdirqueryinfo-function.md)