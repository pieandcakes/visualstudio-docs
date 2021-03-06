---
title: "Mixed Code and Missing Information in the Call Stack Window | Microsoft Docs"
ms.custom: ""
ms.date: "2018-06-30"
ms.prod: "visual-studio-dev14"
ms.reviewer: ""
ms.suite: ""
ms.technology: 
  - "vs-ide-debug"
ms.tgt_pltfrm: ""
ms.topic: "article"
dev_langs: 
  - "FSharp"
  - "VB"
  - "CSharp"
  - "C++"
  - "JScript"
  - "SQL"
  - "VB"
  - "CSharp"
  - "C++"
helpviewer_keywords: 
  - "managed code, stepping"
  - "Call Stack window, mixed-mode debugging"
  - "Call Stack window, troubleshooting"
  - "native frames"
  - "managed call stacks"
  - "mixed-mode debugging, call stack"
  - "stepping, out of managed code"
ms.assetid: dd628427-e8d6-4fc2-b524-9d6393ea5376
caps.latest.revision: 23
author: "mikejo5000"
ms.author: "mikejo"
manager: "ghogen"
---
# Mixed Code and Missing Information in the Call Stack Window
[!INCLUDE[vs2017banner](../includes/vs2017banner.md)]

The latest version of this topic can be found at [Mixed Code and Missing Information in the Call Stack Window](https://docs.microsoft.com/visualstudio/debugger/mixed-code-and-missing-information-in-the-call-stack-window).  
  
Because of differences between call stacks for managed and native code, the debugger cannot always show the complete call stack when the code types mix. When native code calls managed code, you may notice the following discrepancies in the **Call Stack** window:  
  
-   The native frame immediately above the managed code may be missing from the **Call Stack** window. For more information, see [How to: Step out of Managed Code when Native Frames are Missing from the Call Stack Window](../debugger/how-to-step-out-of-managed-code-when-native-frames-are-missing-from-the-call-stack-window.md).  
  
-   For mixed-mode applications launched outside the debugger, the **Call Stack** window may display only the managed code and none of the native frames will be visible.  
  
 Both cases are fairly rare. In most native calls to managed code, call stacks appear correctly.  
  
## See Also  
 [How to: Use the Call Stack Window](../debugger/how-to-use-the-call-stack-window.md)





