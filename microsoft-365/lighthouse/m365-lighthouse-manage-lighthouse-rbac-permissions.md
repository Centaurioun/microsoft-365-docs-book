---
title: "Manage Lighthouse RBAC permissions in Microsoft 365 Lighthouse"
f1.keywords: NOCSH
ms.author: sharik
author: SKjerland
manager: scotv
ms.reviewer: taylorau
ms.date: 04/24/2024
audience: Admin
ms.topic: how-to
ms.service: microsoft-365-lighthouse
ms.localizationpriority: medium
ms.collection:
- Tier1
- scotvorg
- M365-subscription-management
- Adm_O365
ms.custom:
- AdminSurgePortfolio
- M365-Lighthouse                         
search.appverid: MET150
description: "For Managed Service Providers (MSPs) using Microsoft 365 Lighthouse, learn how to manage Lighthouse role-based access control (RBAC) permissions in Microsoft 365 Lighthouse."
---

# Manage Lighthouse RBAC permissions in Microsoft 365 Lighthouse

The Lighthouse permissions page allows administrators in Microsoft 365 Lighthouse to manage user role-based access control (RBAC) permissions in the partner tenant. Administrators can view and manage membership for each Lighthouse RBAC role to ensure that users in the partner tenant have right-sized permissions. Each Lighthouse RBAC role is associated with a security group instead of an Entra ID role, so when users are assigned a Lighthouse RBAC role, they're automatically associated with a specific Lighthouse RBAC security group.

When administrators assign a Lighthouse RBAC role to a user in the partner tenant for the first time, a security group is automatically created. Administrators can view the associated security group for each Lighthouse RBAC role on the Lighthouse permissions page and in the Microsoft Entra admin center. All security group membership changes are reflected in both Lighthouse and the Microsoft Entra admin center.

## Before you begin

To access the Lighthouse permissions page and manage permissions, you must be a Global Administrator in Microsoft Entra ID.

## View Lighthouse RBAC role membership and associated security group

1. In the left navigation pane in <a href="https://go.microsoft.com/fwlink/p/?linkid=2168110" target="_blank">Lighthouse</a>, select **Permissions** > **Lighthouse permissions**.
 
2. Select a Lighthouse role from the list to open the Lighthouse role details pane.
 
3. View users in the partner tenant who are assigned the Lighthouse RBAC role and the associated security group.

## Assign Lighthouse RBAC roles to users in the partner tenant

1. In the left navigation pane in <a href="https://go.microsoft.com/fwlink/p/?linkid=2168110" target="_blank">Lighthouse</a>, select **Permissions** > **Lighthouse permissions**.
 
2. Select a Lighthouse role from the list to open the Lighthouse role details pane.
 
3. Select **Assign users**.
 
4. Select the users you want to assign to the Lighthouse RBAC role.

5. Select **Assign users**.
 
> [!NOTE]
> The Lighthouse Operator role is viewable but not assignable from the Lighthouse permissions page. The Lighthouse Operator role is automatically assigned to users with GDAP permissions.

## Remove users in the partner tenant from a Lighthouse RBAC role

1. In the left navigation pane in <a href="https://go.microsoft.com/fwlink/p/?linkid=2168110" target="_blank">Lighthouse</a>, select **Permissions** > **Lighthouse permissions**.

2. Select a Lighthouse role from the list to open the Lighthouse role details pane.

3. Do one of the following:
    - To remove a single user from the Lighthouse RBAC role, select the **X** next to the user you want to remove.
    - To remove multiple users from the Lighthouse RBAC role, select the users you want to remove, and then select **Remove users**.

4. In the confirmation window, select **Remove users** to confirm removal.
 
## Create or update a security group for a Lighthouse RBAC role

1. In the left navigation pane in <a href="https://go.microsoft.com/fwlink/p/?linkid=2168110" target="_blank">Lighthouse</a>, select **Permissions** > **Lighthouse permissions**.

2. Select a Lighthouse role from the list to open the Lighthouse role details pane.
 
3. Select **Update security group**.

4. Do one of the following:
    - Select **Use an existing security group**, select a security group from the list, and then select **Save**.
    - Select **Create a new security group**, enter a name for the new group, optionally enter a description and add users, and then select **Save**.

> [!NOTE]
> You must assign the Lighthouse RBAC Administrator role to a role-assignable security group. In addition, to be able to assign roles to a role-assignable security group and/or create role-assignable security groups, you must have a Microsoft Entra ID P1 license. To enable Just-in-Time (JIT) roles, Microsoft Entra IDE Governance or a Microsoft Entra ID P2 license is required.
> 
> You can assign all other Lighthouse RBAC roles to any security group, whether it's role-assignable or not, but keep the P1 license requirement in mind for role-assignable security groups.
>  
> To learn more, see [Use Microsoft Entra groups to manage role assignments](/entra/identity/role-based-access-control/groups-concept).

## Next steps

After you've added users to, or removed users from, the available Lighthouse RBAC roles, go to the Lighthouse permissions page to view the latest group membership for each role.

> [!NOTE]
> Once you've added a user to, or removed a user from, a Lighthouse RBAC role, it may take up to an hour for group membership changes to appear in Lighthouse.

To learn more about each Lighthouse RBAC role to determine which roles users in your partner tenant should have, see [Overview of permissions in Microsoft 365 Lighthouse](m365-lighthouse-overview-of-permissions.md).

## Related content

[Overview of permissions in Microsoft 365 Lighthouse](m365-lighthouse-overview-of-permissions.md) (article)\
[Set up GDAP for your customers](m365-lighthouse-setup-gdap.md) (article)\
[Overview of Delegated Access in Microsoft 365 Lighthouse](m365-lighthouse-delegated-access-overview.md) (article)\
[Use Microsoft Entra groups to manage role assignments](/entra/identity/role-based-access-control/groups-concept)