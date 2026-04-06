---
title: Platform Management 15.0.0 - 15.3.6 release notes
linkTitle: Platform Management 15.0.0 - 15.3.6 release notes
weight: 48
simple_list: true
date: 2025-07-03
---

New features, improvements, and fixed issues for releases 15.0.0 - 15.3.6.

---

## 15.3.6 - 3 Jul 2025

Platform Management 15.3.6 is a patch release which includes two fixed issues.

__Fixed issues__

* Fixed an issue where users authenticated via a configured identity provider may experience an error when attempting to access another org which requires a different identity provider.
* Fixed an issue where events related to consumer organization self-deletion may not be displayed on the *Marketplace Activity* view.

---

## 15.3.0 - 26 Feb 2025

Platform Management 15.3.0 is a feature release which includes several new features and two fixed issues.

{{% alert title="Note" color="primary" %}}
In an upcoming major release, some existing roles will under modifications to their permissions and capabilities:

* *Catalog Manager* and *Developer* team role assignees may no longer be granted access to *Business Insights*. This permission will be granted by assigning a new *Insights Viewer* role.
* *Catalog Manager* team role assignees may no longer approve subscriptions and application registration requests. These permissions will be granted by the *Subscription Approver* role and new *API Access Manager* team role respectively.
* *Subscription Approver* team role assignees may no longer approve or manage application registrations. These permissions will be granted by the new *API Access Manager*  role.
* *Consumer* organization role assignees may only be assigned *Consumer* or *Subscriber* team roles.

To maintain existing user and service account capabilities:

* *Catalog Manager* team role assignees will gain the *Subscription Approver*, *API Access Manager*, and *Insights Viewer* roles.
* *Subscription Approver* team role assignees will gain the *API Access Manager* role.
* *Developer* team role assignees will gain the *Insights Viewer* role.

*Consumer* organization role assignees with any of these following team roles will have these team roles unassigned:

* *Catalog Manager*
* *Developer*
* *Subscription Approver*

*Consumer* organization role assignees which need to retain any of these team roles will need to be changed to the *Developer* organization role.

For more information, please refer to the [organization roles and features documentation](https://docs.axway.com/bundle/platform-management/page/docs/management_guide/organizations/organization_roles_and_features/index.html) or [contact support](https://support.axway.com).
{{% /alert %}}

__New features__

* Added a banner to organization, user, and service account management views regarding upcoming role modifications.
* Added warning indicators for users and service accounts which will be impacted by upcoming role modifications.
* Added grouped display of correlated __SecureTransport__ Transfer metrics on *Monthly Usage* view.
* Added an interstitial message after usage entry or upload regarding data propagation delay on *Usage* views and prompting to use the refresh control if needed.

__Fixed issues__

* Fixed an issue where users for which use of a specific identity provider was required to access their organization may not be redirected as expected.
* Correct multiple French language translations.

---

## 15.0.0 - 7 Oct 2024

Platform Management 15.0.0 is a major release which includes two new features.

{{% alert title="Note" color="primary" %}}
With this release, all navigation elements, *Platform Home* tasks and capabilities, and metrics on the *Overview* page related to __Unified Catalog__ have been removed.
{{% /alert %}}

__New features__

* Added support for French, Brazilian Portuguese, and German languages.
* Added capture for French, Brazilian Portuguese, and German language naming and content in *Marketplace* settings views.
