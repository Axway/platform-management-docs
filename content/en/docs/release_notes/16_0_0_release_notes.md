---
title: Platform Management 16.0.0 - 16.9.0 release notes
linkTitle: Platform Management 16.0.0 - 16.9.0 release notes
weight: 47
simple_list: true
date: 2026-04-02
---

New features, improvements, and fixed issues for releases 16.0.0 - 16.9.0.

---

## 16.9.0 - 2 Apr 2026

Platform Management 16.9.0 is a feature release which includes one new feature, several improvements, and one fixed issue.

__New feature__

* Added a *Search Engines* view under Marketplace Integration settings allowing public access Marketplaces to disable search engine indexing or setting a Google Search Console site verification ID.

__Improvements__

* Improved linking to the *Custom Query* view from usage *Report History* table to function when viewing usage for organizations other than for your current session.
* For organizations with a large number of users, the identity provider *Test Mapped Attributes* modal allows entry of an email address rather than prompting selection from a list of users.
* Added consistent tooltips to users in tables to help differentiate those with the same or similar names.

__Fixed issue__

* Fixed an issue where searching by name on the Marketplace *Consumer Organizations* table may only return the first matched organization.

---

## 16.8.2 - 23 Mar 2026

Platform Management 16.8.2 is a patch release which includes one fixed issue.

__Fixed issue__

* Improved validation and error response messages for user account activation link resend endpoint.

---

## 16.8.1 - 20 Mar 2026

Platform Management 16.8.1 is a patch release which includes one fixed issue.

__Fixed issue__

* Restored `onboarding` parameter support on [`GET /org/{org_id}` endpoint](https://platform.axway.com/api-docs.html#tag/org/operation/org_findOne).

{{% alert title="Note" color="primary" %}}
The `onboarding` query parameter is deprecated and will be removed in a future release. Use query parameter `add_fields[]=onboarding` to retrieve `onboarding` data in `GET /org/{org_id}` endpoint responses.
{{% /alert %}}

---

## 16.8.0 - 19 Mar 2026

Platform Management 16.8.0 is a feature release which includes two improvements and one fixed issue.

__Improvements__

* Added support for common `fields`, `add_fields`, and `exclude_fields` query parameters on API endpoints allowing consumers to specify fields to include in responses. Values can be expressed in array format or as comma-delimited strings. E.g., calling `GET /org/{org_id}?fields[]=guid&fields[]=name` and `GET /org/{org_id}?fields=guid,name` return an identical `result` value of `{ "guid": "HHHHHHHH-HHHH-HHHH-HHHH-HHHHHHHHHHHH", "name": "[org name]" }`. See the [API documentation](https://platform.axway.com/api-docs.html) for endpoint specific definitions of allowed and default parameter values.
* Improved performance of identity provider *Test Mapped Attribute* modal in organizations with a large number of users. The modal allows entry of a single user address, rather than prompting selection from a list of existing users.

__Fixed issue__

* Addressed deprecation warning seen in browser console when setting the user's locale for date formatting.

---

## 16.7.2 - 12 Mar 2026

Platform Management 16.7.2 is a patch release which includes one fixed issue.

__Fixed issue__

* Corrected handling for absence of the deprecated `users` field on `PUT /team/{team_id}` endpoint.

---

## 16.7.1 - 5 Mar 2026

Platform Management 16.7.1 is a patch release which includes one improvement and two fixed issues.

__Improvement__

* Updated links in the common navigation menu footer to open in a new tab.

__Fixed issues__

* Fixed an issue where provider organization members signing in from a Marketplace may not be redirectly back to the Marketplace after authenticating.
* Restored display of small non-zero values on the *Monthly Usage* and related views. Previously, small non-integer usage values (specifically Volume) may have been displayed as zero. Non-zero values will now be displayed as `<0.01 GB`.

---

## 16.7.0 - 25 Feb 2026

Platform Management 16.7.0 is a feature release which includes one new feature, two improvements, and one fixed issue.

__New feature__

* Added option to *Custom Query* actions to allow saving an existing query as a new copy.

__Improvements__

* Improved handling of session termination when the user has multiple browser tabs opened on *Platform* views.
* Improved handling of invalid report dates in usage report files.

__Fixed issue__

* Fixed an issue where users who were members of a large number of groups in a configured external identity provider may not have mapped role and team assignments processed as expected.

---

## 16.6.2 - 19 Feb 2026

Platform Management 16.6.2 is a patch release which includes one fixed issue.

__Fixed issue__

* Fixed an issue where email notifications sent to multiple recipients may not be received by all intended recipients.

---

## 16.6.1 - 30 Jan 2026

Platform Management 16.6.1 is a patch release which includes one fixed issue.

__Fixed issue__

* Fixed an issue where Marketplace consumer organization sign-up may not be processed as expected.

---

## 16.6.0 - 20 Jan 2026

Platform Management 16.6.0 is a feature release which includes one improvement and one fixed issue.

__Improvement__

* Added a setting to the Marketplace *Identity Provider Configuration* form to control adding new consumer organization members to their organization's default team.

__Fixed issue__

* Fixed an issue where attempting to remove a domain in the *Identity Providers* table may not function as expected.

---

## 16.5.2 - 12 Jan 2026

Platform Management 16.5.2 is a patch release which includes one improvement and four fixed issues.

__Improvement__

* Improved the granularity of the displayed data when selecting a date range with a chart on the *Custom Query* or other analytics views.

__Fixed issues__

* Fixed an issue where users who are members of only one organization may be shown the *Select Organization* prompt after authenticating.
* Fixed an issue where misconfigured *Identity Provider* default role and team assignments may prohibit users from being provisioned as members of their organization.
* Fixed an issue where selecting a date range with a chart on the *Custom Query* or other analytics views may shift from displaying in local time zone to displaying in UTC.
* Fixed an issue where the Usage *Report History* page may not be displayed as expected for organizations with greater than 10,000 usage report uploads within the selected date range.

---

## 16.5.1 - 18 Dec 2025

Platform Management 16.5.1 is a patch release which includes one fixed issue.

__Fixed issue__

* Fixed an issue where selection of a user to perform an authentication verification flow for an *Identity Provider* configuration may not function as expected.

---

## 16.5.0 - 11 Dec 2025

Platform Management 16.5.0 is a feature release which includes one new feature and one improvement.

__New feature__

* Added the selection of a *Document Library* resource to display as a Marketplace *Console* Getting Started content.

__Improvement__

* Added a prompt to accept local storage access for users in browsers which block third-party cookies.

---

## 16.4.2 - 2 Dec 2025

Platform Management 16.4.2 is a patch release which includes one improvement and one fixed issue.

__Improvement__

* Added the organization's name as a prefix to the downloaded private key file for Platform-generated service account credentials.

__Fixed issue__

* Fixed an issue where provider organization members authenticating from a Marketplace may not be redirected back to the Marketplace after the *Select Organization* prompt.

---

## 16.4.1 - 21 Nov 2025

Platform Management 16.4.1 is a patch release which includes one fixed issue.

__Fixed issue__

* Fixed an issue where authentication and provisioning flows for SAML 2.0 protocol identity provider configurations may not process role and team mappings based on friendly attribute names as expected.

---

## 16.4.0 - 18 Nov 2025

Platform Management 16.4.0 is a feature release which includes one new feature and one fixed issue.

__New feature__

* Added option to set *Console* as the Default Landing Page on *Marketplace Homepage* settings for Marketplaces requiring Protected access.

__Fixed issue__

* Fixed an issue where users displayed in table views may not be updated when paging through the table's content.

---

## 16.3.0 - 30 Oct 2025

Platform Management 16.3.0 is a feature release which includes one new feature and two improvements.

__New feature__

* Added definition for the new `Auditor` role. This role allows read-only access to all resources associated to an organization.

__Improvements__

* Added handling to detect cases when provider organization members attempt to sign in from a Marketplace when currently signed into an organization other than the Marketplace's owner. The user will be redirect to a *Select Organization* prompt with the owning organization selected.
* Improved handling for session invalidation after Marketplace consumer organization members perform self-deletion.

---

## 16.2.3 - 17 Oct 2025

Platform Management 16.2.3 is a patch release which includes one improvement and one fixed issue.

__Improvement__

* Improved post-authentication handling to mitigate an additional full page reload before redirecting to the originating service.

__Fixed issue__

* Updated entitlement definitions to correct reported __Flow Manager__ usage display.

---

## 16.2.2 - 13 Oct 2025

Platform Management 16.2.2 is a patch release which includes several improvements and fixed issues.

__Improvements__

* Removed unnecessary revalidation of a Marketplace URL's CNAME entry unless its value was changed.
* Improved display of error messages during manual usage upload.
* Improved handling for session invalidation after Marketplace consumer organization members perform self-deletion.

__Fixed issues__

* Fixed an issue where configured onboarding fields may not be displayed or captured on the Marketplace *Sign up* form as expected.
* Fixed an issue where setting an invalid value for a user's Identity Provider setting may prohibit the user from signin in.
* Corrected links to __Support Portal__ in the common navigation menus.

---

## 16.2.1 - 30 Sep 2025

Platform Management 16.2.1 is a patch release which includes one fixed issue.

__Fixed issue__

* Fixed an issue where users assigned Engage Admin role may not be able to view all Marketplaces owned by their organization in __Amplify Engage__ services.

---

## 16.2.0 - 24 Sep 2025

Platform Management 16.2.0 is a feature release which includes one new feature and two improvements.

__New feature__

* Added the ability to set visibility for default Marketplace navigation menu entries.

__Improvements__

* Added the ability for users assigned Engage Admin role to view all Marketplaces owned by their organization.
* Improved handling for users performing repeated failed authentication attempts.

---

## 16.1.1 - 17 Sep 2025

Platform Management 16.1.1 is a patch release which includes several fixed issues.

__Fixed issues__

* Fixed an issue where links to *Business Insights* may be included in the common navigation menu entries and on *Platform Home* when the user's role may not grant them access.
* Fixed an issue where importing Marketplace *Footer* settings may not function as expected.
* Corrected validation of uploaded usage report files with invalid file formats or mime types.
* Corrected display of Array type field descriptions in the [API documentation](https://platform.axway.com/api-docs.html).

---

## 16.1.0 - 28 Aug 2025

Platform Management 16.1.0 is a feature release which includes two new features, two improvements, and several fixed issues.

__New features__

* Added the ability to set a Default Landing Page on *Marketplace Homepage* settings.
* Added the ability for provider organization administrators and users assigned Marketplace Manager team role to create Marketplace consumer organizations on their consumers' behalf.

__Improvements__

* Improved handling for users performing repeated failed authentication and device authorization attempts.
* Improved query validation and the display of error messages on the *Custom Query* view.

__Fixed issues__

* Fixed an issue where developer role users may not be able to view their organization's *Monthly Usage* when permitted by the organization's *Security & Privacy* Access Control settings.
* Fixed an issue where queries may not import as expected on the *Custom Query* view.
* Corrected the link to __Axway University__ in the common navigation default *Help & Resources* menu.

---

## 16.0.7 - 14 Aug 2025

Platform Management 16.0.7 is a patch release which includes one fixed issue.

__Fixed issue__

* Fixed an issue where users authenticated via a configured identity provider and which have no roles assigned based on attribute mappings may have manually assigned roles unassigned.

---

## 16.0.6 - 11 Aug 2025

Platform Management 16.0.6 is a patch release which includes one fixed issue.

__Fixed issues__

* Fixed an issue where users authenticated via a configured SAML 2.0 identity provider with roles assigned based on "friendly" attribute mappings may not have the expected roles assigned.

---

## 16.0.5 - 8 Aug 2025

Platform Management 15.0.5 is a patch release which includes one fixed issue.

__Fixed issues__

* Fixed an issue where users authenticated via a configured identity provider may experience an error when attempting to access another org which requires a different identity provider.

---

## 16.0.4 - 7 Aug 2025

Platform Management 16.0.4 is a patch release which includes one fixed issue.

__Fixed issue__

* Fixed an issue where provider org users initiating an authentication flow from their marketplace may not be redirected back to their marketplace after signing in.

---

## 16.0.3 - 6 Aug 2025

Platform Management 16.0.3 is a patch release which includes one improvement.

__Improvement__

* Added support for service accounts to resolve consumer org users using Platform's [`GET /org/{org_id}/user/{user_guid}`](https://platform.axway.com/api-docs.html#tag/org/operation/org_userFindOne) endpoint. Previously, this endpoint only supported user authorization for fetching consumer org users.

---

## 16.0.2 - 28 Jul 2025

Platform Management 16.0.2 is a patch release which includes one fixed issue.

__Fixed issue__

* Restored visibility of *Organization ID* value on the *Organization Overview* for consumer organizations.

---

## 16.0.1 - 23 Jul 2025

Platform Management 16.0.1 is a patch release which includes three fixed issues.

__Fixed issue__

* Fixed an issue where the *Users* and *Teams* views may not be displayed as expected for developer role users in the organization.
* Fixed an issue where the *User Devices* view may not be displayed as expected.
* Fixed an issue where attempting to fetch consumer organizations and their teams using a service account may result in an error.

---

## 16.0.0 - 23 Jul 2025

Platform Management 16.0.0 is a major release which includes several new features, improvements, and fixed issues.

{{% alert title="Note" color="primary" %}}
With this release, some existing roles underwent modifications to their permissions and capabilities:

* *Catalog Manager* and *Developer* team role assignees no longer grants access to *Business Insights*. This permission is granted by assigning a new *Insights Viewer* role.
* *Catalog Manager* team role assignees may no longer approve subscriptions and application registration requests. These permissions are granted by the *Subscription Approver* role and new *API Access Manager* team role respectively.
* *Subscription Approver* team role assignees may no longer approve or manage application registrations. These permissions are granted by the new *API Access Manager*  role.
* *Consumer* organization role assignees may only be assigned *Consumer* or *Subscriber* team roles.

To maintain existing user and service account capabilities:

* *Catalog Manager* team role assignees have been assigned *Subscription Approver*, *API Access Manager*, and *Insights Viewer* roles.
* *Subscription Approver* team role assignees have been assigned *API Access Manager* role.
* *Developer* team role assignees have been assigned the *Insights Viewer* role.

*Consumer* organization role assignees with any of these following team roles have had these team roles unassigned:

* *Catalog Manager*
* *Developer*
* *Subscription Approver*

*Consumer* organization role assignees which need to retain any of these team roles will need to be changed to the *Developer* organization role.

For more information, please refer to the [organization roles and features documentation](https://docs.axway.com/bundle/platform-management/page/docs/management_guide/organizations/organization_roles_and_features/index.html) or [contact support](https://support.axway.com).
{{% /alert %}}

__New features__

* Added new *Insights Viewer* team role which grants access to *Business Insights* views.
* Added new *API Access Manager* team role which grants permission to approve application registration requests.
* Added *Access Control* settings to the *Security & Privacy* view. These allow organization administrators to control developer role assignees visibility of the organization's team, user, environment, and usage data.
* Added ability to configured multiple groupings for queries on the *Customer Query* view.
* Added a "Remember this device" option for users who have multi-factor authentication enabled. Stored devices can be managed on the Account *Devices* view.

__Improvements__

* Extended color customization options captured on the Marketplace *Appearance* view.
* Added stricter content security policy and session cookie storage settings.
* Extended new user activation link expiry from 3 to 90 days.

__Fixed issues__

* Fixed an issue where the common navigation menu's service switcher may not properly link to the *Marketplaces* view.
* Fixed an issue where notifications shown in *Recent Activity* in the top navigation for newly invited or recently removed users may not indicate which user.
* Fixed an issue where previous filter selections may not be reapplied when revisiting certain views.
* Corrected multiple Portuguese language translations.