---
title: Simpan situs atau daftar sebagai template
ms.author: pebaum
author: pebaum
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: 368ff1fa-82cf-4a07-986e-140b212ffc5c
ms.openlocfilehash: 627f49991aaef984f731412045351d7a1862b376
ms.sourcegitcommit: 0f0186044a3597e42ad14c32ca58e7224344dcfa
ms.translationtype: MT
ms.contentlocale: id-ID
ms.lasthandoff: 12/15/2019
ms.locfileid: "40048727"
---
# <a name="save-site-or-list-as-a-template"></a><span data-ttu-id="84c88-102">Simpan situs atau daftar sebagai template</span><span class="sxs-lookup"><span data-stu-id="84c88-102">Save site or list as a template</span></span>

<span data-ttu-id="84c88-103">Template situs SharePoint adalah definisi prebuilt yang dirancang di sekitar kebutuhan bisnis tertentu.</span><span class="sxs-lookup"><span data-stu-id="84c88-103">SharePoint site templates are prebuilt definitions designed around a particular business need.</span></span> <span data-ttu-id="84c88-104">Untuk informasi lebih lanjut, lihat [menggunakan template untuk membuat berbagai jenis situs SharePoint](https://support.office.com/article/using-templates-to-create-different-kinds-of-sharepoint-sites-449eccec-ff99-4cf3-b62e-dcfee37e8da4).</span><span class="sxs-lookup"><span data-stu-id="84c88-104">For more information, see [Using templates to create different kinds of SharePoint sites](https://support.office.com/article/using-templates-to-create-different-kinds-of-sharepoint-sites-449eccec-ff99-4cf3-b62e-dcfee37e8da4).</span></span>

<span data-ttu-id="84c88-105">Berikut adalah beberapa masalah/solusi umum mengenai menyimpan situs atau daftar sebagai template di SharePoint online.</span><span class="sxs-lookup"><span data-stu-id="84c88-105">Here are some common issues/solutions regarding Saving a Site or List as a template in SharePoint Online.</span></span>

<span data-ttu-id="84c88-106">**Simpan situs/daftar template tombol tidak tersedia atau hilang**.</span><span class="sxs-lookup"><span data-stu-id="84c88-106">**Save site/list template button is not available or missing**.</span></span> 

- <span data-ttu-id="84c88-107">Administrator akan perlu Izinkan skrip kustom untuk mengaktifkan fitur template.</span><span class="sxs-lookup"><span data-stu-id="84c88-107">Administrators will need to Allow Custom Script to enable the template features.</span></span> <span data-ttu-id="84c88-108">Untuk langkah rinci, contoh dan pertimbangan Lihat [membolehkan atau mencegah skrip kustom](https://docs.microsoft.com/sharepoint/allow-or-prevent-custom-script).</span><span class="sxs-lookup"><span data-stu-id="84c88-108">For detailed steps, examples and considerations see [Allow or prevent custom script](https://docs.microsoft.com/sharepoint/allow-or-prevent-custom-script).</span></span>


- <span data-ttu-id="84c88-109">Simpan situs sebagai template perintah tidak didukung dan dapat menyebabkan masalah pada situs yang menggunakan infrastruktur penerbitan SharePoint Server.</span><span class="sxs-lookup"><span data-stu-id="84c88-109">The Save site as template command is not supported and can cause problems on sites that use the SharePoint Server Publishing Infrastructure.</span></span>


<span data-ttu-id="84c88-110">**Template situs tidak dapat dibuat atau tidak berfungsi dengan benar**</span><span class="sxs-lookup"><span data-stu-id="84c88-110">**The site template cannot be created or does not work correctly**</span></span>

- <span data-ttu-id="84c88-111">Template mungkin hilang [fitur](https://social.technet.microsoft.com/wiki/contents/articles/14423.sharepoint-2013-existing-features-guid.aspx) dan tidak akan mengaktifkan.</span><span class="sxs-lookup"><span data-stu-id="84c88-111">The template may be missing a [feature](https://social.technet.microsoft.com/wiki/contents/articles/14423.sharepoint-2013-existing-features-guid.aspx) and won’t activate.</span></span> <span data-ttu-id="84c88-112">Jika fitur ini tidak tersedia untuk mengaktifkan dalam koleksi situs saat ini, Anda tidak dapat menggunakan template situs untuk membuat situs.</span><span class="sxs-lookup"><span data-stu-id="84c88-112">If the feature is not available to activate in the current site collection, you cannot use the site template to create a site.</span></span>


- <span data-ttu-id="84c88-113">Periksa untuk melihat apakah ada daftar atau Perpustakaan melebihi [ambang batas tampilan daftar](https://support.office.com/article/Manage-large-lists-and-libraries-in-SharePoint-B8588DAE-9387-48C2-9248-C24122F07C59) 5000 item karena hal ini dapat memblokir pembuatan template situs.</span><span class="sxs-lookup"><span data-stu-id="84c88-113">Check to see if any lists or libraries exceed the [List View Limit Threshold](https://support.office.com/article/Manage-large-lists-and-libraries-in-SharePoint-B8588DAE-9387-48C2-9248-C24122F07C59) of 5000 items as this can block creation of a site template.</span></span>


- <span data-ttu-id="84c88-114">Situs mungkin menggunakan terlalu banyak sumber daya dan oleh karena itu template situs melebihi batas 50 megabyte (MB).</span><span class="sxs-lookup"><span data-stu-id="84c88-114">The site may be using too many resources and therefore the site template exceeds the 50 megabyte (MB) limit.</span></span>


- <span data-ttu-id="84c88-115">Ada masalah menampilkan data dari daftar yang menggunakan kolom pencarian.</span><span class="sxs-lookup"><span data-stu-id="84c88-115">There are problems displaying data from a list that uses a lookup column.</span></span> <span data-ttu-id="84c88-116">Untuk informasi selengkapnya, lihat [Daftar dihasilkan template tidak menampilkan data dari daftar pencarian yang benar di SharePoint online](https://docs.microsoft.com/sharepoint/support/lists-and-libraries/template-generated-list-incorrect-data).</span><span class="sxs-lookup"><span data-stu-id="84c88-116">For more information, see [Template-generated list doesn’t display data from the correct lookup list in SharePoint Online](https://docs.microsoft.com/sharepoint/support/lists-and-libraries/template-generated-list-incorrect-data).</span></span>


<span data-ttu-id="84c88-117">Untuk informasi lebih rinci tentang masalah umum dan solusi silahkan referensi, [membuat dan menggunakan situs template](https://support.office.com/article/Create-and-use-site-templates-60371B0F-00E0-4C49-A844-34759EBDD989).</span><span class="sxs-lookup"><span data-stu-id="84c88-117">For more detailed information on common problems and solutions please reference, [Create and use site templates](https://support.office.com/article/Create-and-use-site-templates-60371B0F-00E0-4C49-A844-34759EBDD989).</span></span>

