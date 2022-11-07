---
title: Managing credentials
linkTitle: Managing credentials
weight: 30
date: 2021-08-12
---
Select **Credentials** from the Account left navigation menu. The *Credentials* view is where you can change your account password and enable or disable multi-factor authentication. 

If your organization is using an Identity Provider, the Credentials link takes you to the view where you can create and change the password you use for tooling. Refer to [Configuring Tooling Credentials](/docs/management_guide/configuring_and_managing_identity_providers/configuring_tooling_credentials).

## Change your password

To change your password:

1. Click **Credentials**.
2. Enter a new password in the **Change Password** field. The password should be at least eight characters (default requirements) or must adhere to any password policies configured for your organization. As you enter a new password in the **Change Password** field, the **Confirm Password** field is displayed.
    ![Change and confirm password](/Images/change_password_latest.png)
3. Confirm the new password in the **Confirm Password** field. The entry in the **Confirm Password** field must be the same as the entry in the **Password** field.
4. Select the **Force Logout** checkbox to force the log out of any current sessions.
5. Click the **Save** button. The password change is saved and an Account Information Changed notification email is sent.

## Manage multi-factor authentication

Enable multi-factor authentication for increased security with authentication verification by an authenticator app or email. Using MFA is optional, but **highly recommended.**

MFA definition (from Wikipedia)

*Multi-factor authentication (MFA; encompassing Two-factor authentication or 2FA, along with similar terms) is an  **electronic authentication method** in which a computer user is granted access to a website or application only after successfully  **presenting two or more pieces of evidence** (or factors) to an authentication mechanism: knowledge (something only the user knows), possession (something only the user has), and inherence (something only the user is). MFA protects the user from an unknown person trying to access their data such as personal ID details or financial assets. A third-party authenticator (TPA) app enables two-factor authentication, usually by showing a randomly-generated and constantly refreshing code to use for authentication.*

Multi-factor authentication in the Amplify Platform is possible when your user account is managed in the Platform. If your account is managed by an external Identity Provider, then MFA is handled by that component.

To enable multi-factor authentication:

1. Click **Credentials**.
2. Select **Enabled** next to the **Multi-Factor Authentication** option. The **Preferred MFA Method** options becomes available.
3. For the **Preferred MFA Method**, select the default method a multi-factor authentication token will be generated for when logging in from a new device. Options are **Authenticator App** and **Email**.

    | Preferred MFA method | How this works | When can this be used |
    | ---| --- | --- |
    | Authenticator App | A random code is generated within the app that needs to be provided when the user logs into the Platform. | Only available when an authenticator app has been configured for your account. See [Setup Authenticator App](#setup-authenticator-app) for details. |
    | Email | A code is sent to your email address that needs to be provided when the user logs into the Platform. | Always available, uses the email address linked to your account. |

4. Click **Save**. Once the Enabled checkbox is selected and the account saved, multi-factor authentication will be enabled, and a notification email will be sent.

5. To complete configuration for the Authenticator app, complete the steps in [Setup Authenticator App](#setup-authenticator-app).
6. After you have enabled MFA and you login you will see a notification asking you to enter an authorization code. You might need to use another browser or a private browser session to test this. Enter the Authorization code provided by your Authenticator App or email, and then click **Authorize**.

    When the code is correctly validated, you will be successfully logged into the Platform.

To disable multi-factor authentication:

1. Click **Credentials**.
2. Deselect **Enabled** next to the **Multi-Factor Authentication** option.
3. Click **Save**.

Once the **Enabled** checkbox is deselected and the account saved, multi-factor authentication is disabled and a notification email is sent.

## Setup Authenticator App

Use an Authenticator App such as Google Authenticator or Microsoft Authenticator.

To setup an authenticator app:

1. Install an Authenticator App.
2. In the Platform, select the Credentials link in the **Account** menu.
3. Click **Configure** next to **Set up Authentication App**. A popup appears with a QR code.
4. Scan the QR code with your Authenticator App.
5. Type the code from the Authenticator App into the modal dialog, and then click **Submit**. The Authenticator App is now configured.