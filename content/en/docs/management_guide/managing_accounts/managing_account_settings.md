---
title: Managing account settings
linkTitle: Managing account settings
weight: 40
date: 2021-08-12
---
Select **Settings** from the Account left navigation menu. The *Settings* view enables you to manage your account settings. You can configure the following settings:

* Select your account theme (Light, Dark, or Match OS)
* Expand or minimize side-bar menus
* Show or hide getting started content on Platform home
* Select your signed-in organization preference
* Select your inactivity sign-out behavior and timeframe
* Enable or disable restoring the previous page on your next sign in
* Delete your account

## Configure the User Interface (UI) layout

Configure the theme to use on the Platform UI.

* **Light**: light mode. This is the default setting.
* **Dark**: dark mode.
* **MatchOS**: the mode matches your Operating System (OS) if the OS and browser supports it.

## Select the signed-in organization

If you are a member or owner of multiple accounts, to configure the organization to sign in to, select one of the following options from the **Sign-in Organization** dropdown menu:

* **Use last signed-in organization** - You will be signed in to the last organization you signed in to.
* **Use default organization** - You will be signed in to the selected organization on every sign in.
* **Always ask for organization** - You will be prompted to select which organization to sign in to.

To view details of a listed organization, click on the organization name and refer to [Managing Organizations](/docs/management_guide/organizations/managing_organizations/).

## Configure your inactivity sign-out behavior and timeframe

You can configure the amount of time before you are signed out of the Platform due to browser session inactivity. The options are 15 minutes, 30 minutes (default), 1 hour, or Disabled (do not sign me out due to inactivity).

## Enable or disable restoring previous page on next sign in

You can enable or disable if you want to be redirected to the page previously viewed once signed back in after being signed out due to inactivity in the Platform. This setting is disabled by default (do not restore previous page on next sign in).

## Export user data

User data added by the user can be exported.

To export data

1. Click **Generate**. A popup window displays to allow you to choose the items to export.

2. Select the items to export, and then select the activity date range.

3. Click **Continue**.

4. The export is created and listed in a table showing the items the export includes, the user who created the export, when the export was created, and the export status. Completed exports are kept for 30 days before being removed.

5. Click the **Actions (...) menu**, and then select one of the following:

    * **Download** - download a zip file containing the exported data in a json file.
    * **Remove** - delete the export.

## Delete account

The option to delete their account is available for the user if they are not a member of one or more organizations with paid subscriptions. Users and organizations created by sign-up with no subscriptions or trial only subscriptions will see the delete option. If the user deleting their account is the only member of their organization, then their organization will also be deleted.

A user which is a member of one or more organizations which have a Support Access Code must email support@axway.com or visit [Axway Support](https://support.axway.com/) to request Axway to delete the account on their behalf.

![Deleting your account](/Images/account_settings_delete.png)

1. Click **Delete**. A confirmation modal displays.
2. Type the password of your account used to sign in to the Platform.
3. Click **Send code**. An authorization code is emailed to your Platform user account email address.
4. Copy and paste or type the authorization code received in the email into the **Authorization code** field in the modal.
5. Click **I understand that this is a permanent and irreversible. Continue**.