---
title: Mengonfigurasi enkripsi pesan untuk lingkungan hibrid
ms.author: v-smandalika
author: v-smandalika
manager: dansimp
ms.date: 02/24/2021
audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9000078"
- "7342"
ms.openlocfilehash: 22c2468b7639680b447b6464431a79b69f7198c3
ms.sourcegitcommit: 6312ee31561db36104f32282d019d069ede69174
ms.translationtype: MT
ms.contentlocale: id-ID
ms.lasthandoff: 03/11/2021
ms.locfileid: "50745399"
---
# <a name="configure-message-encryption-for-a-hybrid-environment"></a><span data-ttu-id="9c601-102">Mengonfigurasi enkripsi pesan untuk lingkungan hibrid</span><span class="sxs-lookup"><span data-stu-id="9c601-102">Configure message encryption for a hybrid environment</span></span>

<span data-ttu-id="9c601-103">Untuk lingkungan Exchange hibrid, pengguna lokal dapat mengirim email terenkripsi menggunakan enkripsi pesan Office (OME) hanya jika email dirutekan melalui Exchange Online.</span><span class="sxs-lookup"><span data-stu-id="9c601-103">For hybrid Exchange environments, on-premises users can send encrypted email using Office Message Encryption (OME) only if email is routed through Exchange Online.</span></span>

<span data-ttu-id="9c601-104">Untuk mengenkripsi email menggunakan OME, lakukan langkah-langkah berikut:</span><span class="sxs-lookup"><span data-stu-id="9c601-104">To encrypt emails using OME, perform the following steps:</span></span>

1. <span data-ttu-id="9c601-105">Gunakan [panduan konfigurasi hibrid](https://docs.microsoft.com/Exchange/hybrid-configuration-wizard) untuk menyiapkan lingkungan hibrid Anda.</span><span class="sxs-lookup"><span data-stu-id="9c601-105">Use the [Hybrid Configuration wizard](https://docs.microsoft.com/Exchange/hybrid-configuration-wizard) to set up your hybrid environment.</span></span> <span data-ttu-id="9c601-106">Tidak ada langkah khusus yang diperlukan untuk menyetel enkripsi.</span><span class="sxs-lookup"><span data-stu-id="9c601-106">No special steps are required for setting up encryption.</span></span>
2. <span data-ttu-id="9c601-107">[Siapkan aturan aliran email untuk enkripsi](https://docs.microsoft.com/microsoft-365/compliance/define-mail-flow-rules-to-encrypt-email) seperti biasa.</span><span class="sxs-lookup"><span data-stu-id="9c601-107">[Set up your mail flow rules for encryption](https://docs.microsoft.com/microsoft-365/compliance/define-mail-flow-rules-to-encrypt-email) like you normally would.</span></span>

