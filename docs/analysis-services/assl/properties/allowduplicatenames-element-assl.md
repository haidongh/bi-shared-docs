---
title: "AllowDuplicateNames Element (ASSL) | Microsoft Docs"
description: Learn about the AllowDuplicateNames property element in the Analysis Services Scripting Language (ASSL) schema.
ms.date: 02/14/2022
ms.service: analysis-services
ms.custom: assl
ms.topic: reference
ms.author: owend
ms.reviewer: owend
author: minewiskan

---
# AllowDuplicateNames Element (ASSL)

  Determines whether duplicate names are allowed in a [Hierarchy](../objects/hierarchy-element-assl.md) element.  
  
## Syntax  
  
```xml  
  
<Hierarchy>  
      ...  
   <AllowDuplicateNames>...</AllowDuplicateNames>  
   ...  
</Hierarchy>  
```  
  
## Element Characteristics  
  
|Characteristic|Description|  
|--------------------|-----------------|  
|Data type and length|Boolean|  
|Default value|**True**|  
|Cardinality|0-1: Optional element that can occur once and only once.|  
  
## Element Relationships  
  
|Relationship|Element|  
|------------------|-------------|  
|Parent element|[Hierarchy](../objects/hierarchy-element-assl.md)|  
|Child elements|None|  
  
## Remarks  
 The element that corresponds to the parent of **AllowDuplicateNames** in the Analysis Management Objects (AMO) object model is <xref:Microsoft.AnalysisServices.Hierarchy>.  
  
## See Also  
 [Properties &#40;ASSL&#41;](properties-assl.md)  
  
  
