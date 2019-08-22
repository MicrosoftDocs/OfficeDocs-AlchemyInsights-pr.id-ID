---
title: Mengidentifikasi alamat IP dan klien dalam log audit
ms.author: chrisda
author: chrisda
manager: dansimp
ms.date: ''
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "1367"
- "3100005"
ms.assetid: ''
ms.openlocfilehash: e0119762d2a34bd2b0da827faf55c832e29d8a2b
ms.sourcegitcommit: 1d98db8acb9959aba3b5e308a567ade6b62da56c
ms.translationtype: MT
ms.contentlocale: id-ID
ms.lasthandoff: 08/22/2019
ms.locfileid: "36539032"
---
# <a name="identify-ip-address-and-client-in-audit-logs"></a><span data-ttu-id="c0b30-102">Mengidentifikasi alamat IP dan klien dalam log audit</span><span class="sxs-lookup"><span data-stu-id="c0b30-102">Identify IP address and client in audit logs</span></span>

<span data-ttu-id="c0b30-103">Alamat IP yang berkaitan dengan aktivitas oleh Office 365 pengguna atau administrator akan ditampilkan dalam log Audit.</span><span class="sxs-lookup"><span data-stu-id="c0b30-103">The IP address that corresponds to an activity by an Office 365 user or administrator is shown in the Audit Logs.</span></span> <span data-ttu-id="c0b30-104">Informasi klien juga login.</span><span class="sxs-lookup"><span data-stu-id="c0b30-104">The client information is also logged.</span></span> <span data-ttu-id="c0b30-105">Berikut adalah langkah-langkah untuk mengidentifikasi informasi tersebut</span><span class="sxs-lookup"><span data-stu-id="c0b30-105">Here are the steps to identifying such information</span></span>

1. <span data-ttu-id="c0b30-106">Masuk ke [Kantor 365 keamanan & Compliance Center](https://protection.office.com/).</span><span class="sxs-lookup"><span data-stu-id="c0b30-106">Log in to the [Office 365 Security & Compliance Center](https://protection.office.com/).</span></span>

2. <span data-ttu-id="c0b30-107">Pergi ke **pencarian** > halaman**pencarian log Audit** .</span><span class="sxs-lookup"><span data-stu-id="c0b30-107">Go to the **Search** > **Audit log search** page.</span></span>

   <span data-ttu-id="c0b30-108">Jika Anda tertarik untuk aktivitas tertentu, pilih dari daftar **kegiatan** .</span><span class="sxs-lookup"><span data-stu-id="c0b30-108">If you're interested in a specific activity, select it from **Activities** list.</span></span> <span data-ttu-id="c0b30-109">Jika tidak, Semua kegiatan akan dikembalikan untuk pemakai dipilih (pengaturan default).</span><span class="sxs-lookup"><span data-stu-id="c0b30-109">If not, all activities will be returned for the selected user (default setting).</span></span>

   <span data-ttu-id="c0b30-110">**Catatan**: aktivitas tertentu mungkin tidak tersedia di menu **kegiatan** ; Namun, mereka melakukan audit item akan dikembalikan jika **Menunjukkan hasil untuk semua kegiatan** adalah dipilih (pengaturan default).</span><span class="sxs-lookup"><span data-stu-id="c0b30-110">**Note**: Certain activities may not be available in the **Activities** menu; however, those audit items will be returned if **Show Results for all activities** is selected (default setting).</span></span>

3. <span data-ttu-id="c0b30-111">Tentukan nama pengguna di bidang **pengguna** , pilih rentang tanggal yang tepat untuk kegiatan, dan kemudian klik **Cari**.</span><span class="sxs-lookup"><span data-stu-id="c0b30-111">Specify the username in the **Users** field, select the appropriate date range for the activity, and then click **Search**.</span></span>

<span data-ttu-id="c0b30-112">Hasil, Anda dapat melihat alamat IP untuk aktivitas di panel hasil.</span><span class="sxs-lookup"><span data-stu-id="c0b30-112">In the results, you can see the IP address for that activity in the results pane.</span></span> <span data-ttu-id="c0b30-113">Pilih record audit untuk melihat informasi rinci di flyout **rincian** (misalnya, klien, pengguna yang melakukan tindakan, dll).</span><span class="sxs-lookup"><span data-stu-id="c0b30-113">Select the audit record to see detailed information in the **Details** flyout (for example, Client, User that performed action, etc.).</span></span>

<span data-ttu-id="c0b30-114">Untuk selengkapnya, lihat [mencari alamat IP komputer yang digunakan untuk mengakses account dikompromikan](https://docs.microsoft.com/office365/securitycompliance/auditing-troubleshooting-scenarios#finding-the-ip-address-of-the-computer-used-to-access-a-compromised-account).</span><span class="sxs-lookup"><span data-stu-id="c0b30-114">For more information, see [Finding the IP address of the computer used to access a compromised account](https://docs.microsoft.com/office365/securitycompliance/auditing-troubleshooting-scenarios#finding-the-ip-address-of-the-computer-used-to-access-a-compromised-account).</span></span>
