---
title: Menggunakan Exchange Online PowerShell untuk mengaktifkan DKIM untuk domain tertentu
ms.author: v-smandalika
author: v-smandalika
manager: dansimp
ms.date: 02/23/2021
audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9002531"
- "7375"
ms.openlocfilehash: 2f2b60a63b512bde794ba588852db11423e766f3
ms.sourcegitcommit: 78fe9f33438cb0c19f0dab31253b5853b73f4f47
ms.translationtype: MT
ms.contentlocale: id-ID
ms.lasthandoff: 03/05/2021
ms.locfileid: "50524177"
---
# <a name="use-exchange-online-powershell-to-enable-dkim-for-a-specific-domain"></a><span data-ttu-id="69f0c-102">Menggunakan Exchange Online PowerShell untuk mengaktifkan DKIM untuk domain tertentu</span><span class="sxs-lookup"><span data-stu-id="69f0c-102">Use Exchange Online PowerShell to enable DKIM for a specific domain</span></span>

<span data-ttu-id="69f0c-103">Jika Anda tidak dapat membuat catatan DNS DKIM di pusat admin, coba gunakan Exchange Online PowerShell.</span><span class="sxs-lookup"><span data-stu-id="69f0c-103">If you can't create the DKIM DNS records in the admin center, try using Exchange Online PowerShell.</span></span> 

<span data-ttu-id="69f0c-104">Untuk membuat catatan DNS DKIM menggunakan Exchange Online PowerShell, lakukan langkah-langkah berikut:</span><span class="sxs-lookup"><span data-stu-id="69f0c-104">To create a DKIM DNS record using Exchange Online PowerShell, perform the following steps:</span></span>

1. <span data-ttu-id="69f0c-105">Buka Windows PowerShell sebagai administrator dan jalankan perintah berikut dalam urutan yang dijelaskan:</span><span class="sxs-lookup"><span data-stu-id="69f0c-105">Open Windows PowerShell as an administrator and run the following commands in the described sequence:</span></span>

    <span data-ttu-id="69f0c-106">untuk.</span><span class="sxs-lookup"><span data-stu-id="69f0c-106">a.</span></span> `$UserCredential = Get-Credential`

    <span data-ttu-id="69f0c-107">b.</span><span class="sxs-lookup"><span data-stu-id="69f0c-107">b.</span></span> `$Session = New-PSSession -ConfigurationName Microsoft.Exchange -ConnectionUri https://outlook.office365.com/powershell-liveid/ -Credential $UserCredential -Authentication Basic -AllowRedirection`

    <span data-ttu-id="69f0c-108">'s.</span><span class="sxs-lookup"><span data-stu-id="69f0c-108">c.</span></span> `Import-PSSession $Session -DisableNameChecking`
    
<span data-ttu-id="69f0c-109">Jika Anda mengalami masalah saat menyambungkan ke Exchange Online PowerShell, lihat [menyambungkan ke Exchange Online PowerShell](https://docs.microsoft.com/powershell/exchange/connect-to-exchange-online-powershell).</span><span class="sxs-lookup"><span data-stu-id="69f0c-109">If you have trouble connecting to Exchange Online PowerShell, see [Connect to Exchange Online PowerShell](https://docs.microsoft.com/powershell/exchange/connect-to-exchange-online-powershell).</span></span>

2. <span data-ttu-id="69f0c-110">Setelah Anda tersambung ke Exchange Online PowerShell, jalankan perintah berikut:</span><span class="sxs-lookup"><span data-stu-id="69f0c-110">Once you're connected to Exchange Online PowerShell, run the following command:</span></span>

    `New-DkimSigningConfig -DomainName < CustomDomain > -Enabled $true`

3. <span data-ttu-id="69f0c-111">Setelah perintah di atas berhasil dieksekusi, jalankan perintah berikut ini untuk mengakhiri sesi PowerShell Exchange Online:</span><span class="sxs-lookup"><span data-stu-id="69f0c-111">Once the above command has been successfully executed, run the following command to terminate the Exchange Online PowerShell session:</span></span>

    `Remove-PSSession $Session` 


