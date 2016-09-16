---
title: "How to create child configuration items in System Center Configuration Manager"
ms.custom: na
ms.date: 2015-12-08
ms.prod: configuration-manager
ms.reviewer: na
ms.suite: na
ms.technology: 
  - configmgr-other
ms.tgt_pltfrm: na
ms.topic: article
ms.assetid: 113984fa-6150-41a1-89ed-d2a83b979732
caps.latest.revision: 5
caps.handback.revision: 0
author: robstackmsft
translation.priority.ht: 
  - cs-cz
  - de-de
  - en-gb
  - es-es
  - fr-fr
  - hu-hu
  - it-it
  - ja-jp
  - ko-kr
  - nl-nl
  - pl-pl
  - pt-br
  - pt-pt
  - ru-ru
  - sv-se
  - tr-tr
  - zh-cn
  - zh-tw
---
# How to create child configuration items in System Center Configuration Manager
Child configuration items in System Center Configuration Manager are copies of configuration items that retain a relationship to the original configuration item; therefore, they inherit the original configuration from the parent configuration item.  
  
 When you view the properties of a child configuration item in the Configuration Manager console, you can view, but not edit the inherited objects and settings with their validation criteria. However, you can add and then edit additional validation criteria to the child configuration item, and you can also add new objects and settings to the child configuration item. Therefore, the usual purpose for creating and editing a child configuration item is that it refines the original configuration item to meet your business requirements.  
  
> [!NOTE]  
>  You can only create child configuration items from configuration items of the type **Windows Desktops and Servers (custom)**.  
  
## To create a child configuration item  
  
1.  In the Configuration Manager console, click **Assets and Compliance**.  
  
2.  In the **Assets and Compliance** workspace, expand **Compliance Settings**, and then click **Configuration Items**.  
  
3.  In the **Configuration Items** list, select the configuration item for which you want to create a child configuration item, and then in the **Home** tab, in the **Configuration Item** group, click **Create Child Configuration Item**.  
  
4.  On the **General** page of the **Create Child Configuration Item Wizard**, you can choose a specific revision of the parent configuration item to use to create the child. Other steps in this wizard are identical to those you would use to create a standard configuration item. For more information, see [How to create custom configuration items for Windows desktop and server computers managed with the System Center Configuration Manager client](../../compliance/deploy-use/create-custom-configuration-items-for-windows-desktop-and-server-computers-managed-with-the-client.md).  
  
5.  Complete the wizard. The new child configuration item displays in the **Configuration Items** list.  
  
## See Also  
 [Compliance settings technical reference for System Center Configuration Manager](../../compliance/deploy-use/compliance-settings-technical-reference.md)