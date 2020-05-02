---
title: Saluran pribadi
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9001223"
- "3205"
ms.openlocfilehash: be518df0d40123c1f0da6596bd6e2e91a0c2c8fa
ms.sourcegitcommit: 057d87c9d866fa1371d02350420d13774545c028
ms.translationtype: MT
ms.contentlocale: id-ID
ms.lasthandoff: 05/02/2020
ms.locfileid: "44005441"
---
# <a name="private-channels-in-microsoft-teams"></a><span data-ttu-id="64290-102">Saluran pribadi di Microsoft teams</span><span class="sxs-lookup"><span data-stu-id="64290-102">Private channels in Microsoft Teams</span></span>

<span data-ttu-id="64290-103">Saluran privat adalah fitur baru di Microsoft teams.</span><span class="sxs-lookup"><span data-stu-id="64290-103">Private channels is a new feature in Microsoft Teams.</span></span> <span data-ttu-id="64290-104">Perhatikan bahwa saluran pribadi tidak dapat dikonversi dari saluran standar atau sebaliknya.</span><span class="sxs-lookup"><span data-stu-id="64290-104">Note that private channels cannot be converted from standard channels or vice versa.</span></span>

<span data-ttu-id="64290-105">Untuk rincian tentang saluran pribadi, seperti informasi tentang [pembuatan saluran pribadi dan keanggotaan](https://docs.microsoft.com/MicrosoftTeams/private-channels#private-channel-creation-and-membership) dan [situs SharePoint saluran pribadi](https://docs.microsoft.com/MicrosoftTeams/private-channels#private-channel-sharepoint-sites), lihat [saluran pribadi di Microsoft teams](https://docs.microsoft.com/MicrosoftTeams/private-channels).</span><span class="sxs-lookup"><span data-stu-id="64290-105">For details about private channels, such as information on [private channel creation and membership](https://docs.microsoft.com/MicrosoftTeams/private-channels#private-channel-creation-and-membership) and [private channel SharePoint sites](https://docs.microsoft.com/MicrosoftTeams/private-channels#private-channel-sharepoint-sites), see [Private channels in Microsoft Teams](https://docs.microsoft.com/MicrosoftTeams/private-channels).</span></span> 

<span data-ttu-id="64290-106">**Catatan:** Karena konfigurasi untuk retensi pesan saluran pribadi belum didukung, penyewa dengan kebijakan retensi diaktifkan tidak akan memiliki saluran pribadi diaktifkan secara default.</span><span class="sxs-lookup"><span data-stu-id="64290-106">**Note:** Because configuration for retention of private channel messages is not yet supported, tenants with retention policies enabled will not have private channels enabled by default.</span></span> <span data-ttu-id="64290-107">Saluran pribadi dapat diaktifkan di pusat admin teams.</span><span class="sxs-lookup"><span data-stu-id="64290-107">Private channels can be enabled in the Teams admin center.</span></span> <span data-ttu-id="64290-108">Selain itu, perhatikan bahwa meskipun retensi pesan pribadi saluran tidak didukung, Penyimpanan file yang dibagi di saluran pribadi didukung.</span><span class="sxs-lookup"><span data-stu-id="64290-108">Also, note that while retention of private channel messages is not supported, retention of files shared in private channels is supported.</span></span>

<span data-ttu-id="64290-109">**Butuh pemilik tim baru?**</span><span class="sxs-lookup"><span data-stu-id="64290-109">**Need a new team owner?**</span></span>

<span data-ttu-id="64290-110">Jika pemilik Channel pribadi Anda keluar, Anda dapat menambahkan pemilik tim baru melalui teams PowerShell.</span><span class="sxs-lookup"><span data-stu-id="64290-110">If your private channel owner leaves, you can add a new team owner via Teams Powershell.</span></span>


- <span data-ttu-id="64290-111">Buka [di sini](https://www.powershellgallery.com/packages/MicrosoftTeams/1.0.6) untuk menginstal tim PowerShell.</span><span class="sxs-lookup"><span data-stu-id="64290-111">Go [here](https://www.powershellgallery.com/packages/MicrosoftTeams/1.0.6) to install Teams Powershell.</span></span>

<span data-ttu-id="64290-112">Berikut adalah cmdlet Anda akan perlu:</span><span class="sxs-lookup"><span data-stu-id="64290-112">Here is the cmdlet you will need:</span></span>

`
    Add-TeamChannelUser -GroupId <group_id> -DisplayName "<channel_name>" -User <UPN> -Role Owner
`

<span data-ttu-id="64290-113">Untuk informasi selengkapnya tentang teams PowerShell, lihat [ringkasan teams PowerShell](https://docs.microsoft.com/microsoftteams/teams-powershell-overview).</span><span class="sxs-lookup"><span data-stu-id="64290-113">For more information on Teams Powershell, see [Teams PowerShell Overview](https://docs.microsoft.com/microsoftteams/teams-powershell-overview).</span></span>
