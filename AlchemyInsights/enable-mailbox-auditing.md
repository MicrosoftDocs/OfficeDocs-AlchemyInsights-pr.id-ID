---
title: Mengaktifkan kotak pesan audit
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 4/5/2018
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom: ''
ms.assetid: 19997b0a-394f-4943-8908-c601696a332c
ms.openlocfilehash: 1ef60017f1ea656296bc7b2aa3bc5365646f11f3
ms.sourcegitcommit: 1d98db8acb9959aba3b5e308a567ade6b62da56c
ms.translationtype: MT
ms.contentlocale: id-ID
ms.lasthandoff: 08/22/2019
ms.locfileid: "36527610"
---
# <a name="enable-mailbox-auditing"></a>Mengaktifkan kotak pesan audit

Aktifkan kotak pesan audit untuk pengguna tunggal atau seluruh organisasi cmdlet berikut harus dijalankan dari Remote Power Shell:
  
 **Satu pengguna**
  
Set-kotak surat - identitas "Jane Dow" - AuditEnabled $true
  
 **Organisasi**
  
Get-kotak surat - ResultSize Unlimited - Filter {RecipientTypeDetails - persamaan "UserMailbox"} | Set-kotak surat - AuditEnabled $true
  
[Pelajari lebih lanjut](https://support.office.com/article/aaca8987-5b62-458b-9882-c28476a66918)
  

