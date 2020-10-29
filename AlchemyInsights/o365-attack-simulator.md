---
title: Simulator serangan 2681 di Microsoft 365
ms.author: chrisda
author: chrisda
manager: dansimp
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "2681"
ms.assetid: ''
ms.openlocfilehash: 7b48abea3400e3565f2ba33c97e24e5b9923eb3b
ms.sourcegitcommit: 4caf5e6c2fee2903ccaf92cfc9006eb580faa7ba
ms.translationtype: MT
ms.contentlocale: id-ID
ms.lasthandoff: 10/29/2020
ms.locfileid: "48801554"
---
# <a name="attack-simulator-in-microsoft-365"></a><span data-ttu-id="d3a1b-102">Serangan Simulator di Microsoft 365</span><span class="sxs-lookup"><span data-stu-id="d3a1b-102">Attack Simulator in Microsoft 365</span></span>

- <span data-ttu-id="d3a1b-103">Apakah Anda kehilangan serangan Simulator?</span><span class="sxs-lookup"><span data-stu-id="d3a1b-103">Are you missing Attack Simulator?</span></span> <span data-ttu-id="d3a1b-104">Simulator serangan memerlukan **Microsoft Defender untuk office 365 paket 2 (paket ATP 2)** atau **Office 365 Enterprise E5** .</span><span class="sxs-lookup"><span data-stu-id="d3a1b-104">Attack Simulator requires **Microsoft Defender for Office 365 Plan 2 (ATP Plan 2)** or **Office 365 Enterprise E5** .</span></span> <span data-ttu-id="d3a1b-105">Simulator serangan **tidak** disertakan dalam Microsoft Defender untuk Office 365 paket 1 (paket ATP 1), Office 365 Enterprise E3, atau aplikasi Microsoft 365 untuk langganan bisnis.</span><span class="sxs-lookup"><span data-stu-id="d3a1b-105">Attack Simulator is **not** included in Microsoft Defender for Office 365 Plan 1 (ATP Plan 1), Office 365 Enterprise E3, or any Microsoft 365 Apps for business subscriptions.</span></span>

- <span data-ttu-id="d3a1b-106">Akun yang Anda gunakan untuk meluncurkan serangan simulasi memerlukan izin administrator global atau administrator keamanan dan multi-Factor Authentication (MFA).</span><span class="sxs-lookup"><span data-stu-id="d3a1b-106">The account you use to launch simulated attacks requires global administrator or security administrator permissions and multi-factor authentication (MFA).</span></span> <span data-ttu-id="d3a1b-107">Untuk informasi selengkapnya tentang persyaratan serangan Simulator, lihat [topik ini](https://docs.microsoft.com/microsoft-365/security/office-365-security/attack-simulator).</span><span class="sxs-lookup"><span data-stu-id="d3a1b-107">For more information about Attack Simulator requirements, see [this topic](https://docs.microsoft.com/microsoft-365/security/office-365-security/attack-simulator).</span></span>

- <span data-ttu-id="d3a1b-108">Hal penting yang perlu diketahui tentang simulasi serangan **kata sandi Brute Force** :</span><span class="sxs-lookup"><span data-stu-id="d3a1b-108">Important things to know about **Brute Force Password** attack simulations:</span></span>

  - <span data-ttu-id="d3a1b-109">Jika akun target telah diaktifkan MFA dan kata sandinya sudah benar, akun tidak akan terlihat seperti dikompromikan (faktor autentikasi kedua tidak akan selesai).</span><span class="sxs-lookup"><span data-stu-id="d3a1b-109">If the target account has MFA enabled and the password was guessed correctly, the account will not show as compromised (the second authentication factor will be incomplete).</span></span>

  - <span data-ttu-id="d3a1b-110">File kata sandi tidak boleh lebih besar dari 10 MB.</span><span class="sxs-lookup"><span data-stu-id="d3a1b-110">The password file can't be larger than 10 MB.</span></span> <span data-ttu-id="d3a1b-111">Gunakan satu kata sandi per baris, dan sertakan baris kosong (carriage return) setelah kata sandi terakhir dalam daftar.</span><span class="sxs-lookup"><span data-stu-id="d3a1b-111">Use one password per line, and include a blank line (carriage return) after the last password in the list.</span></span>

- <span data-ttu-id="d3a1b-112">Hal penting yang perlu diketahui tentang simulasi lampirkan **Pengelabuan** :</span><span class="sxs-lookup"><span data-stu-id="d3a1b-112">Important things to know about **Spear Phishing** attach simulations:</span></span>

  - <span data-ttu-id="d3a1b-113">Dengan desain, Anda tidak dapat memberikan nilai kustom untuk **URL server login Pengelabuan** .</span><span class="sxs-lookup"><span data-stu-id="d3a1b-113">By design, you can't provide a custom value for **Phishing login server URL** .</span></span>

  - <span data-ttu-id="d3a1b-114">Jika Penerima menggunakan [Add-in Aktifkan pesan laporan](https://docs.microsoft.com/microsoft-365/security/office-365-security/enable-the-report-message-add-in) untuk melaporkan pesan sebagai Pengelabuan, Anda mungkin tidak menerima pemberitahuan untuk pesan (karena ini adalah serangan simulasi).</span><span class="sxs-lookup"><span data-stu-id="d3a1b-114">If a recipient uses the [Enable the Report Message add-in](https://docs.microsoft.com/microsoft-365/security/office-365-security/enable-the-report-message-add-in) to report the message as phishing, you might not receive alerts for the message (because this is a simulated attack).</span></span>

- <span data-ttu-id="d3a1b-115">Laporan: setelah serangan simulasi selesai, Anda bisa mengklik **detail serangan** untuk melihat laporan.</span><span class="sxs-lookup"><span data-stu-id="d3a1b-115">Reports: After the simulated attack is complete, you can click **Attack Details** to see the report.</span></span>

- <span data-ttu-id="d3a1b-116">Untuk instruksi mendetail dan fitur baru dalam simulator serangan, lihat [Attack Simulator di Microsoft 365](https://docs.microsoft.com/microsoft-365/security/office-365-security/attack-simulator).</span><span class="sxs-lookup"><span data-stu-id="d3a1b-116">For detailed instructions and new features in Attack Simulator, see [Attack Simulator in Microsoft 365](https://docs.microsoft.com/microsoft-365/security/office-365-security/attack-simulator).</span></span>
