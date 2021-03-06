---
title: "BTAD_InstallDir | Microsoft Docs"
ms.custom: ""
ms.date: "06/08/2017"
ms.prod: "biztalk-server"
ms.reviewer: ""

ms.suite: ""
ms.tgt_pltfrm: ""
ms.topic: "article"
helpviewer_keywords: 
  - "BTAD_InstallDir [environment variable]"
ms.assetid: 3120f897-5501-4e99-8552-9d97e6314cd1
caps.latest.revision: 13
author: "MandiOhlinger"
ms.author: "mandia"
manager: "anneta"
---
# BTAD_InstallDir
BTAD_InstallDir contains the installation path of the BizTalk application. This is only available when the action is Create or Update, and BTAD_HostClass is BizTalkHostInstance.  
  
## Remarks  
 BTAD_InstallDir is set to the TARGETDIR property of the Windows Installer package. The default value is %ProgramFiles%\Generated by BizTalk\\<*application name*\>.  
  
## See Also  
 [Pre- and Post-processing Script Environment Variables](../core/pre-and-post-processing-script-environment-variables.md)   
 [How Environment Variables Indicate Deployment State](../core/how-environment-variables-indicate-deployment-state.md)   
 [How to Install a BizTalk Application](../core/how-to-install-a-biztalk-application.md)