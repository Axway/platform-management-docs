---
title: Getting started with Identity Providers
linkTitle: Getting started with Identity Providers
weight: 10
date: 2021-08-12
---

An organization administrator completes all tasks related to configuring and managing identity providers and associated domains from the Organization's Settings - **Identity Provider** tab in the Platform.

### Prerequisites

You must have an OpenID Connect (OIDC) or SAML v2.0 compatible Identity Provider and DNS access to the domain the IdP is for.

Before configuring a new Identity Provider, you must ensure:

* At least one user whose email address is on the domain for which the Identity Provider is being configured has been invited to or is an existing member of the organization.
* You have the necessary permissions to access and edit your Identity Provider to complete this configuration.

### Accessing the Identity Provider (IdP) page

1. Sign in to the [Platform](https://platform.axway.com/).
2. Click on the **Profile** menu and select **Organization**.
3. Click the **Settings** link from the left navigation.
4. Click the **Identity Provider** link. When you access the *Identity Provider* page for the first time, you will see a message that the organization is currently using the {{% variables/platform_prod_name %}} for authentication.
    ![You are currently using the {{% variables/platform_prod_name %}} as your Identity Provider message](/Images/overview_new_dropdown.png)
5. If you are a member of multiple organizations, select the organization from the *Organization* dropdown menu.

### Next steps

The following tasks must be completed, in any order, before an Identity Provider can be tested and enabled for an organization:

* Configure Identity Providers: [configure an OpenID Connect IdP](/docs/management_guide/configuring_and_managing_identity_providers/managing_identity_provider_configuration/configuring_an_openid_connect_idp) or [configure a SAML v2.0 IdP](/docs/management_guide/configuring_and_managing_identity_providers/managing_identity_provider_configuration/configuring_a_saml_v2.0_idp/).
* [Add a domain](/docs/management_guide/configuring_and_managing_identity_providers/managing_domains/adding_a_domain/) and [verify domain ownership](/docs/management_guide/configuring_and_managing_identity_providers/managing_domains/verifying_domain_ownership/).

After you have configured an Identity Provider and domain ownership is verified you must [confirm the association of an IdP to the domain](/docs/management_guide/configuring_and_managing_identity_providers/enabling_identity_provider_configuration/confirming_the_association_of_an_idp_to_the_domain/), and then you can [enable IdP configuration for all domain users](/docs/management_guide/configuring_and_managing_identity_providers/enabling_identity_provider_configuration/enabling_idp_configuration_for_all_domain_users/) and optionally [add a subdomain](/docs/management_guide/configuring_and_managing_identity_providers/managing_domains/adding_a_subdomain/). The following is an example of the Identity Providers page once all steps are completed with configuring multiple Identity Providers for an organization.

![Multiple Identity Providers configured](/Images/multiple_idps_configured.png)

After an Identity Provider and domain has been added and configured, you can complete the following tasks:

* [Enable multi-org Identity Provider](/docs/management_guide/configuring_and_managing_identity_providers/enabling_identity_provider_multiple_orgs)
* [Optionally configure off-domain users to use an IdP](/docs/management_guide/configuring_and_managing_identity_providers/requiring_identity_provider_use)
* [Remove a domain](/docs/management_guide/configuring_and_managing_identity_providers/managing_domains/removing_a_domain/)
* [Dissociate a Domain](/docs/management_guide/configuring_and_managing_identity_providers/managing_domains/dissociating_a_domain/)
* [Delete an Identity Provider configuration](/docs/management_guide/configuring_and_managing_identity_providers/managing_identity_provider_configuration/deleting_an_identity_provider_configuration/)
