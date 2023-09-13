---
title: Editing a service account with the UI
linkTitle: Editing a service account with the UI
weight: 15
date: 2023-09-13
---
1. Sign into the Amplify platform and select **Organization** from the *User* dropdown menu.
2. Click **Service Accounts** from the left navigation.
3. Select one of the existing Service Account definitions by clicking on the name.
4. Edit any of the following values:
    * **Name**
    * **Description**
    * **Credentials** - The original selected authentication method is locked.
    * **Org Roles** - Select the role this service account should have. If this service account is set up for usage reporting, select Usage Reporter.
    * **Teams** - Select the roles the service account should have in the various teams. If this account is set up for usage reporting, no adjustments have to be made.
5. Click **Save**. If you selected the authentication credentials to be platform generated, a dialog is displayed that allows you to view or copy the generated secret, or download the private key if you selected Client Certificate as the authentication option. Store the credential details, as this is the only time it will ever be displayed.
6. Now that your service account has been updated, use your client Id and secret or certificate to authenticate to the platform.