---
title: "IDebugSymbolProvider::GetContextFromAddress | Microsoft Docs"
ms.custom: ""
ms.date: "2018-06-30"
ms.prod: "visual-studio-dev14"
ms.reviewer: ""
ms.suite: ""
ms.technology: 
  - "vs-ide-sdk"
ms.tgt_pltfrm: ""
ms.topic: "article"
f1_keywords: 
  - "IDebugSymbolProvider::GetContextFromAddress"
helpviewer_keywords: 
  - "IDebugSymbolProvider::GetContextFromAddress method"
ms.assetid: 7a27d56f-20d4-4e5c-af7b-7307d3aff0a1
caps.latest.revision: 12
ms.author: "gregvanl"
manager: "ghogen"
---
# IDebugSymbolProvider::GetContextFromAddress
[!INCLUDE[vs2017banner](../../../includes/vs2017banner.md)]

The latest version of this topic can be found at [IDebugSymbolProvider::GetContextFromAddress](https://docs.microsoft.com/visualstudio/extensibility/debugger/reference/idebugsymbolprovider-getcontextfromaddress).  
  
This method maps a debug address into a document context.  
  
## Syntax  
  
```cpp#  
HRESULT GetContextFromAddress(   
   IDebugAddress*           pAddress,  
   IDebugDocumentContext2** ppDocContext  
);  
```  
  
```csharp  
int GetContextFromAddress(  
   IDebugAddress              pAddress,   
   out IDebugDocumentContext2 ppDocContext  
);  
```  
  
#### Parameters  
 `pAddress`  
 [in] The debug address as represented by an [IDebugAddress](../../../extensibility/debugger/reference/idebugaddress.md) interface.  
  
 `ppDocContext`  
 [out] Returns a document context as represented by an [IDebugDocumentContext2](../../../extensibility/debugger/reference/idebugdocumentcontext2.md) interface.  
  
## Return Value  
 If successful, returns `S_OK`; otherwise, returns an error code.  
  
## See Also  
 [IDebugSymbolProvider](../../../extensibility/debugger/reference/idebugsymbolprovider.md)   
 [IDebugAddress](../../../extensibility/debugger/reference/idebugaddress.md)   
 [IDebugDocumentContext2](../../../extensibility/debugger/reference/idebugdocumentcontext2.md)

