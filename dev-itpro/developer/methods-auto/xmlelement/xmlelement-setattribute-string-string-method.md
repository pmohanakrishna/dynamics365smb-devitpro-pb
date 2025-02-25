---
title: "XmlElement.SetAttribute(String, String) Method"
description: "Sets the value of the specified attribute or create it if is not part of the element's attribute collection."
ms.author: solsen
ms.custom: na
ms.date: 07/07/2021
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: reference
ms.service: "dynamics365-business-central"
author: SusanneWindfeldPedersen
---
[//]: # (START>DO_NOT_EDIT)
[//]: # (IMPORTANT:Do not edit any of the content between here and the END>DO_NOT_EDIT.)
[//]: # (Any modifications should be made in the .xml files in the ModernDev repo.)
# XmlElement.SetAttribute(String, String) Method
> **Version**: _Available or changed with runtime version 1.0._

Sets the value of the specified attribute or create it if is not part of the element's attribute collection.


## Syntax
```AL
 XmlElement.SetAttribute(Name: String, Value: String)
```
## Parameters
*XmlElement*  
&emsp;Type: [XmlElement](xmlelement-data-type.md)  
An instance of the [XmlElement](xmlelement-data-type.md) data type.  

*Name*  
&emsp;Type: [String](../string/string-data-type.md)  
The fully qualified name of the attribute to set.
        
*Value*  
&emsp;Type: [String](../string/string-data-type.md)  
The value to set for the attribute.  



[//]: # (IMPORTANT: END>DO_NOT_EDIT)
## See Also
[XmlElement Data Type](xmlelement-data-type.md)  
[Getting Started with AL](../../devenv-get-started.md)  
[Developing Extensions](../../devenv-dev-overview.md)