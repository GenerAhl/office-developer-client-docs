---
title: "PageTopMargin Cell (Print Properties Section)"
 
 
manager: soliver
ms.date: 03/09/2015
ms.audience: Developer
ms.topic: reference
f1_keywords:
- Vis_DSS.chm1033785
 
ms.localizationpriority: medium
ms.assetid: 2ba0fd22-65a6-6cb6-da00-08f391705544
description: "Specifies the margin at the top of the printer page."
---

# PageTopMargin Cell (Print Properties Section)

Specifies the margin at the top of the printer page.
  
## Remarks

This value represents physical units and is unaffected by scale or drawing units. For example, if this cell has a value of 0.25 in., this margin is 0.25 inch even if page units are feet. If units are not explicitly stated, this value defaults to page units. 
  
To get a reference to the PageTopMargin cell by name from another formula, or from a program using the **CellsU** property, use: 
  
|||
|:-----|:-----|
| Cell name:  <br/> | PageTopMargin  <br/> |
   
To get a reference to the PageTopMargin cell by index from a program, use the **CellsSRC** property with the following arguments: 
  
|||
|:-----|:-----|
| Section index:  <br/> |**visSectionObject** <br/> |
| Row index:  <br/> |**visRowPrintProperties** <br/> |
| Cell index:  <br/> |**visPrintPropertiesTopMargin** <br/> |
   

