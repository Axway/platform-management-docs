---
title: Adding a service account with the UI
linkTitle: Adding a service account with the UI
weight: 10
date: 2023-09-13
---
1. Sign into the Amplify platform and select **Organization** from the *User* dropdown menu.
2. Click **Service Accounts** from the left navigation.
3. Click **+ Service Account** at the top right.
4. Complete the following fields:
    * **Name** - Provide a name for your service account. If this account is used for usage reporting for one or more products and you intent to have different accounts for different environments, a good illustrative naming pattern could be `<product name>_<environment>_usage`.
    * **Authentication Method** - Client Certificate or Client Secret. If this account is used for usage reporting, validate the authentication option the product supports.
        * Select either to provide the credentials or have them platform generated.
    * **Org Roles** - Select the role this service account should have. If this account is set up for usage reporting, select Usage Reporter.
    * **Teams** - Select the roles the service account should have in the various teams. If this account is set up for usage reporting, no adjustments have to be made.
5. Click **Save**. If you selected the authentication details to be platform issued, a dialog is displayed that allows you to view or copy the generated secret, or download the private key if you selected Client Certificate as the authentication option. Store the generated Secret or Private Key details in a safe place, as this is the only time you will be able to obtain these from the platform.
6. Now that your service account has been created, use your client Id and secret or certificate to authenticate to the platform.