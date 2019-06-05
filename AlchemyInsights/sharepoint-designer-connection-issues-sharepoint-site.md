---
title: Tingkat izin SharePoint Online
ms.author: kirks
author: Techwriter40
manager: pamgreen
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom: ''
ms.assetid: f2b1b6b4-10c9-4e83-b9cb-529a0b8a3c55
ms.openlocfilehash: 7451cfe957545537298f57feb5b47bd6d43cddbf
ms.sourcegitcommit: 6d341637dbb14e90726a1ce1d68f077ace9bb765
ms.translationtype: MT
ms.contentlocale: id-ID
ms.lasthandoff: 06/04/2019
ms.locfileid: "34716895"
---
# <a name="sharepoint-designer-connection-issues"></a>Masalah sambungan SharePoint Designer 

<p>Jika SharePoint Designer mengalami masalah sambungan ke situs SharePoint, silahkan mencoba solusi umum berikut.</p> <p><strong>Langkah 1:</strong> <strong>Memverifikasi SharePoint Designer diperbarui&nbsp; </strong></p> <ul> <li><a href="https://www.microsoft.com/en-us/download/details.aspx?id=35491">SharePoint Designer 2013</a></li> <li><a href="https://support.microsoft.com/en-us/help/2817441/description-of-microsoft-sharepoint-designer-2013-service-pack-1-sp1">SharePoint Designer Paket Layanan 1 (SP1)</a></li> <li><a href="https://support.microsoft.com/en-us/help/3114721/august-2-2016-update-for-sharepoint-designer-2013-kb3114721">Pembaruan untuk SharePoint Designer 2013 (KB3114721)</a></li> </ul> <p><strong>Langkah 2:</strong> <strong>Menghapus file cache lokal</strong>&nbsp;</p> <ol> <li style="font-weight: 400;">Dekat SharePoint desainer 2013.&nbsp;</li> <li style="font-weight: 400;">Pada komputer lokal, browse ke folder berikut untuk menghapus cache file.&nbsp;</li> <li style="font-weight: 400;">Klik <strong>mulai -&gt; menjalankan</strong> dan menghapus semua file yang ditemukan di bawah masing-masing di bawah lokasi.&nbsp;<br /><br />%APPDATA%\Microsoft\Web server Extensions\Cache<br />%APPDATA%\Microsoft\SharePoint Designer\ProxyAssemblyCache<br />%USERPROFILE%\AppData\Local\Microsoft\WebsiteCache</li> <li style="font-weight: 400;">Buka SharePoint desainer 2013 dan masukkan account lagi untuk melihat apakah ia bekerja.</li> </ol> <p><strong>Langkah 3:</strong> <a href="https://docs.microsoft.com/en-us/office365/admin/security-and-compliance/enable-modern-authentication?redirectSourcePath=%252fen-us%252farticle%252fEnable-Modern-Authentication-for-Office-2013-on-Windows-devices-7dc1c01a-090f-4971-9677-f1b192d6c910&amp;view=o365-worldwide"> <strong>Mengaktifkan otentikasi Modern untuk kantor 2013 pada perangkat Windows</strong></a>&nbsp;</p> <p><strong>Langkah 4:</strong> <strong>Administrator akan perlu untuk membolehkan Custom Script untuk memungkinkan koneksi SharePoint Designer</strong>.</p> <p>Untuk langkah-langkah rinci, contoh dan pertimbangan Lihat <a href="https://docs.microsoft.com/en-us/sharepoint/allow-or-prevent-custom-script">Bolehkan atau mencegah script kustom</a>.&nbsp;</p>


