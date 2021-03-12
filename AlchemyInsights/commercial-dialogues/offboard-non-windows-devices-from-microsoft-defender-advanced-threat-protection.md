---
title: Perangkat non-Windows Offboard dari Microsoft Defender Advanced Threat Protection (ATP)
ms.author: v-jmathew
author: v-jmathew
manager: dansimp
audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9000760"
- "7391"
ms.openlocfilehash: 435957c555cd80155a985a49bd94b041a4ada31d
ms.sourcegitcommit: 6312ee31561db36104f32282d019d069ede69174
ms.translationtype: MT
ms.contentlocale: id-ID
ms.lasthandoff: 03/11/2021
ms.locfileid: "50745648"
---
# <a name="offboard-non-windows-devices-from-microsoft-defender-advanced-threat-protection-atp"></a><span data-ttu-id="b300f-102">Perangkat non-Windows Offboard dari Microsoft Defender Advanced Threat Protection (ATP)</span><span class="sxs-lookup"><span data-stu-id="b300f-102">Offboard non-Windows devices from Microsoft Defender Advanced Threat Protection (ATP)</span></span>

<span data-ttu-id="b300f-103">Berikut caranya:</span><span class="sxs-lookup"><span data-stu-id="b300f-103">Here's how:</span></span>

1. <span data-ttu-id="b300f-104">Ikuti dokumentasi pihak ketiga untuk memutuskan koneksi solusi pihak ketiga dari Microsoft Defender ATP.</span><span class="sxs-lookup"><span data-stu-id="b300f-104">Follow the third-party documentation for disconnecting the third-party solution from Microsoft Defender ATP.</span></span>
2. <span data-ttu-id="b300f-105">Dari penyewa direktori aktif Azure Anda, Hapus izin untuk solusi pihak ketiga:</span><span class="sxs-lookup"><span data-stu-id="b300f-105">From your Azure Active Directory tenant, remove permissions for the third-party solution:</span></span>

    1. <span data-ttu-id="b300f-106">Masuk ke [Azure portal](https://go.microsoft.com/fwlink/?linkid=2125612).</span><span class="sxs-lookup"><span data-stu-id="b300f-106">Sign in to the [Azure portal](https://go.microsoft.com/fwlink/?linkid=2125612).</span></span>
    1. <span data-ttu-id="b300f-107">Pilih **semua**  >  aplikasi **Azure Active Directory**  >  **Enterprise** Services.</span><span class="sxs-lookup"><span data-stu-id="b300f-107">Select **All services** > **Azure Active Directory** > **Enterprise Applications**.</span></span>
    1. <span data-ttu-id="b300f-108">Pilih aplikasi yang ingin Anda Offboard.</span><span class="sxs-lookup"><span data-stu-id="b300f-108">Select the application you'd like to offboard.</span></span>
    1. <span data-ttu-id="b300f-109">Pilih **Hapus**.</span><span class="sxs-lookup"><span data-stu-id="b300f-109">Select **Delete**.</span></span>

<span data-ttu-id="b300f-110">Untuk mempelajari selengkapnya, lihat [Offboard perangkat non-Windows](https://go.microsoft.com/fwlink/?linkid=2143630).</span><span class="sxs-lookup"><span data-stu-id="b300f-110">To learn more, see [Offboard non-Windows devices](https://go.microsoft.com/fwlink/?linkid=2143630).</span></span>