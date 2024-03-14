---
title: Platform Management 11.0.0 - 11.1.0 release notes
linkTitle: Platform Management 11.0.0 - 11.1.0 release notes
weight: 70
simple_list: true
date: 2021-08-12
---

New features, improvements, and bug fixes for releases 11.0.0 - 11.1.0.

---

## Platform Management 11.1.0 - 15 Sep 2022

Platform Management 11.1.0 is a minor release which includes two new features.

{{% alert title="Note" color="primary" %}}
With this release, API endpoints related to **Application Development** offering support have been marked as deprecated. They will be removed in a future release. Please see the [Platform API documentation](https://platform.axway.com/api-docs.html) for the set of deprecated endpoints.
{{% /alert %}}

### New features

* Added the ability for users and organizations created through signup to delete themselves. This option is available on *Account Settings* for users and on a new *Manage* view under *Settings* for organizations. This ability is only available for organizations and their members with no active or expired paid subscriptions and no Support Access Code set on the organization.
* Added the ability to view and download an event on the organization, user, and app *Activity* views as well as download the page of displayed events.

---

## Platform Management 11.0.0 - 01 Sep 2022

Platform Management 11.0.0 is a major release which includes two new features and three fixed issues.

{{% alert title="Note" color="primary" %}}
This release corresponds with the **Mobile Backend Services** and **Amplify Runtime Services** End-of-Support [initially announced February 24, 2021](https://blog.axway.com/learning-center/software-development/api-development/prepare-your-apps-for-appcelerator-end-of-support#mobile-backend-services). Support for applications' use of these services has been discontinued. Access to manage **Runtime Services** applications and **Mobile Backend Services** data is no longer available within **Platform Management** UI. Access to the **Mobile Backend Services** APIs and applications deployed on **Amplify Runtime Services** will be terminated effective 07 Sep 2022. Existing **Cloud Capacity** subscriptions have been terminated effective 01 Sep 2022.
{{% /alert %}}

{{% alert title="Note" color="primary" %}}
Additionally, location based analytics are no longer supported and map as an analytics display type has been removed with this release.
{{% /alert %}}

### New feature

* Added Subscription Approver as an assignable team role allowing more granular control when granting Marketplace Subscription and Access Request permissions. See the [Team roles documentation](https://docs.axway.com/bundle/platform-management/page/docs/management_guide/organizations/organization_roles_and_features/index.html#team-roles) for more information.
* Added Stream as a display type on the *Custom Query* view when Find is the selected method.

### Fixed issues

* Fixed an issue where users authenticating to various Axway portals may not be returned to their initial destination after logging in.
* Fixed an issue where the *Events* metric overview may not display event names when grouped by name.
* Fixed an issue where navigating between app analytics views may not function as expected.
