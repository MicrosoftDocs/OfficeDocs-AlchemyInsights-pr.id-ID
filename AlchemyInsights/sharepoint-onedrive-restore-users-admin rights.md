---
title: Pemecahan masalah akses pesan yang ditolak ke OneDrive untuk situs bisnis
ms.author: pebaum
author: pebaum
manager: pamgreen
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.assetid: cebb7a4a-33e1-474e-a5d0-dbd02a80b1e9
ms.openlocfilehash: 9001cf0b7d9f1f05a2ecedca2c3137dd1b8a1c38
ms.sourcegitcommit: c6692ce0fa1358ec3529e59ca0ecdfdea4cdc759
ms.translationtype: MT
ms.contentlocale: id-ID
ms.lasthandoff: 09/14/2020
ms.locfileid: "47670619"
---
# <a name="troubleshooting-access-denied-messages-to-onedrive-for-business-sites"></a><span data-ttu-id="16375-102">Pemecahan masalah akses pesan yang ditolak ke OneDrive untuk situs bisnis</span><span class="sxs-lookup"><span data-stu-id="16375-102">Troubleshooting Access denied messages to OneDrive for Business sites</span></span>

<span data-ttu-id="16375-103">Masalah ini paling sering terjadi ketika pengguna dihapus dan dibuat ulang dengan nama prinsip pengguna (UPN) yang sama.</span><span class="sxs-lookup"><span data-stu-id="16375-103">This issue most frequently occurs when a user is deleted and re-created with the same user principal name (UPN).</span></span> <span data-ttu-id="16375-104">Akun baru dibuat menggunakan nilai PUID (ID unik paspor) yang berbeda.</span><span class="sxs-lookup"><span data-stu-id="16375-104">The new account is created by using a different PUID (Passport Unique ID) value.</span></span> <span data-ttu-id="16375-105">Saat pengguna mencoba mengakses kumpulan situs atau OneDrive mereka, pengguna tersebut memiliki PUID yang salah.</span><span class="sxs-lookup"><span data-stu-id="16375-105">When the user tries to access a site collection or their OneDrive, the user has an incorrect PUID.</span></span> <span data-ttu-id="16375-106">Skenario kedua melibatkan sinkronisasi direktori dengan unit organisasi direktori aktif (OU).</span><span class="sxs-lookup"><span data-stu-id="16375-106">A second scenario involves directory synchronization with an Active Directory organizational unit (OU).</span></span> <span data-ttu-id="16375-107">Jika pengguna sudah masuk ke SharePoint, lalu dipindahkan ke OU berbeda dan resynced dengan SharePoint, mereka mungkin mengalami masalah ini.</span><span class="sxs-lookup"><span data-stu-id="16375-107">If users have already signed in to SharePoint, and then are moved to a different OU and resynced with SharePoint, they may experience this problem.</span></span>

1. <span data-ttu-id="16375-108">Untuk mengatasi masalah ini, Anda harus memulihkan UPN asli dengan langkah-langkah dalam artikel, [memulihkan pengguna di Microsoft 365](https://docs.microsoft.com/microsoft-365/admin/add-users/restore-user).</span><span class="sxs-lookup"><span data-stu-id="16375-108">To resolve this issue you should restore the original UPN with the steps in the article, [Restore a user in Microsoft 365](https://docs.microsoft.com/microsoft-365/admin/add-users/restore-user).</span></span>
2. <span data-ttu-id="16375-109">Jika Anda tidak bisa memulihkan pengguna asli, Anda harus menghapus pengguna lama dari situs OneDrive menggunakan langkah-langkah ini, [menghapus pengguna dari daftar Info pengguna]().</span><span class="sxs-lookup"><span data-stu-id="16375-109">If you cannot restore the original user you should remove the old user from the OneDrive site using these steps, [Remove a user from the user info list]().</span></span> 
3. <span data-ttu-id="16375-110">Setelah ini selesai, Anda dapat memverifikasi bahwa pengguna memiliki hak admin ke situs OneDrive dengan mengikuti langkah-langkah untuk [menambahkan admin untuk onedrive pengguna](https://docs.microsoft.com/sharepoint/manage-user-profiles)</span><span class="sxs-lookup"><span data-stu-id="16375-110">After this is done, you can verify the user has admin rights to the OneDrive site by following the steps to [Add admin's for a user's OneDrive](https://docs.microsoft.com/sharepoint/manage-user-profiles)</span></span>

<span data-ttu-id="16375-111">Untuk informasi selengkapnya tentang tingkat izin, lihat artikel, [memahami tingkat izin di SharePoint](https://docs.microsoft.com/sharepoint/understanding-permission-levels).</span><span class="sxs-lookup"><span data-stu-id="16375-111">For more information on permission levels, see the article, [Understanding permission levels in SharePoint](https://docs.microsoft.com/sharepoint/understanding-permission-levels).</span></span>
