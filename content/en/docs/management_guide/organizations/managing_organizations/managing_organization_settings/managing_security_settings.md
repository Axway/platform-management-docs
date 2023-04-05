---
title: Managing security settings
linkTitle: Managing security settings
weight: 30
date: 2021-08-12
---
Redact personal information and configure password policy rules to add to the default password requirements.

Click **Security** from the Organization - Settings menu to access organization security settings. Then, select the organization from the *Organization* dropdown menu to configure the following settings for the specified organization.

![Managing organization settings](/Images/settings_tab_security.png)

## Redact personal information

Select the option to **Redact Personal Information** to redact email addresses within an organization where the user's email address is displayed, except the *Account* view. The email address on the *Account* view is always redacted, whether the setting is enabled or disabled. By default, the setting is disabled.

## Configure password settings

Administrators have the option to configure additional password settings to add to the default password requirements.

* **Minimum Password Length** - Minimum number of characters a password must contain.
* **Password Complexity** - Select the option to require at least one character of the following type to be included in the password, or select **Advanced** to specify the number of required characters.

    * Lower case characters
    * Upper case characters
    * Special characters
    * Digits
* **Renewal period** - Number of days after which a user must change their password.
* **Not Recently Used** - Number of times a unique password is required before a previously used password can be reused.
* **Account Lock Out** - Number of times a user can attempt to sign in with an incorrect password before the account is locked.