---
title: Platform Management 9.0.0 - 9.2.2 release notes
linkTitle: Platform Management 9.0.0 - 9.2.2 release notes
weight: 90
simple_list: true
date: 2021-08-12
---

New features, improvements, and bug fixes for releases 9.0.0 - 9.2.2.

---

## 9.2.2 - 18 February 2022

Platform Management 9.2.2 is a patch release which includes two fixed issues.

__Fixed issues__

* Fixed an issue where org *Activity* view events for updating a team member's roles or removing a member from a team may not state which member was affected.
* Fixed an issue where __Amplify Runtime Services__ app *Overview* view may not render for unpublished apps.

---

## 9.2.1 ❤️ 14 February 2022

Platform Management 9.2.1 is a patch release which includes a new feature and a fixed issue.

__New feature__

* Added abiltiy to download a published __Amplify Runtime Services__ app (not available for apps published with `--type image`) or manage its CNAME setting.

__Fixed issue__

* Removed an unneeded Environment filter on __Amplify Runtime Services__ app *Analytics* view.

---

## 9.2.0 - 10 February 2022

Platform Management 9.2.0 is a minor release which includes a new feature and several fixed issues.

__New feature__

* Added a *Devices* view in the *Account* section for users using __Amplify platform__ for authentication allowing authorized devices to be viewed and managed.

__Fixed issues__

* Fixed an issue where usage of __Cloud Capacity__ subscription entitlements may fail to load on the *Manage Subscriptions* service.
* Fixed an issue where a banner on the *Users* view indicating an org had unavailable roles assigned to its members may persist when switching between orgs.
* Corrected an outdated *Connecting Environments* documentation link on the *Platform Home* Getting Started section.

---

## 9.1.1 - 31 January 2022

Platform Management 9.1.1 is a patch release which includes an improvement and several fixed issues.

{{% alert title="Note" color="primary" %}}
Supported browser versions have been updated with the release. Support for Firefox ESR 91 has been reinstated. Support for Google Chrome Enterprise versions prior to 87 has been ended. Please see the [Supported Browsers page](https://platform.axwaytest.net/browser) for more information.
{{% /alert %}}

{{% alert title="Note" color="primary" %}}
With the upcoming [End-of-Support for Titanium SDK](https://blog.axway.com/mobile-apps/changes-to-application-development-services), subscriptions for __Application Development__ have been updated to set a termination date of March 1, 2022. Please see the [End-of-Support accouncement](https://blog.axway.com/mobile-apps/changes-to-application-development-services) for more information.
{{% /alert %}}

__Improvements__

* Improved usability of left menu on small screen sizes.

__Fixed issues__

* Fixed an issue where users authenticating in Axway CLI using an Identity Provider may experience a timeout error.
* Fixed an issue on the *Usage Report History* table view where the number of files may be incorrectly reported on initial access.
* Fixed an issue on the *New User* and *Manage User* views where the Central Admin role may have been assignable on users which were not assigned a Platform role of Developer or Administrator.

---

## 9.1.0 - 20 January 2022

Platform Management 9.1.0 is a minor release which includes several improvements and fixed issues.

__Improvements__

* Added filters for Environment and file Status on the *Usage Report History* table view.
* *Organization Overview* Subscriptions table no longer shows zero value entitlements.
* Changed Team name validation to allow use of special characters.
* Improved usability of date input fields by allowing direct entry.

__Fixed issues__

* Fixed an issue where navigating from __Mobile Backend Services__ data table details to a related object may cause an error.
* Fixed an issue where paging through objects in __Mobile Backend Services__ data tables may not behave as expected.
* Fixed an issue where API Management analytics views may not show friendly event names.

---

## 9.0.5 - 6 January 2022

Platform Management 9.0.5 is a patch release which includes two fixed issues.

__Fixed issues__

* Fixed an issue where users associated to an external identity provider may be prompted to provide their current password when setting Tooling Credentials.
* Fixed an issue where users who are not assigned org Administrator role may not be able to edit teams in which they are assigned Administrator role.

---

## 9.0.4 - 17 December 2021

Platform Management 9.0.4 is a patch release which includes one improvement and one fixed issue.

__Improvement__

* Added validation to *Identity Provider Configuration* form to require https protocol for all URLs.

__Fixed issue__

* Fixed an issue where __Mobile Backend Services__ *Manage Data* tables may not show the correct object counts as a user pages through objects.

---

## 9.0.3 - 16 December 2021

Platform Management 9.0.3 is a patch release which includes one improvement and one fixed issue.

__Improvement__

* *Organization Overview* Subscriptions table no longer shows zero value entitlements.

__Fixed issue__

* Fixed an issue where a user's Team membership may not save as expected.

---

## 9.0.2 - 15 December 2021

Platform Management 9.0.2 is a patch release which includes one improvement and three fixed issues.

__Improvement__

* *Usage Entry* view no longer shows entitlements which have a zero value quota.

__Fixed issues__

* Fixed an issue where __Mobile Backend Services__ datasource links on the *All Apps* table may show an error for datasources in a (VPC) service environment.
* Fixed an issue where __Mobile Backend Services__ *Manage Data* tables may not be filterable by a Custom Field.
* Fixed an issue where users who are members of multiple orgs may not be able to directly access app views for an app in an org they are not signed in to.

---

## 9.0.1 - 10 December 2021

Platform Management 9.0.1 is a patch release which includes one improvement and two fixed issues.

__Improvement__

* Improved label colors for toggle controls in dark theme.

__Fixed issues__

* Fixed an issue where users may not be able to reset their password if they forgot their credentials.
* Fixed an issue where events shown on *Activity* views may not link to the user who performed the action.

---

## 9.0.0 - 9 December 2021

Platform Management 9.0.0 is a major release which includes several improvements and one bug fix.

{{% alert title="Note" color="primary" %}}
With this release, use of the [https://dashboard.appcelerator.com](https://platform.axway.com) URL to access Platform Management UI or API is no longer supported and requests will issue a redirect to the current URL of [https://platform.axway.com](https://platform.axway.com).
{{% /alert %}}

{{% alert title="Note" color="primary" %}}
Also, with this release, the *Event Funnels* feature in *App Analytics* is no longer available. Users can retrieve event counts using the *Custom Queries* feature.
{{% /alert %}}

__Improvements__

* Updated the Platform Management user interface to provide more consistent look and feel, page layouts, tables, and form views with other Amplify Platform services' UIs.
* Updated the layout of the organization *Usage* view to group entitlements and their usage and quotas under each subscribed product.
* Added improved form validation interactions; fields are now validated during interaction and display messages to help guide users to provide valid inputs.
* Added "dirty form" detection; users are now presented with a confirmation when attempting to navigate away from a form view in which changes have been provided without saving.
* Added Agent and Central asset events to organization *Activity* view.
* Improved consistency and completeness of response samples in Platform Management API documentation.

__Fixed issue__

* Fixed an issue where filters may not apply on the __Mobile Backend Services__ Push Notification *Subscribed Devices* table view.
