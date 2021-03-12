---
title: Memecahkan masalah akses masuk tunggal (SSO) berbasis kata sandi
ms.author: v-jmathew
author: v-jmathew
manager: scotv
audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9004357"
- "9374"
ms.openlocfilehash: 4a9163f199a505df9b2de4f02b7c37a5f5677022
ms.sourcegitcommit: 0eb4f9bde53395b5fd4b5cd4ffc56ca96db91298
ms.translationtype: MT
ms.contentlocale: id-ID
ms.lasthandoff: 03/10/2021
ms.locfileid: "50714771"
---
# <a name="troubleshoot-password-based-seamless-single-sign-on-sso-issues"></a><span data-ttu-id="ae0a2-102">Memecahkan masalah akses masuk tunggal (SSO) berbasis kata sandi</span><span class="sxs-lookup"><span data-stu-id="ae0a2-102">Troubleshoot Password-based Seamless Single Sign-on (SSO) issues</span></span>

<span data-ttu-id="ae0a2-103">Untuk mempelajari dasar-dasar SSO berbasis kata sandi, lihat [autentikasi berbasis kata sandi dengan Azure Active Directory](https://docs.microsoft.com/azure/active-directory/fundamentals/auth-password-based-sso).</span><span class="sxs-lookup"><span data-stu-id="ae0a2-103">To learn the fundamentals of password-based SSO, see [Password-based authentication with Azure Active Directory](https://docs.microsoft.com/azure/active-directory/fundamentals/auth-password-based-sso).</span></span>

<span data-ttu-id="ae0a2-104">**Mengonfigurasi SSO berbasis kata sandi**</span><span class="sxs-lookup"><span data-stu-id="ae0a2-104">**Configure Password-based SSO**</span></span>

1. <span data-ttu-id="ae0a2-105">[Konfigurasi akses masuk tunggal berbasis kata sandi](https://docs.microsoft.com/azure/active-directory/manage-apps/configure-password-single-sign-on-non-gallery-applications) -artikel ini MEMBAHAS opsi SSO berbasis kata sandi.</span><span class="sxs-lookup"><span data-stu-id="ae0a2-105">[Configure password-based single sign-on](https://docs.microsoft.com/azure/active-directory/manage-apps/configure-password-single-sign-on-non-gallery-applications) - This article goes into more detail about the password-based SSO option.</span></span> <span data-ttu-id="ae0a2-106">Jika aplikasi yang Anda tambahkan memerlukan konfigurasi kustom dan Anda perlu menggunakan SSO berbasis kata sandi, maka artikel ini ditujukan untuk Anda.</span><span class="sxs-lookup"><span data-stu-id="ae0a2-106">If the application you're adding requires custom configuration and you need to use password-based SSO, then this article is for you.</span></span>
2. <span data-ttu-id="ae0a2-107">[Konfigurasi single sign-on berbasis kata sandi untuk aplikasi di prem](https://docs.microsoft.com/azure/active-directory/manage-apps/application-proxy-configure-single-sign-on-password-vaulting) -proksi aplikasi mendukung beberapa mode masuk tunggal.</span><span class="sxs-lookup"><span data-stu-id="ae0a2-107">[Configure password-based single sign on for on-prem apps](https://docs.microsoft.com/azure/active-directory/manage-apps/application-proxy-configure-single-sign-on-password-vaulting) - Application Proxy supports several single sign-on modes.</span></span> <span data-ttu-id="ae0a2-108">Masuk berbasis kata sandi ditujukan untuk aplikasi yang menggunakan kombinasi nama pengguna/kata sandi untuk autentikasi.</span><span class="sxs-lookup"><span data-stu-id="ae0a2-108">Password-based sign-on is intended for applications that use a username/password combination for authentication.</span></span> <span data-ttu-id="ae0a2-109">Saat Anda mengonfigurasi masuk berbasis kata sandi untuk aplikasi Anda, pengguna Anda harus masuk ke aplikasi di tempat satu kali.</span><span class="sxs-lookup"><span data-stu-id="ae0a2-109">When you configure password-based sign-on for your application, your users have to sign in to the on-premises application once.</span></span> <span data-ttu-id="ae0a2-110">Setelah itu, Azure Active Directory menyimpan informasi masuk dan secara otomatis menyediakannya ke aplikasi saat pengguna Anda mengaksesnya dari jarak jauh.</span><span class="sxs-lookup"><span data-stu-id="ae0a2-110">After that, Azure Active Directory stores the sign-in information and automatically provides it to the application when your users access it remotely.</span></span>
    - <span data-ttu-id="ae0a2-111">Anda harus sudah menerbitkan dan menguji aplikasi Anda dengan proksi aplikasi.</span><span class="sxs-lookup"><span data-stu-id="ae0a2-111">You should already have published and tested your app with Application Proxy.</span></span> <span data-ttu-id="ae0a2-112">Jika tidak, ikuti langkah-langkah dalam [menerbitkan aplikasi menggunakan proksi aplikasi AZURE AD](https://docs.microsoft.com/azure/active-directory/manage-apps/application-proxy-add-on-premises-application) lalu Lanjutkan konfigurasi SSO berbasis kata sandi untuk aplikasi di prem.</span><span class="sxs-lookup"><span data-stu-id="ae0a2-112">If not, follow the steps in [Publish applications using Azure AD Application Proxy](https://docs.microsoft.com/azure/active-directory/manage-apps/application-proxy-add-on-premises-application) then continue your configuration of password-based SSO for on-prem apps.</span></span>

<span data-ttu-id="ae0a2-113">Untuk memecahkan masalah SSO berbasis kata sandi, lihat [memecahkan masalah masuk tunggal berbasis kata sandi di AZURE AD](https://docs.microsoft.com/azure/active-directory/manage-apps/troubleshoot-password-based-sso)</span><span class="sxs-lookup"><span data-stu-id="ae0a2-113">To troubleshoot password-based SSO, see [Troubleshoot password-based single sign-on in Azure AD](https://docs.microsoft.com/azure/active-directory/manage-apps/troubleshoot-password-based-sso)</span></span>