---
title: Kirim sebagai email yang mengaktifkan folder publik di EXO
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
- "1956"
- "3500007"
ms.openlocfilehash: ed62c6d7db0ae532f806ce4fdc48f42623bcd545
ms.sourcegitcommit: 1fb324fd156008e77b7e2008af4b3dc1c0d0ea3e
ms.translationtype: MT
ms.contentlocale: id-ID
ms.lasthandoff: 10/13/2020
ms.locfileid: "48461961"
---
# <a name="sendas-mail-enabled-public-folder"></a>Email SendAs mengaktifkan folder publik

Contoh berikut ini menetapkan izin "Kirim sebagai" untuk folder publik yang didukung email NewPF1 kepada pengguna Jason.

Add-RecipientPermission-identitas ' NewPF1 '-Trustee "Jason"-AccessRights ' SendAs '

Untuk informasi mendetail dan sintaks, lihat [menetapkan izin "Kirim sebagai" atau izin "Kirim atas nama" untuk folder publik dengan dukungan email](https://docs.microsoft.com/exchange/collaboration-exo/public-folders/assign-permissions-mail-enabled-pfs).

