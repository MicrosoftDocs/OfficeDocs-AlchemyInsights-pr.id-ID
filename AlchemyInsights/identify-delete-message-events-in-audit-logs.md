---
title: Mengidentifikasi Hapus pesan peristiwa di log audit
ms.author: chrisda
author: chrisda
manager: serdars
ms.date: ''
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom: 1370
ms.assetid: ''
ms.openlocfilehash: 93f8a192af6e689e2b2d04013f35b8da2b69e607
ms.sourcegitcommit: ffe2f489b1ac3aae62aa784c959da6a41c3261eb
ms.translationtype: MT
ms.contentlocale: id-ID
ms.lasthandoff: 04/17/2019
ms.locfileid: "31909321"
---
# <a name="audit-logs-for-deleted-email-messages"></a>Log audit untuk pesan dihapus email

Mulai Januari 2019, Microsoft adalah menyalakan audit kotak pesan log secara default. Jika tidak, untuk meninjau Hapus pesan acara untuk pengguna tertentu, Anda harus secara manual mengaktifkan tindakan delete untuk audit. Jika kotak pesan audit penebangan kayu sudah diaktifkan untuk organisasi Anda atau untuk pengguna tertentu, ikuti langkah berikut.

1. Masuk ke [Kantor 365 keamanan & Compliance Center](https://protection.office.com/)

2. Klik **Cari dan penyelidikan** dan pilih **Cari Log Audit**.

3. Pilih rentang tanggal di bidang **tanggal mulai** dan **tanggal akhir** . Tentukan nama pengguna untuk pengguna yang ingin menyelidiki (pengguna yang dihapus). Di bidang **kegiatan** , pilih **pesan dihapus dari folder Item dihapus** dan **pesan dipindahkan ke folder Item dihapus**.

4. Klik **Cari**.

Hasil, pilih catatan audit. Di flyout rincian, klik **Informasi selengkapnya**. Informasi tambahan tentang item yang dihapus (misalnya, baris subjek dan lokasi item ketika dihapus) dipajangkan di bidang **AffectedItems** . Properti **ClientInfoString** akan menunjukkan jika penghapusan terjadi di Outlook, Outlook pada web (sebelumnya dikenal sebagai Outlook Web App), atau perangkat lain.

Untuk informasi lebih lanjut, lihat [menentukan yang mengatur email forwarding untuk kotak pesan](https://docs.microsoft.com/office365/securitycompliance/auditing-troubleshooting-scenarios#determining-if-a-user-deleted-email-items).

**Catatan**: Anda tidak dapat mengambil item yang dihapus menggunakan fitur log audit. Untuk mengambil pesan dihapus di Outlook di web, lihat [memulihkan item di Outlook Web App yang dihapus](https://support.office.com/article/C3D8FC15-EEEF-4F1C-81DF-E27964B7EDD4).