---
title: Petunjuk untuk menyembunyikan/menampilkan grup dari daftar alamat
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "1200024"
- "3161"
ms.openlocfilehash: d0e0285701f1a5f308bdc682abaddf5cc2d34120
ms.sourcegitcommit: defe2c412567b596fa8c3ab52111bde712ebb314
ms.translationtype: MT
ms.contentlocale: id-ID
ms.lasthandoff: 10/29/2019
ms.locfileid: "37768928"
---
# <a name="hide-office-365-group-from-address-list-gal"></a><span data-ttu-id="8d9c7-102">Sembunyikan Office 365 grup dari daftar alamat (GAL)</span><span class="sxs-lookup"><span data-stu-id="8d9c7-102">Hide Office 365 group from address list (GAL)</span></span>

<span data-ttu-id="8d9c7-103">Untuk menyembunyikan Office 365 grup dari alamat daftar (GAL) klien Exchange (seperti Outlook atau OWA), gunakan perintah berikut di EXO Shell:</span><span class="sxs-lookup"><span data-stu-id="8d9c7-103">To hide an Office 365 group from address lists (GAL) of Exchange clients (such as Outlook or OWA), use the following command in EXO shell:</span></span>

`Set-UnifiedGroup -Identity GroupName -HiddenFromAddressListsEnabled:$true`

<span data-ttu-id="8d9c7-104">Untuk menyembunyikan Office 365 grup dari yang terlihat untuk Exchange klien, gunakan perintah berikut di EXO Shell:</span><span class="sxs-lookup"><span data-stu-id="8d9c7-104">To hide the Office 365 group from being visible to Exchange clients, use the following command in EXO shell:</span></span>

`Set-unifiedGroup -Identity GroupName -HiddenFromExchangeClientsEnabled:$true
Check this article for detailed instructions`
