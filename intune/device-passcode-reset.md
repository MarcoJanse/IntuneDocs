---
# required metadata

title: Reset device passcodes with Microsoft Intune - Azure | Microsoft Docs
description: Remove or reset the passcode by using the remove passcode action on devices you manage or monitor with Intune.
keywords:
author: MandiOhlinger
ms.author: mandia
manager: dougeby
ms.date: 03/06/2018
ms.topic: article
ms.prod:
ms.service: microsoft-intune
ms.technology:
ms.assetid: 47181d19-4049-4c7a-a8de-422206c4027e

# optional metadata

#ROBOTS:
#audience:
#ms.devlang:
#ms.reviewer: ilwu
ms.suite: ems
#ms.tgt_pltfrm:
ms.custom: intune-azure

---

# Reset or remove a device passcode in Intune

[!INCLUDE[azure_portal](./includes/azure_portal.md)]

To create a new passcode for a device, use the **Remove passcode** action.

## Supported platforms

- Windows Phone 8.1 (not joined to Azure Active Directory), including releases up to Windows 10 Creators Update
- Windows 10 Creators Update and later
- iOS
- Android versions earlier than Android 7

This feature is not supported for the following systems:

- Windows
- macOS
- Android for Work

## Reset a passcode

1. Sign in to the [Azure portal](https://portal.azure.com).
2. Select **All services**, filter on **Intune**, and then select **Microsoft Intune**.
3. Select **Devices**, and then select **All devices**.
4. From the list of devices you manage, select a device, and choose **...More**. Then choose the **Remove passcode** device remote action.

## Next steps

To see the status of the action you just took, in **Devices**, select **Device actions**.
