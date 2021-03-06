---
title: "_pAtlModule | Microsoft Docs"
ms.custom: ""
ms.date: "11/04/2016"
ms.reviewer: ""
ms.suite: ""
ms.technology: ["cpp-windows"]
ms.tgt_pltfrm: ""
ms.topic: "reference"
f1_keywords: ["ATLBASE/ATL::_pAtlModule"]
dev_langs: ["C++"]
helpviewer_keywords: ["pAtlModule variable", "_pAtlModule variable"]
ms.assetid: 0ecde3a9-3f4d-4c7b-bb54-713ce05c4777
caps.latest.revision: 13
author: "mikeblome"
ms.author: "mblome"
manager: "ghogen"
---
# _pAtlModule
A global variable storing a pointer to the current module.  
  
## Syntax  
  
```  
__declspec(selectany) CAtlModule* _pAtlModule  
```  
  
## Remarks  
 Methods on this global variable can be used to provide the functionality that the (now obsolete) class [CComModule](../../atl/reference/ccommodule-class.md) provided in Visual C++ 6.0.  
  
## Example  
 [!code-cpp[NVC_ATL_Windowing#97](../../atl/codesnippet/cpp/patlmodule_1.cpp)]  
  
## Requirements  
 **Header:** atlbase.h  
  
## See Also  
 [Global Variables](../../atl/reference/atl-global-variables.md)



