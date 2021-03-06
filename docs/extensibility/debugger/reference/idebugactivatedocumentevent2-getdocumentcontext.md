---
title: "IDebugActivateDocumentEvent2::GetDocumentContext | Microsoft Docs"
ms.custom: ""
ms.date: "11/04/2016"
ms.reviewer: ""
ms.suite: ""
ms.technology: 
  - "vs-ide-sdk"
ms.tgt_pltfrm: ""
ms.topic: "article"
f1_keywords: 
  - "IDebugActivateDocumentEvent2::GetDocumentContext"
helpviewer_keywords: 
  - "GetDocumentContext method"
  - "IDebugActivateDocumentEvent2::GetDocumentContext method"
ms.assetid: e7472069-7337-4ef4-8f8a-8c027a2e22f4
caps.latest.revision: 10
ms.author: "gregvanl"
manager: "ghogen"
---
# IDebugActivateDocumentEvent2::GetDocumentContext
Gets the document context that describes the position in the document that is to be made active by the debug package.  
  
## Syntax  
  
```cpp  
HRESULT GetDocumentContext (   
   IDebugDocumentContext2** ppDocContext  
);  
```  
  
```csharp  
int GetDocumentContext (   
   out IDebugDocumentContext2 ppDocContext  
);  
```  
  
#### Parameters  
 `ppDocContext`  
 [out] Returns an [IDebugDocumentContext2](../../../extensibility/debugger/reference/idebugdocumentcontext2.md) object that represents a position in a source file document.  
  
## Remarks  
 This position might be used to show the caret, for example.  
  
## Return Value  
 If successful, returns `S_OK`; otherwise, returns an error code.  
  
## See Also  
 [IDebugActivateDocumentEvent2](../../../extensibility/debugger/reference/idebugactivatedocumentevent2.md)   
 [IDebugDocumentContext2](../../../extensibility/debugger/reference/idebugdocumentcontext2.md)