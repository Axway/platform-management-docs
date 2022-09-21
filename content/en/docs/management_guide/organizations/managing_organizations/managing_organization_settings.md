---
title: Managing organization settings
linkTitle: Managing organization settings
weight: 70
date: 2021-08-12
---

The **Settings** view enables you to:

* Apply branding to the Amplify Platform navigation and selected views for the selected organization.
* Configure and manage entity providers for Amplify Platform authentication.
* Redact personal information and configure password policy rules to add to the default password requirements.
* Change the organization name or delete the organization.

![Managing organization settings](/Images/settings_tab.png)

### Change the branding

To apply branding to Amplify Platform per your organization's branding requirements:

1. Sign in to the [Platform](https://platform.axway.com/).
2. Click on the **User & Org** menu and select **Organization**.
3. Click **Settings** from the left navigation. The *Branding* page appears.
4. If you're a member of multiple organizations, select the organization you want to view from the *Branding* dropdown menu.
5. Select your organization's logo. The logo will be displayed at a maximum height of 45 pixels, and the logo file must be less than 100KB.
    1. Click **Choose File**.
    2. Select the logo file to upload. Once the logo file is selected, the *Branding Preview* will update to display the selected logo.
    3. To remove the selected icon file, click **Remove**.
6. Select your catalog colors. As you select your catalog colors, the *Branding Preview* will update to display the selected colors.
    1. Select or enter the **Header Left** color.
    2. Select or enter the **Header Right** color.
    3. Select or enter the **Tile Border** color.
    4. Select or enter the **Tile Border on Hover** color.
7. Click **Save**.

### Manage Identity Providers

Click **Identity Provider** from the Organization - Settings menu to configure Identity Providers to use for user authentication with the Platform. Refer to the [Configuring and Managing Identity Providers (IdPs)](/docs/management_guide/configuring_and_managing_identity_providers/) page for details.

### Manage security settings

Click **Security** from the Organization - Settings menu to access organization security settings. Then, select the organization from the *Organization* dropdown menu to configure the following settings for the specified organization.

![Managing organization settings](/Images/settings_tab_security.png)

#### Redact personal information

Select the option to **Redact Personal Information** to redact email addresses within an organization where the user's email address is displayed, except the *Account* view. The email address on the *Account* view is always redacted, whether the setting is enabled or disabled. By default, the setting is disabled.

#### Configure password settings

Administrators have the option to configure additional password settings to add to the default password requirements.

* **Minimum Password Length** - Minimum number of characters a password must contain.
* **Password Complexity** - Select the option to require at least one character of the following type to be included in the password, or select **Advanced** to specify the number of required characters.

    * Lower case characters
    * Upper case characters
    * Special characters
    * Digits
* **Renewal period** - Number of days after which a user must change their password.
* **Not Recently Used** - Number of times a unique password is required before a previously used password can be reused.
* **Account Lock Out** - Number of times a user can attempt to log in with an incorrect password before the account is locked.

### Change organization name or delete organization

Click **Manage** from the Organization - Settings menu to change the organization name or delete the organization.

Type a different name to use for the organization, and then click **Save** to save changes, or **Reset** to revert changes.

The option to delete their organization is available for the user if they are not a member of one or more organizations with paid subscriptions. Users and organizations created by sign-up with no subscriptions or trial only subscriptions will see the delete option. If the user deleting their organization is the only member, then their user account will also be deleted.

A user which is a member of one or more organizations which have a Support Access Code must email support@axway.com or visit [Axway Support](https://support.axway.com/) to request Axway to delete the organization on their behalf.

![Deleting an organization](/Images/organization_settings_manage.png)

1. Click **Delete**. A confirmation modal displays.
2. Type the organization name you want to delete.
3. Click **Send code**. An authorization code is emailed to your Platform user account email address.
4. Copy and paste or type the authorization code received in the email into the **Authorization code** field in the modal.
5. Click **I understand that this is a permanent and irreversible. Continue**.