---
title: Enabling an Identity Provider for multiple organizations
linkTitle: Enabling multi-org Identity Provider
weight: 45
date: 2022-04-21
---

After an Identity Provider has been configured and enabled for an organization, you can associate an email domain and Identity Provider with any other organizations that your domain users use. This allows you to use the provisioning, role, and team management capabilities across all of your platform organizations.

Complete the following steps to add your existing Identity Provider to other organizations of which you are an administrator.

## Prerequisites

Complete the documentation for establishing domains and Identity Providers for an **initial** organization through [Enabling Identity Provider configuration](/docs/management_guide/configuring_and_managing_identity_providers/enabling_identity_provider_configuration).

{{% alert title="Note" color="primary" %}}Tasks in step 1a\* (add and verify a domain) or step 1b\* (configure an IdP) can be completed in any order.

| Complete (**✓)** | Step | Task |
| --- | --- | --- |
| - | 1a\* | [Add a domain](/docs/management_guide/configuring_and_managing_identity_providers/managing_domains/adding_a_domain/) and [Verify domain ownership](/docs/management_guide/configuring_and_managing_identity_providers/managing_domains/verifying_domain_ownership/) |
| - | 1b\* | Configure an [OIDC](/docs/management_guide/configuring_and_managing_identity_providers/managing_identity_provider_configuration/configuring_an_openid_connect_idp/) or [SAML v2.0](/docs/management_guide/configuring_and_managing_identity_providers/managing_identity_provider_configuration/configuring_a_saml_v2.0_idp/) IdP |
| - | 2 | [Confirm the association of an IdP to the domain](/docs/management_guide/configuring_and_managing_identity_providers/enabling_identity_provider_configuration/confirming_the_association_of_an_idp_to_the_domain/) |
| - | 3 | [Enable the IdP configuration for all domain users](/docs/management_guide/configuring_and_managing_identity_providers/enabling_identity_provider_configuration//enabling_idp_configuration_for_all_domain_users) |{{% /alert %}}

## Adding additional organizations

After the initial organization is configured, complete the following steps for **additional** organizations.

1. Complete the steps to [add a domain](/docs/management_guide/configuring_and_managing_identity_providers/managing_domains/adding_a_domain/) and [verify domain ownership](/docs/management_guide/configuring_and_managing_identity_providers/managing_domains/verifying_domain_ownership/) for the domain(s) you want to use the existing Identity Provider for.

2. In the Identity Provider page, select **Associate to Another Organization's IdP** from the **Actions** (**...**) menu for the domain from the *Email Domain* table. The *Associate with Another Organization's Identity Provider* modal appears showing the Identity Providers and their existing organizations that you are able to associate with the additional organization.

    ![Associate](/Images/multiorg_idp_associate.png)

3. Click **Associate**. The *Association Created* confirmation modal appears.

4. Click **Close**. After associating the intended Identity Provider with the additional organization, the domain status is updated to *Associated* in the Email Domains table and the Identity Provider is added to the Identity Providers table.

5. Follow the [role assignments](/docs/management_guide/configuring_and_managing_identity_providers/managing_identity_provider_configuration/role_assignments) documentation for the Identity Provider in the additional organization(s).

    {{% alert title="Note" color="primary" %}}For convenience, the Identity Provider's default organization role configuration and any role mappings configured for the initial organization are preconfigured for the additional organization(s). However, no default team associations or team mapping configurations are initially created for the additional organization(s), therefore they must be manually configured.{{% /alert %}}

6. After you have completed the Identity Provider configuration for the additional organization(s), complete the [steps](/docs/management_guide/configuring_and_managing_identity_providers/enabling_identity_provider_configuration//enabling_idp_configuration_for_all_domain_users) to enable its use for all users on the domain in the additional organization(s).