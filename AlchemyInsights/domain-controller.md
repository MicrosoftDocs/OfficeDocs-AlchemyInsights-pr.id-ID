---
title: Pengontrol domain
ms.author: v-smandalika
author: v-smandalika
manager: dansimp
ms.date: 01/17/2021
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom:
- "7909"
- "9003233"
ms.openlocfilehash: d4cbe80c3e8f0ce32fcbe89e852f24efd6f50575
ms.sourcegitcommit: 6d02eb533fd74199af6b20f714b3720991da2c4a
ms.translationtype: MT
ms.contentlocale: id-ID
ms.lasthandoff: 01/18/2021
ms.locfileid: "49901026"
---
# <a name="domain-controller"></a><span data-ttu-id="cf7ce-102">Pengontrol domain</span><span class="sxs-lookup"><span data-stu-id="cf7ce-102">Domain controller</span></span>

<span data-ttu-id="cf7ce-103">**Tidak dapat mengaktifkan AAD-DS atau Deployment gagal**</span><span class="sxs-lookup"><span data-stu-id="cf7ce-103">**Unable to enable AAD-DS or deployment is failing**</span></span>

<span data-ttu-id="cf7ce-104">Untuk mengatasi masalah layanan domain Azure AD (AAD-DS) yang tidak diaktifkan atau gagal untuk disebarkan, lakukan langkah-langkah berikut:</span><span class="sxs-lookup"><span data-stu-id="cf7ce-104">To solve the issue of Azure AD domain service (AAD-DS) not being enabled or failing to be deployed, perform the following steps:</span></span>

1. <span data-ttu-id="cf7ce-105">Jika Anda menggunakan jaringan virtual yang sudah ada, periksa NSG Anda untuk aturan yang diperlukan untuk menyinkronkan Port dalam AAD-DS di portal https://aka.ms/aadds-networking .</span><span class="sxs-lookup"><span data-stu-id="cf7ce-105">If you are using an already existing virtual network, check your NSG for rules that block ports needed to synchronize in AAD-DS in the portal https://aka.ms/aadds-networking.</span></span>
2. <span data-ttu-id="cf7ce-106">Periksa untuk melihat apakah pesan kesalahan Anda dijawab dalam panduan pemecahan masalah yang tersedia di  https://aka.ms/aadds-troubleshoot-enable .</span><span class="sxs-lookup"><span data-stu-id="cf7ce-106">Check to see if your error message is answered in this troubleshooting guide that is available in  https://aka.ms/aadds-troubleshoot-enable.</span></span>
3. <span data-ttu-id="cf7ce-107">Cobalah menyebarkan layanan domain Azure AD di jaringan virtual baru.</span><span class="sxs-lookup"><span data-stu-id="cf7ce-107">Try deploying Azure AD Domain Services in a new virtual network.</span></span>
4. <span data-ttu-id="cf7ce-108">Ikuti panduan memulai tentang cara menyebarkan AAD-DS, yang tersedia di [tutorial untuk membuat layanan domain AZURE AD](https://docs.microsoft.com/azure/active-directory-domain-services/tutorial-create-instance).</span><span class="sxs-lookup"><span data-stu-id="cf7ce-108">Follow the Getting Started guide on how to deploy AAD-DS, which is available at [Tutorial to Create Azure AD Domain Services](https://docs.microsoft.com/azure/active-directory-domain-services/tutorial-create-instance).</span></span>
5. <span data-ttu-id="cf7ce-109">Jika Anda mengalami masalah dalam menyebarkan layanan domain Azure AD, lihat [memecahkan masalah layanan domain AZURE AD](https://docs.microsoft.com/azure/active-directory-domain-services/troubleshoot) untuk mengatasi kesalahan umum untuk membantu Anda menyelesaikan pekerjaan.</span><span class="sxs-lookup"><span data-stu-id="cf7ce-109">If you are having issues with Deploying Azure AD Domain Services, see [Troubleshoot Azure AD Domain Services](https://docs.microsoft.com/azure/active-directory-domain-services/troubleshoot) to resolve common errors to help you get things working again.</span></span> 

<span data-ttu-id="cf7ce-110">**Tidak dapat menonaktifkan AAD-DS**</span><span class="sxs-lookup"><span data-stu-id="cf7ce-110">**Unable to disable AAD-DS**</span></span>

<span data-ttu-id="cf7ce-111">AAD-DS tidak dapat dihentikan sebentar.</span><span class="sxs-lookup"><span data-stu-id="cf7ce-111">AAD-DS is unable to be paused.</span></span> <span data-ttu-id="cf7ce-112">Jika ingin berhenti menggunakan domain terkelola, Anda harus dihapus.</span><span class="sxs-lookup"><span data-stu-id="cf7ce-112">If you wish to stop using your managed domain, it must be deleted.</span></span>

<span data-ttu-id="cf7ce-113">Jika Anda mengalami masalah, untuk mengatasi pesan kesalahan umum dan untuk langkah pemecahan masalah terkait untuk membantu Anda menyelesaikan pekerjaan, lihat [memecahkan masalah layanan domain Azure Active Directory](https://docs.microsoft.com/azure/active-directory-domain-services/troubleshoot).</span><span class="sxs-lookup"><span data-stu-id="cf7ce-113">If you run into issues, to resolve common error messages and for associated troubleshooting steps to help you get things running again, see [Troubleshoot Azure Active Directory Domain Services](https://docs.microsoft.com/azure/active-directory-domain-services/troubleshoot).</span></span>