---
title: How to remove duplicate mobile device management objects in Azure Active Directory
description: Describes how to remove duplicate mobile device management objects in Azure AD that are not automatically removed.
ms.date: 09/02/2021
ms.reviewer: anthonge, willfid
search.appverid: MET150
---
# How to remove duplicate mobile device management objects in Azure Active Directory

This article describes how to remove duplicate mobile device management objects in Azure Active Directory (Azure AD). You can use this procedure to remove orphaned device objects in Azure AD that are not automatically removed by the service after 90 days.

> [!NOTE]
> Microsoft recommends that administrators use PowerShell to remove duplicate or stale devices from Azure AD. However, there may be instances in which it is necessary to remove Intune-managed devices manually. For more information, see [clean up stale devices in the Azure portal](/azure/active-directory/devices/manage-stale-devices#clean-up-stale-devices-in-the-azure-portal).

1. Sign in to the [Microsoft 365 admin center](https://admin.microsoft.com/) as an administrator.
2. Select **Azure Active Directory** > **Users**, and then select the user account that the device is registered to.

    > [!NOTE]
    >  If you don't already have a Microsoft Azure subscription, each paid Office 365 subscription includes a free subscription to Microsoft Azure. To obtain this subscription, you must first sign up for the Azure AD subscription.

3. Select **Devices**.
4. In the list of devices that are registered to the user, select the device that you want to remove.
5. Delete the orphaned entry.
