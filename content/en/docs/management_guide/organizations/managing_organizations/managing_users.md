---
title: Managing users
linkTitle: Managing users
weight: 20
date: 2021-08-12
---

The **Users** view enables you to view and manage users of the selected organization.

![Managing users](/Images/dashboard_users.png)

### Invite a user to your organization

If you are an organization admin, you can add users to an organization.

1. Sign in to the [Platform](https://platform.axway.com/).
2. Click on the **User & Org** menu and select **Organization**.
3. Click the **Users** tab from the left navigation.
4. If you're a user of multiple organizations, select the organization you want to view from the *Users* dropdown menu.
5. Click the **User** button in the upper-right corner.
6. Enter the user's email address.
7. Select the user's roles from the *Org Roles* dropdown menu. One platform role and zero, one or more service roles can be selected. Administrators can manage all users and applications in the organization.
8. In the **Teams** list, select the teams, if any, to which the user should be added.
9. Select the role the new organization member will fulfill on their assigned team from the *Roles* dropdown menu.
10. Click **Save**.

An email invitation is sent to the user, providing a link to confirm their membership.

### View and modify a user's role or access

After you create or add a users to your organization, you can view and modify the user's access rights or role.

1. Sign in to the [Platform](https://platform.axway.com/).
2. Click the **User & Org** menu, and then select **Organization**.
3. Click **Users** from the left navigation.
4. If you're a user of multiple organizations, select the organization you want to view from the *Users* dropdown menu.
5. If an Identity Provider is configured for the organization, an *Identity Provider* dropdown menu is provided. Select a different Identity Provider or no restriction (do not require authenticating with a configured Identity Provider) from the *Identity Provider* dropdown menu.
6. To change a user's role, select a different role or additional roles from the *Role* dropdown menu. Note that the *Role* dropdown menu selections are sorted by product roles. Administrators can manage all users and applications in the organization. All other user roles can view only applications to which they belong.
7. To remove a selected user from the organization, select the **Actions** menu (**...**), and select **Remove User** and then confirm the removal.
8. To view a user's team assignments, select the **Actions** icon, and select **View Teams**. Refer to [Managing teams](#managing-teams).

The user's last login is displayed in the *Last Login* column, and their current multi-factor authentication status is shown in the *MFA* column. For more information on multi-factor authentication, refer to [Manage multi-factor authentication](/docs/management_guide/managing_accounts/#manage-multi-factor-authentication).