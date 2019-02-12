---
title: Menginstal office pada Server Terminal - tanpa izin
ms.author: pebaum
author: pebaum
ms.date: 12/17/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: b1074430-489e-4d49-bfe4-3d8783d8073c
ms.openlocfilehash: 971edd9c064b448446ba16361e99df4a2291c14f
ms.sourcegitcommit: dd43cc0a9470f98b8ef2a3787c823801d674c666
ms.translationtype: MT
ms.contentlocale: id-ID
ms.lasthandoff: 02/12/2019
ms.locfileid: "29918978"
---
# <a name="installing-office-on-a-terminal-server"></a>Menginstal Office pada Terminal Server

Untuk menggunakan kantor 365 ProPlus pada Windows Server menggunakan Remote Desktop Services (RDS), sebelumnya bernama Layanan Terminal:
  
- Anda harus memiliki rencana Office 365 yang mencakup kantor 365 ProPlus, seperti kantor 365 Enterprise E3 atau Enterprise E5. Office 365 bisnis dan kantor 365 bisnis Premium rencana tidak termasuk kantor 365 ProPlus.
    
- Anda perlu untuk mengaktifkan [aktivasi komputer bersama](https://docs.microsoft.com/DeployOffice/overview-of-shared-computer-activation-for-office-365-proplus).
    
Jika Anda ingin menginstal Office 365 ProPlus pada RDS dari portal Office 365, ** *yang menggunakan pengaturan default instalasi* **, ikuti langkah berikut: 
  
1. Periksa apa rencana Office 365 yang Anda miliki. [Belajar bagaimana](https://docs.microsoft.com/office365/admin/admin-overview/what-subscription-do-i-have)
    
2. Jika perlu, beralih ke Office 365 berbeda berencana. [Belajar bagaimana](https://docs.microsoft.com/office365/admin/subscriptions-and-billing/switch-to-a-different-plan)
    
3. Jika kantor sudah diinstal pada server RDS menggunakan rencana Office 365 lain, uninstall. Sebagai contoh, dengan pergi ke Control Panel \> Uninstall sebuah program. Uninstall menggunakan [Microsoft Support dan asisten pemulihan](https://aka.ms/SARA-OfficeUninstall-Alchemy) jika Anda menjalankan ke masalah. 
    
4. Di RDS server, masuk ke portal 365 kantor dengan administrator account dan [menginstal Office 365 ProPlus](https://portal.office.com/OLS/MySoftware.aspx).
    
5. Setelah kantor diinstal, ** *tidak membuka atau masuk* ** untuk aplikasi kantor. 
    
6. Di RDS server, mengaktifkan aktivasi komputer bersama dengan mengedit registri dengan mengikuti langkah berikut:
    
1. Klik kanan tombol Windows di sudut kiri bawah layar Anda, lalu pilih Jalankan. Di kotak buka, ketikkan **regedit**, dan kemudian pilih OK. 
    
2. Pilih Ya saat diminta agar Registry Editor untuk membuat perubahan ke perangkat Anda.
    
3. Di Penyunting registri, menambahkan nilai string dari **SharedComputerLicensing** dengan suasana 1 di bawah HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft \Office\ClickToRun\Configuration. 
    
7. Di RDS server, ** *masuk sebagai pengguna akhir* ** dan [memverifikasi bahwa komputer bersama aktivasi diaktifkan untuk Office 365 ProPlus](https://docs.microsoft.com/DeployOffice/troubleshoot-issues-with-shared-computer-activation-for-office-365-proplus#verify-that-activation-for-office-365-proplus-succeeded).
    
Untuk detail lebih lanjut tentang prasyarat, setup instruksi dan panduan instalasi yang disesuaikan dengan menggunakan alat penyebaran kantor, silakan lihat [Menyebarkan kantor 365 ProPlus dengan menggunakan Remote Desktop Services](https://docs.microsoft.com/DeployOffice/deploy-office-365-proplus-by-using-remote-desktop-services).
  
Untuk memperbaiki kesalahan yang berhubungan dengan komputer bersama aktivasi, lihat [mengatasi masalah masalah dengan komputer bersama aktivasi untuk Office 365 ProPlus](https://docs.microsoft.com/DeployOffice/troubleshoot-issues-with-shared-computer-activation-for-office-365-proplus).
  
