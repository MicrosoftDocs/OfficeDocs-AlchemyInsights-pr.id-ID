---
title: Batas harian email melebihi. Alur kerja ini ditangguhkan.
ms.author: efrene
author: efrene
manager: pamgreen
ms.date: 7/25/2019
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "5200020"
- "1227"
ms.openlocfilehash: 802aba696da61be5f0a6c12072842cbc3cd96499
ms.sourcegitcommit: 407f6c1e82f1a0be5cf53301fbf03cd25dcbf0ee
ms.translationtype: MT
ms.contentlocale: id-ID
ms.lasthandoff: 08/02/2019
ms.locfileid: "36059642"
---
# <a name="daily-email-limit-exceeded-workflow-is-suspended"></a><span data-ttu-id="51100-103">Email harian yang melebihi batas.</span><span class="sxs-lookup"><span data-stu-id="51100-103">Daily email Limit Exceeded.</span></span> <span data-ttu-id="51100-104">Alur kerja ini ditangguhkan.</span><span class="sxs-lookup"><span data-stu-id="51100-104">Workflow is suspended.</span></span>

<span data-ttu-id="51100-105">Kesalahan ini dapat diterima dalam skenario berikut:</span><span class="sxs-lookup"><span data-stu-id="51100-105">This error may be received in the following scenarios:</span></span>

- <span data-ttu-id="51100-106">Anda memiliki alur kerja di SharePoint Online yang menggunakan SharePoint 2010 atau jenis platform SharePoint 2013 alur kerja.</span><span class="sxs-lookup"><span data-stu-id="51100-106">You have a workflow in SharePoint Online that's using the SharePoint 2010 or SharePoint 2013 workflow platform type.</span></span>
- <span data-ttu-id="51100-107">Alur kerja dikonfigurasi untuk mengirim pesan email kustom ke lebih dari 200 pengguna pada suatu waktu, lebih dari 10.000 Penerima per hari atau lebih dari 30 pesan per menit.</span><span class="sxs-lookup"><span data-stu-id="51100-107">The workflow is configured to send a custom email message to more than 200 users at a time, more than 10,000 recipients per day, or more than 30 messages per minute.</span></span>
- <span data-ttu-id="51100-108">Ketika Anda menjalankan alur kerja, pesan email tidak dikirim, dan Anda melihat aktivitas berikut:</span><span class="sxs-lookup"><span data-stu-id="51100-108">When you run the workflow, the email message isn't sent, and you notice the following behavior:</span></span>
    - <span data-ttu-id="51100-109">Untuk alur kerja menggunakan jenis platform SharePoint 2013, Anda browse ke halaman **Alur kerja Status** .</span><span class="sxs-lookup"><span data-stu-id="51100-109">For a workflow using the SharePoint 2013 platform type, you browse to the **Workflow Status** page.</span></span> <span data-ttu-id="51100-110">Pada halaman Status alur kerja, **Internal Status** diatur untuk **memulai**, dan menampilkan informasi balon **gagal mengirim ke penerima**.</span><span class="sxs-lookup"><span data-stu-id="51100-110">On the Workflow Status page, the **Internal Status** is set to **Started**, and the information balloon displays **Unable to send to a recipient**.</span></span>

<span data-ttu-id="51100-111">Untuk mengatasi masalah ini, konfigurasikan alur kerja Anda untuk mengirim pesan email tanpa melebihi [batas pengirim Exchange Online](https://docs.microsoft.com/office365/servicedescriptions/exchange-online-service-description/exchange-online-limits#recipientlimits).</span><span class="sxs-lookup"><span data-stu-id="51100-111">To work around this issue, configure your workflow to send email messages without exceeding the [Exchange Online sender limits](https://docs.microsoft.com/office365/servicedescriptions/exchange-online-service-description/exchange-online-limits#recipientlimits).</span></span> <span data-ttu-id="51100-112">Misalnya, menggunakan jeda dalam alur kerja, kirim email ke Office 365 grup, grup distribusi, atau grup mail diaktifkan keamanan, atau mengirim pesan ke kurang dari 200 Penerima pada suatu waktu.</span><span class="sxs-lookup"><span data-stu-id="51100-112">For example, use a pause in the workflow, send the email to an Office 365 group, a distribution group or mail enabled security group, or send the message to fewer than 200 recipients at a time.</span></span>


<span data-ttu-id="51100-113">Untuk informasi lebih lanjut, lihat [artikel](https://support.microsoft.com/help/3150442/daily-email-limit-has-exceeded-and-your-workflow-has-been-suspended-or)berikut.</span><span class="sxs-lookup"><span data-stu-id="51100-113">For more information, see the following [article](https://support.microsoft.com/help/3150442/daily-email-limit-has-exceeded-and-your-workflow-has-been-suspended-or).</span></span>

## <a name="related-topics"></a><span data-ttu-id="51100-114">Topik terkait</span><span class="sxs-lookup"><span data-stu-id="51100-114">Related topics</span></span>
- [<span data-ttu-id="51100-115">Menciptakan aliran</span><span class="sxs-lookup"><span data-stu-id="51100-115">Create Flow</span></span>](https://support.office.com/article/Create-a-flow-for-a-list-or-library-in-SharePoint-Online-or-OneDrive-for-Business-a9c3e03b-0654-46af-a254-20252e580d01) 
- [<span data-ttu-id="51100-116">SharePoint dan aliran</span><span class="sxs-lookup"><span data-stu-id="51100-116">SharePoint and Flow</span></span>](https://flow.microsoft.com/blog/sharepoint-and-flow/) 