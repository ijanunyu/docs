---
title: "-= Operator (C# Reference)1 | Microsoft Docs"
ms.custom: ""
ms.date: "2015-07-20"
ms.prod: "visual-studio-dev14"
ms.reviewer: ""
ms.suite: ""
ms.technology: 
  - "devlang-csharp"
ms.tgt_pltfrm: ""
ms.topic: "article"
f1_keywords: 
  - "/=_CSharpKeyword"
dev_langs: 
  - "CSharp"
helpviewer_keywords: 
  - "division assignment operator (/=) [C#]"
  - "/= (division assignment operator) [C#]"
ms.assetid: 50fc02b0-ee9c-4c3e-b58d-d591282caf1c
caps.latest.revision: 17
author: "BillWagner"
ms.author: "wiwagn"
manager: "wpickett"
---
# /= Operator (C# Reference)
[!INCLUDE[csharpbanner](../../../includes/csharpbanner.md)]

The division assignment operator.  
  
## Remarks  
 An expression using the `/=` assignment operator, such as  
  
```  
x /= y  
```  
  
 is equivalent to  
  
```  
x = x / y  
```  
  
 except that `x` is only evaluated once. The [/ operator](../../../csharp/language-reference/operators/operator-csharp-reference.md) is predefined for numeric types to perform division.  
  
 The `/=` operator cannot be overloaded directly, but user-defined types can overload the [/ operator](../../../csharp/language-reference/operators/operator-csharp-reference.md) (see [operator](../../../csharp/language-reference/keywords/operator-csharp-reference.md)). On all compound assignment operators, overloading the binary operator implicitly overloads the equivalent compound assignment.  
  
## Example  
 [!code-cs[csRefOperators#5](../../../csharp/language-reference/operators/codesnippet/csharp/csrefOperators/csrefOperators.cs#5)]  
  
## See Also  
 [C# Reference](../../../csharp/language-reference/index.md)   
 [C# Programming Guide](../../../csharp/programming-guide/index.md)   
 [C# Operators](../../../csharp/language-reference/operators/index.md)