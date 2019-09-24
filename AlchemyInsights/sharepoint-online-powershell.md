---
title: SharePoint online PowerShell
ms.author: v-todmc
author: todmccoy
manager: mnirkhe
ms.date: 9/18/19
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9000266"
- "1867"
ms.openlocfilehash: 00ec337ce34da9d3c3fba0a71602c3078a556552
ms.sourcegitcommit: 6b102e079a7d30298105fd811a67efb707d6d5bf
ms.translationtype: MT
ms.contentlocale: id-ID
ms.lasthandoff: 09/23/2019
ms.locfileid: "37123002"
---
# <a name="sharepoint-online-powershell"></a><span data-ttu-id="eddef-102">SharePoint online PowerShell</span><span class="sxs-lookup"><span data-stu-id="eddef-102">Sharepoint Online PowerShell</span></span>

<span data-ttu-id="eddef-103">Bekerja dengan PowerShell atau skrip dalam SharePoint online?</span><span class="sxs-lookup"><span data-stu-id="eddef-103">Working with PowerShell or Scripts within Sharepoint Online?</span></span> <span data-ttu-id="eddef-104">Kunjungi link di bawah ini untuk informasi lebih lanjut.</span><span class="sxs-lookup"><span data-stu-id="eddef-104">Visit the links below for more information.</span></span>
- [<span data-ttu-id="eddef-105">Memulai SharePoint online Management Shell</span><span class="sxs-lookup"><span data-stu-id="eddef-105">Getting started with SharePoint Online Management Shell</span></span>](https://docs.microsoft.com/powershell/sharepoint/sharepoint-online/connect-sharepoint-online?view=sharepoint-ps)
- [<span data-ttu-id="eddef-106">Sambungkan ke SPO PowerShell dengan otentikasi multifaktor (MFA)</span><span class="sxs-lookup"><span data-stu-id="eddef-106">Connect to SPO PowerShell with multifactor authentication (MFA)</span></span>](https://docs.microsoft.com/powershell/sharepoint/sharepoint-online/connect-sharepoint-online?view=sharepoint-ps#to-connect-with-multifactor-authentication-mfa)
- <span data-ttu-id="eddef-107">[Pola dan praktik SharePoint (PNP)](https://docs.microsoft.com/powershell/sharepoint/sharepoint-pnp/sharepoint-pnp-cmdlets?view=sharepoint-ps) berisi perpustakaan perintah PowerShell yang memungkinkan Anda untuk melakukan tindakan manajemen yang KOMPLEKS terhadap SPO.</span><span class="sxs-lookup"><span data-stu-id="eddef-107">[SharePoint Patterns and Practices (PnP)](https://docs.microsoft.com/powershell/sharepoint/sharepoint-pnp/sharepoint-pnp-cmdlets?view=sharepoint-ps) contains a library of PowerShell commands that allows you to perform complex management actions towards SPO.</span></span>

> [!NOTE]
> - <span data-ttu-id="eddef-108">Jika Anda mengalami masalah menyambung dengan SPO manajemen shell, pastikan bahwa Anda telah diperbarui ke versi terbaru dan mencoba [impor ulang modul](https://docs.microsoft.com/powershell/developer/module/importing-a-powershell-module) menggunakan *"Impor-modul Microsoft. online. SharePoint. PowerShell".*</span><span class="sxs-lookup"><span data-stu-id="eddef-108">If you are having issues connecting with the SPO management shell, make sure that you have updated to the latest version and try to [re-import the module](https://docs.microsoft.com/powershell/developer/module/importing-a-powershell-module) using *“Import-Module Microsoft.Online.SharePoint.PowerShell”.*</span></span>
> - <span data-ttu-id="eddef-109">Jika Anda mencoba untuk menjalankan skrip model objek klien, Anda akan perlu memiliki [SharePoint online klien komponen SDK](https://www.microsoft.com/download/details.aspx?id=42038) diinstal pada komputer lokal Anda.</span><span class="sxs-lookup"><span data-stu-id="eddef-109">If you are attempting to run client-side object model scripts, you will need to have the [Sharepoint Online Client Components SDK](https://www.microsoft.com/download/details.aspx?id=42038) installed on your local machine.</span></span>
> - <span data-ttu-id="eddef-110">Jika Anda mengalami masalah menjalankan skrip dari PowerShell, Anda mungkin ingin mempertimbangkan untuk menjalankan PowerShell sebagai administrator dan mengubah [kebijakan eksekusi](https://docs.microsoft.com/powershell/module/microsoft.powershell.core/about/about_execution_policies?view=powershell-6).</span><span class="sxs-lookup"><span data-stu-id="eddef-110">If you are having issues running scripts from PowerShell, you may want to consider running PowerShell as an Administrator and changing the [Execution Policy](https://docs.microsoft.com/powershell/module/microsoft.powershell.core/about/about_execution_policies?view=powershell-6).</span></span>