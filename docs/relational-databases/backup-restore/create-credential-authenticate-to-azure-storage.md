---
title: "Create Credential - Authenticate to Azure Storage | Microsoft Docs"
ms.custom: ""
ms.date: "03/01/2017"
ms.prod: sql
ms.prod_service: backup-restore
ms.reviewer: ""
ms.technology: backup-restore
ms.topic: conceptual
f1_keywords: 
  - "sql13.swb.backuptourl.createcred.f1"
ms.assetid: 0622619d-27c5-4ff0-83e5-cde31648c27a
author: MikeRayMSFT
ms.author: mikeray
---
# Create Credential - Authenticate to Azure Storage
[!INCLUDE[appliesto-ss-xxxx-xxxx-xxx-md](../../includes/appliesto-ss-xxxx-xxxx-xxx-md.md)]
  Use the **Backup to URL - Create Credential** dialog box to create a new SQL Credential.  
  
 When using this dialog box to create a credential, you must provide a Azure Management Certificate added to the local certificate store or a publishing profile downloaded to your computer to validate the subscription and the storage account information.  
  
 **SQL Credential**  
 Specify the name of the SQL Credential you want to create.  
  
## Azure Credentials  
 **Management Certificate**  
 Use this option to specify a certificate from the local certificate store that matches the management certificate from Azure. For more information on Azure management certificate, see [Create and Upload a Management Certificate for Azure](https://go.microsoft.com/fwlink/?LinkId=320781).  
  
 **Subscription**  
 Select, type, or paste your Azure subscription ID that matches the management certificate from the local certificate store.  
  
 **Publishing Profile**  
 Use this option if you have a publishing profile downloaded to your computer. If you use this option, the subscription ID, and the certificate are auto populated.  
  
> [!CAUTION]  
>  SQL Server currently supports publishing profile version 2.0. To download the supported version of the publishing profile, see [Download Publishing Profile 2.0](https://go.microsoft.com/fwlink/?LinkId=396421).  
  
## Storage Account  
 Select the storage account you want to use to store the backup files on.  
  
  
