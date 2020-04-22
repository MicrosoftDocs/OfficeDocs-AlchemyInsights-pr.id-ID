---
title: Error saat mengirim email yang diblokir oleh SpamHaus
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 04/21/2020
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "255"
- "3100003"
ms.assetid: fa98ab4a-92eb-45e9-8d57-ad10fb123042
ms.openlocfilehash: 3ff4f7a155fe74f5b42a1bd43e67ef0a751d7fbd
ms.sourcegitcommit: 55eff703a17e500681d8fa6a87eb067019ade3cc
ms.translationtype: MT
ms.contentlocale: id-ID
ms.lasthandoff: 04/22/2020
ms.locfileid: "43714261"
---
# <a name="error-sending-email-client-host-blocked-using-spamhaus"></a><span data-ttu-id="9aa8f-102">Kesalahan pengiriman email: host klien diblokir menggunakan SpamHaus</span><span class="sxs-lookup"><span data-stu-id="9aa8f-102">Error sending email: Client host blocked using Spamhaus</span></span>

<span data-ttu-id="9aa8f-103">Alamat IP yang mengirim pesan adalah pada daftar blokir milik [SpamHaus](https://go.microsoft.com/fwlink/p/?linkid=123245).</span><span class="sxs-lookup"><span data-stu-id="9aa8f-103">The IP address that sent the message is on a block list owned by [Spamhaus](https://go.microsoft.com/fwlink/p/?linkid=123245).</span></span> <span data-ttu-id="9aa8f-104">Alasan diblokir oleh SpamHaus termasuk akun yang dikompromikan, dikompromikan mesin berbagi alamat IP publik, dan Internet Service Provider (ISP) kebijakan.</span><span class="sxs-lookup"><span data-stu-id="9aa8f-104">Reasons for being blocked by Spamhaus include compromised accounts, compromised machines sharing a public IP address, and Internet Service Provider (ISP) policies.</span></span> <span data-ttu-id="9aa8f-105">Kemungkinan perbaikan adalah:</span><span class="sxs-lookup"><span data-stu-id="9aa8f-105">Possible fixes are:</span></span>
  
- <span data-ttu-id="9aa8f-106">Untuk pesan masuk diblokir di mana Anda mengontrol server email sumber, Anda perlu menentukan penyebabnya dan menghapus blok dari situs web SpamHaus.</span><span class="sxs-lookup"><span data-stu-id="9aa8f-106">For blocked inbound messages where you control the source email server, you need to determine the cause and remove the block from the Spamhaus website.</span></span>

- <span data-ttu-id="9aa8f-107">Untuk pesan masuk diblokir di mana alamat IP sumber milik orang lain, pemilik alamat harus menghapus blok dari situs web SpamHaus.</span><span class="sxs-lookup"><span data-stu-id="9aa8f-107">For blocked inbound messages where the source IP address belongs to someone else, the address owner needs to remove the block from the Spamhaus website.</span></span> <span data-ttu-id="9aa8f-108">Jika alamat IP di kebijakan blok daftar (PBL), pemilik dapat menetapkan alamat IP statis yang berbeda atau menghapus alamat dari PBL.</span><span class="sxs-lookup"><span data-stu-id="9aa8f-108">If the IP address is on the Policy Block List (PBL), the owner can assign a different static IP address or remove the address from the PBL.</span></span>

- <span data-ttu-id="9aa8f-109">Untuk diblokir pesan keluar dari domain Anda terhubung ke Microsoft, Anda dapat menerima galat ini jika pesan diarahkan melalui layanan pihak ke-3.</span><span class="sxs-lookup"><span data-stu-id="9aa8f-109">For blocked outbound messages from your domain connected to Microsoft, you can receive this error if the messages are routed through a 3rd party service.</span></span> <span data-ttu-id="9aa8f-110">Anda dapat menggunakan alat pencarian WHOIS untuk menemukan pemilik alamat IP yang diblokir.</span><span class="sxs-lookup"><span data-stu-id="9aa8f-110">You can use a WHOIS lookup tool to find the blocked IP address owner.</span></span>
