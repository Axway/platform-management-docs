---
title: Sign in
linkTitle: Sign in
weight: 20
date: 2021-08-12
---

This page includes {{% variables/platform_prod_name %}} instructions to sign in using single sign-on (SSO) or your {{% variables/platform_prod_name %}} password. Follow the applicable sign-on instructions for your organization's configuration.

## Sign in with single sign-on (SSO)

Use the following sign-in instructions if your organization has the single sign-on (SSO) feature enabled and its [identity provider configured](/docs/management_guide/configuring_and_managing_identity_providers/).

**To sign in to the {{% variables/platform_prod_name %}} using single sign-on:**

1. Navigate to [https://platform.axway.com](https://platform.axway.com/). The *Sign In* page is displayed.
2. Enter the email address associated with your account. If your organization's [identity provider configuration](/docs/management_guide/configuring_and_managing_identity_providers/) has your email domain associated, you will be forwarded to your company's identity provider to continue the sign-in process. If you do not have an {{% variables/platform_prod_name %}} account, [contact support](https://support.axway.com/en/auth/contacts) with your organization's Support Access Code to request access.
3. Enter your organization account password and click **Sign In**. Clicking **Sign In** will forward you to the {{% variables/platform_prod_name %}} home page. For an overview of the {{% variables/platform_prod_name %}}, refer to the [Amplify Platform Overview](/docs/management_guide/overview/).

## Sign In with your Amplify Platform password

Use the following sign-in if your organization does not have the single sign-on (SSO) feature entitled or enabled or its identity provider configured.

**To sign in to the {{% variables/platform_prod_name %}} using your {{% variables/platform_prod_name %}} password:**

1. Navigate to [https://platform.axway.com](https://platform.axway.com/). The *Sign In* page is displayed.
2. Enter the email address associated with your account. If you do not have an {{% variables/platform_prod_name %}} account, [contact support](https://support.axway.com/en/auth/contacts) with your organization's Support Access Code to request access.
3. Click **Next**. Clicking Next will forward you to the {{% variables/platform_prod_name %}} *Sign In* page.
4. Enter the password associated with your {{% variables/platform_prod_name %}} account and click **Sign In**.
5. If you are using multi-factor authentication, and the device or browser you are using has not been authenticated, you must provide an authorization code. If requested, enter the authorization code sent to you by email or an authenticator app (shown in the example image) associated with your account and click **Authorize**.

    ![Device authorization modal](/Images/device_authorization.png)

6. If you are a member of multiple organizations, you may be forwarded to the *Select Organization* page. You can configure the sign-in organization preference from your Account - Settings page. Refer to the [Select the org rule](/docs/management_guide/managing_accounts/#select-the-sign-in-organization) section in Managing Accounts.
    ![Select organization modal](/Images/multiple_orgs.png)
7. Select the organization to sign in to from the Select Organization drop-down menu.
8. Click **Continue**. Clicking **Continue** will forward you to the {{% variables/platform_prod_name %}} home page. For an overview of the {{% variables/platform_prod_name %}} refer to the [Amplify Platform Overview](/docs/management_guide/overview/).
