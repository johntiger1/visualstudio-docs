---
title: "IDebugBreakpointChecksumRequest2 | Microsoft Docs"
ms.custom: ""
ms.date: "11/04/2016"
ms.reviewer: ""
ms.suite: ""
ms.technology: 
  - "vs-ide-sdk"
ms.tgt_pltfrm: ""
ms.topic: "article"
helpviewer_keywords: 
  - "IDebugBreakpointChecksumRequest2 interface"
ms.assetid: 9cfdbca5-052c-48e9-8411-e2e9e4065d00
caps.latest.revision: 7
ms.author: "gregvanl"
manager: "ghogen"
---
# IDebugBreakpointChecksumRequest2
Represents a document checksum for a breakpoint request.  
  
## Syntax  
  
```  
IDebugBreakpointChecksumRequest2 : IUnknown  
```  
  
## Notes for Implementers  
 Implemented by the [!INCLUDE[vsprvs](../../../code-quality/includes/vsprvs_md.md)] Debug package and consumed by debug engines.  
  
## Methods  
 The following table shows the methods of `IDebugBreakpointChecksumRequest2`.  
  
|Method|Description|  
|------------|-----------------|  
|[GetChecksum](../../../extensibility/debugger/reference/idebugbreakpointchecksumrequest2-getchecksum.md)|Retrieves the document checksum for a breakpoint request given the unique identifier of the checksum algorithm to use.|  
|[IsChecksumEnabled](../../../extensibility/debugger/reference/idebugbreakpointchecksumrequest2-ischecksumenabled.md)|Determines if the checksum is enabled for this document.|  
  
## Requirements  
 Header: Msdbg.h  
  
 Namespace: Microsoft.VisualStudio.Debugger.Interop  
  
 Assembly: Microsoft.VisualStudio.Debugger.Interop.dll