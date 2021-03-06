---
title: "MODULE_FLAGS | Microsoft Docs"
ms.custom: ""
ms.date: "11/04/2016"
ms.reviewer: ""
ms.suite: ""
ms.technology: 
  - "vs-ide-sdk"
ms.tgt_pltfrm: ""
ms.topic: "article"
f1_keywords: 
  - "MODULE_FLAGS"
helpviewer_keywords: 
  - "MODULE_FLAGS enumeration"
ms.assetid: 0e555b42-b846-4dbb-812e-8e3d11c85b2d
caps.latest.revision: 11
ms.author: "gregvanl"
manager: "ghogen"
---
# MODULE_FLAGS
Used to describe a module.  
  
## Syntax  
  
```cpp  
enum enum_MODULE_FLAGS {   
   MODULE_FLAG_NONE        = 0x0000,  
   MODULE_FLAG_SYSTEM      = 0x0001,  
   MODULE_FLAG_SYMBOLS     = 0x0002,  
   MODULE_FLAG_64BIT       = 0x0004,  
   MODULE_FLAG_OPTIMIZED   = 0x0008,  
   MODULE_FLAG_UNOPTIMIZED = 0x0010  
};  
typedef DWORD MODULE_FLAGS;  
```  
  
```csharp  
public enum enum_MODULE_FLAGS {   
   MODULE_FLAG_NONE        = 0x0000,  
   MODULE_FLAG_SYSTEM      = 0x0001,  
   MODULE_FLAG_SYMBOLS     = 0x0002,  
   MODULE_FLAG_64BIT       = 0x0004,  
   MODULE_FLAG_OPTIMIZED   = 0x0008,  
   MODULE_FLAG_UNOPTIMIZED = 0x0010  
};  
```  
  
## Members  
 MODULE_FLAG_NONE  
 Specifies no module.  
  
 MODULE_FLAG_SYSTEM  
 Specifies a system module.  
  
 MODULE_FLAG_SYMBOLS  
 Specifies a symbol module.  
  
 MODULE_FLAG_64BIT  
 Specifies a 64-bit module.  
  
 MODULE_FLAG_OPTIMIZED  
 Specifies the module has been optimized. This state is reflected in the **Modules** window.  
  
 MODULE_FLAG_UNOPTIMIZED  
 Specifies the module has not been optimized. This state is reflected in the **Modules** window. This is the default state.  
  
## Remarks  
 Used for the `m_dwModuleFlags` member of the [MODULE_INFO](../../../extensibility/debugger/reference/module-info.md) structure.  
  
 These flags may be combined with a bitwise `OR`.  
  
## Requirements  
 Header: msdbg.h  
  
 Namespace: Microsoft.VisualStudio.Debugger.Interop  
  
 Assembly: Microsoft.VisualStudio.Debugger.Interop.dll  
  
## See Also  
 [Enumerations](../../../extensibility/debugger/reference/enumerations-visual-studio-debugging.md)   
 [MODULE_INFO](../../../extensibility/debugger/reference/module-info.md)