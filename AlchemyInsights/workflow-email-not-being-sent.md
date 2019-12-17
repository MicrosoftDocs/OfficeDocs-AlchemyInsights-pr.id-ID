---
title: Alur kerja email tidak sedang dikirim
ms.author: pebaum
author: pebaum
manager: pamgreen
ms.date: 7/25/2019
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "5200020"
- "1586"
ms.openlocfilehash: 76b64323c9d34d49e9c6bd77c2cc7eff6d7c5402
ms.sourcegitcommit: 0f0186044a3597e42ad14c32ca58e7224344dcfa
ms.translationtype: MT
ms.contentlocale: id-ID
ms.lasthandoff: 12/15/2019
ms.locfileid: "40049376"
---
# <a name="workflow-email-is-not-being-sent-for-a-sharepoint-list-or-library"></a><span data-ttu-id="fe2a6-102">Alur kerja email tidak sedang dikirim untuk SharePoint daftar atau Perpustakaan</span><span class="sxs-lookup"><span data-stu-id="fe2a6-102">Workflow email is not being sent for a SharePoint list or library</span></span>

1. <span data-ttu-id="fe2a6-103">Email dari alur kerja tidak dikirim ke semua pengguna atau hanya pengguna tertentu, atau Anda melihat galat **pesan email tidak dapat dikirim. Pastikan e-mail memiliki penerima yang valid**.</span><span class="sxs-lookup"><span data-stu-id="fe2a6-103">Email from workflows are not sent to all users or only specific users, or you see the error **The e-mail message cannot be sent. Make sure the e-mail has a valid recipient**.</span></span>

    <span data-ttu-id="fe2a6-104">Periksa jika pengguna yang ada di **semua orang** izin grup (daftar informasi pengguna) untuk koleksi situs tersebut.</span><span class="sxs-lookup"><span data-stu-id="fe2a6-104">Check if the user exist in the **All People** permissions group (user information list) for that site collection.</span></span>  <span data-ttu-id="fe2a6-105">Contoh URL langsung: https://<tenant>. sharepoint.com/sites/<sitename>/_layouts/15/People.aspx? MembershipGroupId = 0</span><span class="sxs-lookup"><span data-stu-id="fe2a6-105">Sample direct URL: https://<tenant>.sharepoint.com/sites/<sitename>/_layouts/15/people.aspx?MembershipGroupId=0</span></span>

    - <span data-ttu-id="fe2a6-106">Jika pengguna tidak ada, pastikan pengguna masuk ke halaman.</span><span class="sxs-lookup"><span data-stu-id="fe2a6-106">If the user does not exist, make sure the user is signed into the page.</span></span> 
    - <span data-ttu-id="fe2a6-107">Jika pengguna eksternal, pastikan bahwa undangan mereka telah diterima.</span><span class="sxs-lookup"><span data-stu-id="fe2a6-107">If it is an external user, make sure that their invitation has been accepted.</span></span>
    - <span data-ttu-id="fe2a6-108">Jika pengguna tidak ada di grup izin, pastikan alamat email sudah benar.</span><span class="sxs-lookup"><span data-stu-id="fe2a6-108">If the user does exist in the permissions group, make sure the email address is correct.</span></span>
    - <span data-ttu-id="fe2a6-109">Jika alamat email pengguna tidak ditetapkan di sini, kemudian membuat peringatan contoh untuk pengguna yang memaksa sinkronisasi akun pengguna tersebut dari profil pengguna SharePoint untuk koleksi situs ini.</span><span class="sxs-lookup"><span data-stu-id="fe2a6-109">If the users email address is not set here, then create a sample alert for that user which forces the sync of that user account from User Profiles of SharePoint to this site collection.</span></span>
 
2. <span data-ttu-id="fe2a6-110">Email dari alur kerja dikirim ke administrator koleksi situs tetapi tidak untuk pengguna lain dan melihat galat **http terlarang untuk <span>https:</span>/url/_vti_bin/client.xvc.SP.Utilities.Utility.sendemail**.</span><span class="sxs-lookup"><span data-stu-id="fe2a6-110">Email from workflows are sent to the site collection administrators but not to other users and see the error **HTTP Forbidden to <span>https:</span>//URL/_vti_bin/client.xvc.sp.utilities.utility.SendEmail**.</span></span>
 

    <span data-ttu-id="fe2a6-111">Lihat [Akses ditolak ketika Anda mengirim email ke grup SharePoint](https://docs.microsoft.com/sharepoint/support/sharing-and-permissions/access-denied-when-send-an-email-to-groups).</span><span class="sxs-lookup"><span data-stu-id="fe2a6-111">See [Access Denied when you send an email to a SharePoint group](https://docs.microsoft.com/sharepoint/support/sharing-and-permissions/access-denied-when-send-an-email-to-groups).</span></span>

    <span data-ttu-id="fe2a6-112">Selain itu, verifikasi bahwa fitur pengumpulan situs **akses terbatas pengguna izin penguncian mode** tidak aktif.</span><span class="sxs-lookup"><span data-stu-id="fe2a6-112">Also, verify that the **Limited-access user permission lockdown mode** site collection feature is not active.</span></span>


## <a name="related-topics"></a><span data-ttu-id="fe2a6-113">Topik terkait</span><span class="sxs-lookup"><span data-stu-id="fe2a6-113">Related topics</span></span>
<span data-ttu-id="fe2a6-114">Ingin mencoba Microsoft Flow di SharePoint online?</span><span class="sxs-lookup"><span data-stu-id="fe2a6-114">Want to try Microsoft Flow in SharePoint Online?</span></span>
- [<span data-ttu-id="fe2a6-115">Membuat Flow</span><span class="sxs-lookup"><span data-stu-id="fe2a6-115">Create Flow</span></span>](https://support.office.com/article/Create-a-flow-for-a-list-or-library-in-SharePoint-Online-or-OneDrive-for-Business-a9c3e03b-0654-46af-a254-20252e580d01) 
- [<span data-ttu-id="fe2a6-116">SharePoint dan aliran</span><span class="sxs-lookup"><span data-stu-id="fe2a6-116">SharePoint and Flow</span></span>](https://flow.microsoft.com/blog/sharepoint-and-flow/) 


