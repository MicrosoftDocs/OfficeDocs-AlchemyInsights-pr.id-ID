---
title: Cara menambahkan dan mengelola langkah-langkah yang direkomendasikan administrator
ms.author: v-smandalika
author: v-smandalika
manager: dansimp
ms.date: 12/07/2020
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9004114"
- "7194"
ms.openlocfilehash: ed3aa5defabdd4f505ee4f74570023d990910dcb
ms.sourcegitcommit: 04bf13605a30ad4a2218ad9e94dcffcee4cc9aa6
ms.translationtype: MT
ms.contentlocale: id-ID
ms.lasthandoff: 01/05/2021
ms.locfileid: "49755838"
---
# <a name="how-to-add-and-manage-administrators---recommended-steps"></a><span data-ttu-id="559d2-102">Cara menambahkan dan mengelola langkah-langkah yang direkomendasikan administrator</span><span class="sxs-lookup"><span data-stu-id="559d2-102">How to add and manage administrators - recommended steps</span></span>

<span data-ttu-id="559d2-103">Berdasarkan Deskripsi masalah Anda, kami telah menemukan solusi untuk Anda.</span><span class="sxs-lookup"><span data-stu-id="559d2-103">Based on your issue description, we’ve found a solution for you.</span></span> <span data-ttu-id="559d2-104">Sebagian besar pelanggan dapat mengatasi masalah mereka sendiri setelah mengikuti dokumentasi kami.</span><span class="sxs-lookup"><span data-stu-id="559d2-104">Most customers were able to resolve their issue on their own after following our documentation.</span></span>

<span data-ttu-id="559d2-105">**Mengedit administrator langganan atau administrator bersama**</span><span class="sxs-lookup"><span data-stu-id="559d2-105">**Edit the Subscription Administrator or Co-administrator**</span></span>

- <span data-ttu-id="559d2-106">Administrator akun bisa mengedit kedua peran sedangkan administrator langganan hanya dapat mengubah administrator bersama di [portal Azure](https://ms.portal.azure.com/#home).</span><span class="sxs-lookup"><span data-stu-id="559d2-106">The Account Administrator can edit both roles whereas the Subscription Administrator can only change Co-administrators in the [Azure portal](https://ms.portal.azure.com/#home).</span></span>
- [<span data-ttu-id="559d2-107">Menambahkan atau mengubah administrator langganan Azure</span><span class="sxs-lookup"><span data-stu-id="559d2-107">Add or change Azure subscription administrators</span></span>](https://docs.microsoft.com/azure/cost-management-billing/manage/add-change-subscription-administrator)

<span data-ttu-id="559d2-108">**Memperbarui administrator langganan atau Co-Administrator untuk langganan internal (MENGUDARA)**</span><span class="sxs-lookup"><span data-stu-id="559d2-108">**Update the Subscription Administrator or Co-Administrator for Internal (AIRS) Subscriptions**</span></span>

<span data-ttu-id="559d2-109">Administrator layanan atau administrator bersama bisa melakukan sendiri tindakan ini dengan menggunakan langkah-langkah berikut:</span><span class="sxs-lookup"><span data-stu-id="559d2-109">The Service Administrator or the Co-administrator can self-serve this action by using the following steps:</span></span>

1. <span data-ttu-id="559d2-110">Masuk ke [portal Azure](https://ms.portal.azure.com/#home) dan klik **biaya manajemen + tagihan** di bilah kiri.</span><span class="sxs-lookup"><span data-stu-id="559d2-110">Log in to the [Azure portal](https://ms.portal.azure.com/#home) and click **Cost Management + Billing** in the left blade.</span></span>
2. <span data-ttu-id="559d2-111">Klik item baris dengan langganan Anda.</span><span class="sxs-lookup"><span data-stu-id="559d2-111">Click on the line item with your subscription.</span></span> <span data-ttu-id="559d2-112">Ini akan membuka gambaran umum langganan Anda.</span><span class="sxs-lookup"><span data-stu-id="559d2-112">This opens the Overview for your subscription.</span></span>
3. <span data-ttu-id="559d2-113">Pada bilah **langganan** , klik **properti**.</span><span class="sxs-lookup"><span data-stu-id="559d2-113">On the **Subscription** blade, click **Properties**.</span></span> 
4. <span data-ttu-id="559d2-114">Klik tombol **admin Layanan** .</span><span class="sxs-lookup"><span data-stu-id="559d2-114">Click the **Service Admin** button.</span></span>
5. <span data-ttu-id="559d2-115">Masukkan email pengguna yang ingin Anda setel sebagai administrator layanan dan klik **OK**.</span><span class="sxs-lookup"><span data-stu-id="559d2-115">Enter the email of the user whom you want to set as a Service Administrator and click **OK**.</span></span>

<span data-ttu-id="559d2-116">**Tambahkan/Ubah/Hapus administrator bersama**</span><span class="sxs-lookup"><span data-stu-id="559d2-116">**Add/Change/Remove Co-administrator**</span></span>

1. <span data-ttu-id="559d2-117">Masuk ke [Azure portal](https://ms.portal.azure.com/#home) sebagai administrator layanan.</span><span class="sxs-lookup"><span data-stu-id="559d2-117">Log in to the [Azure portal](https://ms.portal.azure.com/#home) as a Service Administrator.</span></span>
2. <span data-ttu-id="559d2-118">Buka [langganan](https://ms.portal.azure.com/#blade/Microsoft_Azure_Billing/SubscriptionsBlade) dan pilih langganan.</span><span class="sxs-lookup"><span data-stu-id="559d2-118">Open [Subscriptions](https://ms.portal.azure.com/#blade/Microsoft_Azure_Billing/SubscriptionsBlade) and select a subscription.</span></span> <span data-ttu-id="559d2-119">(Rekan kerja tunggal hanya dapat ditetapkan di lingkup langganan.)</span><span class="sxs-lookup"><span data-stu-id="559d2-119">(Co-adminstrators can only be assigned at the subscription scope.)</span></span>
3. <span data-ttu-id="559d2-120">Navigasikan ke administrator klasik **Access Control (iam)**  >    >  **Tambahkan**  >  **Add Co-administrator** untuk membuka panel **Tambahkan bersama admin** (jika opsi Tambahkan bersama administrator dinonaktifkan, maka Anda tidak memiliki izin).</span><span class="sxs-lookup"><span data-stu-id="559d2-120">Navigate to **Access control (IAM)** > **Classic administrators** > **Add** > **Add co-administrator** to open the **Add co-admin** pane (If the Add co-administrator option is disabled, it denotes that you do not have permissions).</span></span>
4. <span data-ttu-id="559d2-121">Pilih pengguna yang ingin Anda tambahkan dan klik **Tambahkan**.</span><span class="sxs-lookup"><span data-stu-id="559d2-121">Select the user whom you want to add and click **Add**.</span></span>

<span data-ttu-id="559d2-122">**Pelajari lebih lanjut:**</span><span class="sxs-lookup"><span data-stu-id="559d2-122">**Learn more:**</span></span>
- [<span data-ttu-id="559d2-123">Menambahkan administrator bersama</span><span class="sxs-lookup"><span data-stu-id="559d2-123">Add a Co-Administrator</span></span>](https://docs.microsoft.com/azure/role-based-access-control/classic-administrators)
- [<span data-ttu-id="559d2-124">Menghapus administrator bersama</span><span class="sxs-lookup"><span data-stu-id="559d2-124">Remove a co-administrator</span></span>](https://docs.microsoft.com/azure/role-based-access-control/classic-administrators)
- [<span data-ttu-id="559d2-125">Mengubah administrator Layanan</span><span class="sxs-lookup"><span data-stu-id="559d2-125">Change the Service Administrator</span></span>](https://docs.microsoft.com/azure/role-based-access-control/classic-administrators)
- [<span data-ttu-id="559d2-126">Menampilkan administrator akun</span><span class="sxs-lookup"><span data-stu-id="559d2-126">View the Account Administrator</span></span>](https://docs.microsoft.com/azure/role-based-access-control/classic-administrators)
- [<span data-ttu-id="559d2-127">Mengelola Access menggunakan portal RBAC dan Azure</span><span class="sxs-lookup"><span data-stu-id="559d2-127">Manage access using RBAC and Azure portal</span></span>](https://docs.microsoft.com/azure/role-based-access-control/role-assignments-portal)

<span data-ttu-id="559d2-128">**Menambahkan/menghapus pengguna menggunakan Azure Active Directory (AD)**</span><span class="sxs-lookup"><span data-stu-id="559d2-128">**Add/delete users using Azure Active Directory (AD)**</span></span>

<span data-ttu-id="559d2-129">Anda dapat menambahkan pengguna baru atau menghapus pengguna yang sudah ada dari organisasi Azure Active Directory (Azure AD):</span><span class="sxs-lookup"><span data-stu-id="559d2-129">You can add new users or delete existing users from your Azure Active Directory (Azure AD) organization:</span></span>

1. <span data-ttu-id="559d2-130">Untuk menambahkan pengguna baru, masuk ke [Azure portal](https://ms.portal.azure.com/#home) sebagai administrator pengguna untuk organisasi.</span><span class="sxs-lookup"><span data-stu-id="559d2-130">To add a new user, log in to the [Azure portal](https://ms.portal.azure.com/#home) as a User-administrator for the organization.</span></span>
2. <span data-ttu-id="559d2-131">Pilih **direktori aktif Azure**, pilih **pengguna** , lalu klik **pengguna baru**.</span><span class="sxs-lookup"><span data-stu-id="559d2-131">Select **Azure Active Directory**, select **Users** and then click **New user**.</span></span>
3. <span data-ttu-id="559d2-132">Pada halaman **pengguna** , isi informasi yang diperlukan.</span><span class="sxs-lookup"><span data-stu-id="559d2-132">On the **User** page, fill out the required information.</span></span> <span data-ttu-id="559d2-133">Klik **buat**.</span><span class="sxs-lookup"><span data-stu-id="559d2-133">Click **Create**.</span></span> <span data-ttu-id="559d2-134">Pengguna dibuat dan ditambahkan ke penyewa Azure AD Anda.</span><span class="sxs-lookup"><span data-stu-id="559d2-134">The user is created and added to your Azure AD tenant.</span></span>

<span data-ttu-id="559d2-135">**Pelajari selengkapnya**:</span><span class="sxs-lookup"><span data-stu-id="559d2-135">**Learn more**:</span></span>

- [<span data-ttu-id="559d2-136">Menambahkan pengguna baru</span><span class="sxs-lookup"><span data-stu-id="559d2-136">Add a new user</span></span>](https://docs.microsoft.com/azure/active-directory/fundamentals/add-users-azure-active-directory)
- [<span data-ttu-id="559d2-137">Menghapus pengguna</span><span class="sxs-lookup"><span data-stu-id="559d2-137">Delete a user</span></span>](https://docs.microsoft.com/azure/active-directory/fundamentals/add-users-azure-active-directory)
- [<span data-ttu-id="559d2-138">Menambahkan atau memperbarui informasi profil pengguna menggunakan Azure Active Directory</span><span class="sxs-lookup"><span data-stu-id="559d2-138">Add or update a user's profile information using Azure Active Directory</span></span>](https://docs.microsoft.com/azure/active-directory/fundamentals/active-directory-users-profile-azure-portal)

<span data-ttu-id="559d2-139">**Dokumen yang direkomendasikan**</span><span class="sxs-lookup"><span data-stu-id="559d2-139">**Recommended documents**</span></span>

- [<span data-ttu-id="559d2-140">Apa itu kontrol akses berbasis peran (RBAC)?</span><span class="sxs-lookup"><span data-stu-id="559d2-140">What is role-based access control (RBAC)?</span></span>](https://docs.microsoft.com/azure/role-based-access-control/overview)
- [<span data-ttu-id="559d2-141">Memahami peran berbeda di Azure</span><span class="sxs-lookup"><span data-stu-id="559d2-141">Understand the different roles in Azure</span></span>](https://docs.microsoft.com/azure/role-based-access-control/rbac-and-directory-admin-roles)
- [<span data-ttu-id="559d2-142">Izin peran administrator di Azure Active Directory</span><span class="sxs-lookup"><span data-stu-id="559d2-142">Administrator role permissions in Azure Active Directory</span></span>](https://docs.microsoft.com/azure/active-directory/roles/permissions-reference)
- [<span data-ttu-id="559d2-143">Tutorial: memberi akses untuk pengguna menggunakan RBAC dan portal Azure</span><span class="sxs-lookup"><span data-stu-id="559d2-143">Tutorial: Grant access for a user using RBAC and the Azure portal</span></span>](https://docs.microsoft.com/azure/role-based-access-control/quickstart-assign-role-user-portal)
- [<span data-ttu-id="559d2-144">Memecahkan masalah RBAC di Azure</span><span class="sxs-lookup"><span data-stu-id="559d2-144">Troubleshoot RBAC in Azure</span></span>](https://docs.microsoft.com/azure/role-based-access-control/troubleshooting)
- [<span data-ttu-id="559d2-145">Menata sumber daya Anda dengan grup manajemen Azure</span><span class="sxs-lookup"><span data-stu-id="559d2-145">Organize your resources with Azure management groups</span></span>](https://docs.microsoft.com/azure/governance/management-groups/overview)
- [<span data-ttu-id="559d2-146">Cara meminta salinan faktur Azure melalui email</span><span class="sxs-lookup"><span data-stu-id="559d2-146">How to request copy of Azure invoice via email</span></span>](https://azure.microsoft.com/en-us/blog/azure-email-invoices/)
- [<span data-ttu-id="559d2-147">Cara menambahkan, memperbarui, atau menghapus kartu kredit atau debit dari Azure</span><span class="sxs-lookup"><span data-stu-id="559d2-147">How to add, update or remove a credit or debit card from Azure</span></span>](https://docs.microsoft.com/azure/cost-management-billing/manage/change-credit-card)
- [<span data-ttu-id="559d2-148">Langganan Kelola (aktivasi ulang/Batalkan/pengalihan)</span><span class="sxs-lookup"><span data-stu-id="559d2-148">Manage (Reactivate/Cancel/Switch) subscription</span></span>](https://docs.microsoft.com/azure/cost-management-billing/manage/subscription-disabled)



