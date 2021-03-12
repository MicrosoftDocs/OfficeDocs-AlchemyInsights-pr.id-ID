---
title: Kumpulan replika
ms.author: v-jmathew
author: v-jmathew
manager: scotv
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9004400"
- "9004395"
- "8265"
- "9276"
ms.openlocfilehash: 3834696ff59b7e96e90a5b660a489003dfa9729c
ms.sourcegitcommit: 581c696ec108184adae9d4bc8f47cb9247131de8
ms.translationtype: MT
ms.contentlocale: id-ID
ms.lasthandoff: 03/10/2021
ms.locfileid: "50714249"
---
# <a name="replica-set"></a><span data-ttu-id="818d4-102">Kumpulan replika</span><span class="sxs-lookup"><span data-stu-id="818d4-102">Replica set</span></span>

<span data-ttu-id="818d4-103">Tambahkan juga disebut sebagai domain terkelola.</span><span class="sxs-lookup"><span data-stu-id="818d4-103">AADDS is also called as the managed domain.</span></span> <span data-ttu-id="818d4-104">Sebenarnya ada dua pengontrol domain yang dijalankan dan dipelihara oleh backend.</span><span class="sxs-lookup"><span data-stu-id="818d4-104">It is actually two domain controllers that are run and maintained by the backend.</span></span> <span data-ttu-id="818d4-105">Dua DCs menyertakan satu DC utama dan satu replikasi DC.</span><span class="sxs-lookup"><span data-stu-id="818d4-105">The two DCs include one main DC and one replication DC.</span></span> <span data-ttu-id="818d4-106">Pencadangan di AADDS (domain terkelola) adalah proses otomatis yang dikelola oleh platform Azure.</span><span class="sxs-lookup"><span data-stu-id="818d4-106">Backups in AADDS (managed domain) are an automated process managed by the Azure platform.</span></span> <span data-ttu-id="818d4-107">Dalam Kejadian masalah dengan domain terkelola Anda, dukungan Azure dapat membantu Anda memulihkan dari cadangan.</span><span class="sxs-lookup"><span data-stu-id="818d4-107">In the event of an issue with your managed domain, Azure support can assist you in restoring from backup.</span></span>

<span data-ttu-id="818d4-108">Anda membuat setiap rangkaian replika dalam jaringan virtual.</span><span class="sxs-lookup"><span data-stu-id="818d4-108">You create each replica set in a virtual network.</span></span> <span data-ttu-id="818d4-109">Setiap jaringan virtual harus dipengpeered ke setiap jaringan virtual lainnya yang menghosting kumpulan replika domain terkelola.</span><span class="sxs-lookup"><span data-stu-id="818d4-109">Each virtual network must be peered to every other virtual network that hosts a managed domain's replica set.</span></span> <span data-ttu-id="818d4-110">Konfigurasi ini membuat topologi jaringan mesh yang mendukung replikasi direktori.</span><span class="sxs-lookup"><span data-stu-id="818d4-110">This configuration creates a mesh network topology that supports directory replication.</span></span> <span data-ttu-id="818d4-111">Jaringan virtual bisa mendukung beberapa kumpulan replika, asalkan setiap rangkaian replika berada dalam subnet virtual berbeda.</span><span class="sxs-lookup"><span data-stu-id="818d4-111">A virtual network can support multiple replica sets, provided that each replica set is in a different virtual subnet.</span></span>

<span data-ttu-id="818d4-112">Untuk detail selengkapnya tentang kumpulan replika, lihat [rangkaian replika konsep](https://docs.microsoft.com/azure/active-directory-domain-services/concepts-replica-sets).</span><span class="sxs-lookup"><span data-stu-id="818d4-112">For more details on Replica set, see [Concepts Replica sets](https://docs.microsoft.com/azure/active-directory-domain-services/concepts-replica-sets).</span></span>
