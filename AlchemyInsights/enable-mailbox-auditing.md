---
title: Mengaktifkan audit kotak pesan
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 04/21/2020
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom: ''
ms.assetid: 19997b0a-394f-4943-8908-c601696a332c
ms.openlocfilehash: 2bcfb7cc174cd58b21e1bb0c82f0d7cdb25e2fdd
ms.sourcegitcommit: bc7d6f4f3c9f7060d073f5130e1ec856e248d020
ms.translationtype: MT
ms.contentlocale: id-ID
ms.lasthandoff: 06/02/2020
ms.locfileid: "44506957"
---
# <a name="enable-mailbox-auditing"></a>Mengaktifkan audit kotak pesan

Untuk mengaktifkan audit kotak surat untuk salah satu pengguna atau seluruh organisasi cmdlet berikut harus dijalankan dari remote Power Shell:
  
 **Pengguna tunggal**
  
Set-kotak surat-identitas "Jane Dow"-AuditEnabled $true
  
 **Organisasi**
  
Get-kotak surat-ResultSize terbatas-filter {RecipientTypeDetails-EQ "UserMailbox"} | Set-kotak surat-AuditEnabled $true
  
[Pelajari lebih lanjut](https://docs.microsoft.com/microsoft-365/compliance/enable-mailbox-auditing)
  

