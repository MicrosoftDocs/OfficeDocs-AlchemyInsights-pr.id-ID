---
title: Instruksi untuk menyembunyikan/memunculkan grup dari daftar alamat
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "1200024"
- "3161"
ms.openlocfilehash: 1ad9ab294d46ca0fc88a454e3503ddcf80398896
ms.sourcegitcommit: c6692ce0fa1358ec3529e59ca0ecdfdea4cdc759
ms.translationtype: MT
ms.contentlocale: id-ID
ms.lasthandoff: 09/14/2020
ms.locfileid: "47663012"
---
# <a name="hide-microsoft-365-group-from-address-list-gal"></a>Sembunyikan grup Microsoft 365 dari daftar alamat (GAL)

Untuk menyembunyikan grup Microsoft 365 dari daftar alamat (GAL) klien Exchange (seperti Outlook atau OWA), gunakan perintah berikut ini di EXO Shell:

`Set-UnifiedGroup -Identity GroupName -HiddenFromAddressListsEnabled:$true`

Untuk menyembunyikan grup Microsoft 365 agar tidak terlihat oleh klien Exchange, gunakan perintah berikut ini di EXO Shell:

`Set-unifiedGroup -Identity GroupName -HiddenFromExchangeClientsEnabled:$true
Check this article for detailed instructions`

