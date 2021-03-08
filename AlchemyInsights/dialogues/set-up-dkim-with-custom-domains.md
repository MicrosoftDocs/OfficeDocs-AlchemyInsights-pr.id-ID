---
title: Menyiapkan DKIM dengan domain kustom
ms.author: v-smandalika
author: v-smandalika
manager: dansimp
ms.date: 02/22/2021
audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9002531"
- "7375"
ms.openlocfilehash: c448956f0dad0738f4de7507ec4686c738a90a55
ms.sourcegitcommit: 78fe9f33438cb0c19f0dab31253b5853b73f4f47
ms.translationtype: MT
ms.contentlocale: id-ID
ms.lasthandoff: 03/05/2021
ms.locfileid: "50524273"
---
# <a name="set-up-dkim-with-custom-domains"></a><span data-ttu-id="d1567-102">Menyiapkan DKIM dengan domain kustom</span><span class="sxs-lookup"><span data-stu-id="d1567-102">Set up DKIM with custom domains</span></span>

<span data-ttu-id="d1567-103">Anda harus menerbitkan dua catatan CNAME untuk setiap domain kustom di DNS.</span><span class="sxs-lookup"><span data-stu-id="d1567-103">You must publish two CNAME records for each custom domain in DNS.</span></span> <span data-ttu-id="d1567-104">Untuk melakukan ini, gunakan format berikut:</span><span class="sxs-lookup"><span data-stu-id="d1567-104">To do this, use the following format:</span></span>

```console
Host name:            selector1._domainkey
Points to address or value:    selector1-<domainGUID>._domainkey.<initialDomain>
TTL:                3600

Host name:            selector2._domainkey
Points to address or value:    selector2-<domainGUID>._domainkey.<initialDomain>
TTL:                3600
```
> [!NOTE]
> <span data-ttu-id="d1567-105">**Domainguid** adalah teks di sebelah kiri **. mail.Protection.Outlook.com** dalam catatan MX yang dikustomisasi untuk domain kustom (misalnya, contoso-com untuk domain **contoso.com**).</span><span class="sxs-lookup"><span data-stu-id="d1567-105">**DomainGUID** is the text to the left of **.mail.protection.outlook.com** in the customized MX record for the custom domain (for example, contoso-com for the domain **contoso.com**).</span></span> <span data-ttu-id="d1567-106">**Initialdomain** adalah domain yang Anda gunakan saat mendaftar untuk Office 365 (misalnya, **contoso.onmicrosoft.com**).</span><span class="sxs-lookup"><span data-stu-id="d1567-106">**InitialDomain** is the domain you used when you signed up for Office 365 (for example, **contoso.onmicrosoft.com**).</span></span>

<span data-ttu-id="d1567-107">Untuk informasi selengkapnya tentang catatan DNS, lihat [membuat catatan DNS di penyedia hosting DNS untuk Office 365](https://docs.microsoft.com/microsoft-365/admin/get-help-with-domains/create-dns-records-at-any-dns-hosting-provider).</span><span class="sxs-lookup"><span data-stu-id="d1567-107">For more information about DNS records, see [Create DNS records at any DNS hosting provider for Office 365](https://docs.microsoft.com/microsoft-365/admin/get-help-with-domains/create-dns-records-at-any-dns-hosting-provider).</span></span>