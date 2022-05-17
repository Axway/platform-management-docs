---
title: Requiring Identity Provider use
linkTitle: Requiring Identity Provider use
weight: 45
date: 2022-05-16
---

As well as associating users on specific domains to use a configured Identity Provider, users on domains other than ones associated to the organization can be individually configured to require use of a specified Identity Provider to access an organization.

This allows collaboration with partners with email addresses outside of owned domains while still applying your Identity Provider's authentication restrictions, even if the partner is already a member of another organization in the Amplify Platform.

{{% alert title = "Note" color = "primary" %}} The off-domain user needs to be configured with the Identity Provider before they are able to use it to authenticate with the Amplify Platform.{{% /alert %}}

To configure a user to require use of an Identity Provider:

1. Follow the steps to invite a new user or modify an existing user’s access to your organization. Refer to [Managing users](/docs/management_guide/organizations/managing_organizations/#managing-users) for details.
2. If an Identity Provider has been configured for the organization, then the user invite form displays an *Identity Provider* dropdown. Select the Identity Provider the user should be required to use to access the organization.

    ![Select an Identity Provider](/Images/idp_new_user_form.png)
    
3. An email invitation or notification is sent to the user providing a link to log in using the selected Identity Provider.

Upon subsequent logins to the Amplify Platform, if the invited user attempts to authenticate and access the organization using an Identity Provider other than the one configured, a message appears that they must re-authenticate using the configured Identity Provider.

![Authenticate with IdP during sign in](/Images/idp_signin_restricted.png)

Also, if a user attempt to switch to the organization from another having initially authenticated with an Identity Provider other than the one configured, they will similarly be prompted to re-authenticate.

![Authenticate with IdP when switching orgs](/Images/idp_switch_org_restricted.png)