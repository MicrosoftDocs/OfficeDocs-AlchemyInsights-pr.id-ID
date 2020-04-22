---
title: 902 (sinkronisasi kesalahan karena duplikat objek)
ms.author: chrisda
author: chrisda
manager: dansimp
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom: 902
ms.assetid: 9d9277a5-c825-4512-8d54-7138b2ee0c40
ms.openlocfilehash: 6ea833e0c4aebe72bc5c02e3dc10c1edc4136dcc
ms.sourcegitcommit: 631cbb5f03e5371f0995e976536d24e9d13746c3
ms.translationtype: MT
ms.contentlocale: id-ID
ms.lasthandoff: 04/22/2020
ms.locfileid: "43767131"
---
# <a name="sync-errors-due-to-duplicate-objects"></a><span data-ttu-id="fdbf9-102">Galat sinkronisasi karena duplikat objek</span><span class="sxs-lookup"><span data-stu-id="fdbf9-102">Sync errors due to duplicate objects</span></span>

<span data-ttu-id="fdbf9-103">Anda mungkin menerima salah satu pesan galat berikut saat sinkronisasi direktori selesai di Microsoft 365:</span><span class="sxs-lookup"><span data-stu-id="fdbf9-103">You might receive one of the following error messages when directory synchronization finishes in Microsoft 365:</span></span>

- <span data-ttu-id="fdbf9-104">Tidak dapat memutakhirkan objek ini di Microsoft Online Services karena atribut berikut ini yang berkaitan dengan objek ini memiliki nilai yang sudah mungkin terkait dengan objek lain di direktori lokal Anda.</span><span class="sxs-lookup"><span data-stu-id="fdbf9-104">Unable to update this object in Microsoft Online Services because the following attributes associated with this object have values that may already be associated with another object in your local directory.</span></span>

- <span data-ttu-id="fdbf9-105">Objek disinkronkan dengan alamat proksi yang sama yang sudah ada di direktori Microsoft Online Services.</span><span class="sxs-lookup"><span data-stu-id="fdbf9-105">A synchronized object with the same proxy address already exists in your Microsoft Online Services directory.</span></span>

- <span data-ttu-id="fdbf9-106">Tidak dapat memutakhirkan objek ini karena atribut berikut ini yang berkaitan dengan objek ini memiliki nilai yang sudah mungkin terkait dengan objek lain di layanan direktori lokal Anda: UserPrincipalName.</span><span class="sxs-lookup"><span data-stu-id="fdbf9-106">Unable to update this object because the following attributes associated with this object have values that may already be associated with another object in your local directory services: UserPrincipalName.</span></span>

<span data-ttu-id="fdbf9-107">Untuk mengidentifikasi dan memperbaiki masalah, Unduh dan jalankan [alat remediasi galat DirSync idfix](https://www.microsoft.com/download/details.aspx?id=36832).</span><span class="sxs-lookup"><span data-stu-id="fdbf9-107">To identify and fix the issue, download and run the [IdFix DirSync Error Remediation Tool](https://www.microsoft.com/download/details.aspx?id=36832).</span></span>

<span data-ttu-id="fdbf9-108">Untuk informasi selengkapnya, lihat [KB2647098](https://support.microsoft.com/help/2647098/duplicate-or-invalid-attributes-prevent-directory-synchronization-in-o).</span><span class="sxs-lookup"><span data-stu-id="fdbf9-108">For more information, see [KB2647098](https://support.microsoft.com/help/2647098/duplicate-or-invalid-attributes-prevent-directory-synchronization-in-o).</span></span>
