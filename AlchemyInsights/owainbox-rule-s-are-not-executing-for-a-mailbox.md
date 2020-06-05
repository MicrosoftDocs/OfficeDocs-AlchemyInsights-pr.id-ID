---
title: 1332 OWA-kotak masuk aturan (s) tidak mengeksekusi untuk kotak surat
ms.author: chrisda
author: chrisda
manager: dansimp
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "1332"
- "3700002"
ms.assetid: 383d1c77-5e4b-4a69-92d6-c404d890b6b7
ms.openlocfilehash: 9abdcdcb33d39b8b9fe2df80f0c15a8b55e465fd
ms.sourcegitcommit: f28dafa0f727870038f72bc904da926daf4ec07b
ms.translationtype: MT
ms.contentlocale: id-ID
ms.lasthandoff: 06/05/2020
ms.locfileid: "44576563"
---
# <a name="an-inbox-rule-doesnt-work-as-expected"></a><span data-ttu-id="c94e2-102">Aturan kotak masuk tidak berfungsi seperti yang diharapkan</span><span class="sxs-lookup"><span data-stu-id="c94e2-102">An Inbox rule doesn't work as expected</span></span>

<span data-ttu-id="c94e2-103">Pastikan pengaturan berikut di Outlook di web:</span><span class="sxs-lookup"><span data-stu-id="c94e2-103">Verify the following settings in Outlook on the web:</span></span>

- <span data-ttu-id="c94e2-104">Pesan dapat diarahkan, diteruskan, atau membalas secara otomatis berdasarkan aturan kotak masuk hanya satu kali.</span><span class="sxs-lookup"><span data-stu-id="c94e2-104">A message can be redirected, forwarded, or replied to automatically based on Inbox rules only one time.</span></span> <span data-ttu-id="c94e2-105">Aturan pengarah ulang (aturan kotak masuk atau aturan alur e-mail, juga dikenal sebagai aturan transport) dapat menambahkan maksimal sepuluh Penerima penerusan ke pesan.</span><span class="sxs-lookup"><span data-stu-id="c94e2-105">A redirecting rule (an Inbox rule or mail flow rule, also known as a transport rule) can add a maximum of ten forwarding recipients to a message.</span></span> <span data-ttu-id="c94e2-106">Untuk informasi selengkapnya, lihat [batas aturan jurnal, transportasi, dan kotak masuk](https://docs.microsoft.com/office365/servicedescriptions/exchange-online-service-description/exchange-online-limits).</span><span class="sxs-lookup"><span data-stu-id="c94e2-106">For more information, see [Journal, Transport, and Inbox rule limits](https://docs.microsoft.com/office365/servicedescriptions/exchange-online-service-description/exchange-online-limits).</span></span>

- <span data-ttu-id="c94e2-107">Aturan kotak masuk tidak bekerja pada kotak surat penjurnan alternatif.</span><span class="sxs-lookup"><span data-stu-id="c94e2-107">Inbox rules don't work on the alternate journaling mailbox.</span></span> <span data-ttu-id="c94e2-108">Untuk informasi selengkapnya tentang kotak surat penjurnan alternatif, lihat [kotak surat Penjurnasan alternatif](https://docs.microsoft.com/Exchange/security-and-compliance/journaling/journaling#alternate-journaling-mailbox).</span><span class="sxs-lookup"><span data-stu-id="c94e2-108">For more information about the alternate journaling mailbox, see [Alternate journaling mailbox](https://docs.microsoft.com/Exchange/security-and-compliance/journaling/journaling#alternate-journaling-mailbox).</span></span>

<span data-ttu-id="c94e2-109">Untuk memperbaiki masalah ini, lihat [KB 2829319](https://support.microsoft.com/kb/2829319).</span><span class="sxs-lookup"><span data-stu-id="c94e2-109">To fix these issues, see [KB 2829319](https://support.microsoft.com/kb/2829319).</span></span>

<span data-ttu-id="c94e2-110">Jika masalah sebelumnya tidak berlaku, jalankan laporan diagnostik aturan kotak masuk sebelum Anda laporkan masalah ke dukungan Microsoft:</span><span class="sxs-lookup"><span data-stu-id="c94e2-110">If the previous issues don't apply, run the Inbox rule diagnostic report before you escalate the issue to Microsoft Support:</span></span>

1. <span data-ttu-id="c94e2-111">Buka kotak surat di Outlook di web, dan klik</span><span class="sxs-lookup"><span data-stu-id="c94e2-111">Open the mailbox in Outlook on the web, and click</span></span> <img src='data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABIAAAASCAMAAABhEH5lAAAA51BMVEX6+fj6+fDr+fjK+fj69LRxsuj6+cjY+fi/+fin3ev6+ddMk81HdK5AaatHLn/ntXTrsW5cRmLOk0pAND5KNCl1NCOi3fiGwvjJ3fDBz+F6teFgpdt6stX68c314syTucirtchum8bjz8BQh7/6+b47fbrKtapiian63aFDaaHJuZJiQo36woVabH7ZtHiOQnTHm2wlKmqriWF/cFzVnVTFjlSyeUkrNEmBLkWfaUGsaT67fTrj9Pi19PjO8fiv5vj69OFWm9Pt3aZ1Qo0lNHQ1P2iYTWGOQmHcpV5kRlqvc0mrbERpPzMoEeekAAAAxElEQVQY03WQ5w6CUAyFy3Jv3HsrICoKqLj3fP/nsTcNakjsn9t+bW/OKfyL6iTCc49e/ktuRs2WEhE1U/qgQQfEzGkNyxzVXLdw0ASW+a7BZp3HpJ+cpovUjcv6PYtvSmKj4/SswTMaBgg9FQF5axWysKoson4cGMYCvlEAQDwK7XkZwEVbRBpDPC46ygbAbPl31p4Wvd8nwiRCLnIArJb1ZBD7KFWMkdQLSUVIhowsGaIwzzVHikfVV8lzHPv3OGTfTd4gnRNqGdZ49AAAAABJRU5ErkJggg==' />
 <span data-ttu-id="c94e2-112">**Pengaturan**  >  **Lihat semua pengaturan Outlook**  >  **Surat**  >  **Aturan**.</span><span class="sxs-lookup"><span data-stu-id="c94e2-112">**Settings** > **View all Outlook Settings** > **Mail** > **Rules**.</span></span>

2. <span data-ttu-id="c94e2-113">Di bagian bawah halaman, klik **jika aturan Anda tidak berfungsi, klik di sini untuk membuat laporan diagnostik**.</span><span class="sxs-lookup"><span data-stu-id="c94e2-113">At the bottom of the page, click **If your rules are not working click here to generate a diagnostic report**.</span></span>
