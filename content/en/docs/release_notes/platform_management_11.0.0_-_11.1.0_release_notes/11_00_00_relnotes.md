---
title: Platform Management 11.0.0 release notes
linkTitle: Platform Management 11.0.0 release notes
weight: 68
date: 2022-08-31
Hide_readingtime: true
---

## Platform Management 11.0.0 - 01 Sep 2022

Platform Management 11.0.0 is a major release which includes two new features and three fixed issues.

This release corresponds with the **Mobile Backend Services** and **Amplify Runtime Services** End-of-Support [initially announced February 24, 2021](https://blog.axway.com/learning-center/software-development/api-development/prepare-your-apps-for-appcelerator-end-of-support#mobile-backend-services). Support for applications' use of these services has been discontinued. Access to manage **Runtime Services** applications and **Mobile Backend Services** data is no longer available within **Platform Management** UI. Access to the **Mobile Backend Services** APIs and applications deployed on **Amplify Runtime Services** will be terminated effective 07 Sep 2022. Existing **Cloud Capacity** subscriptions have been terminated effective 01 Sep 2022.

Additionally, location based analytics are no longer supported and map as an analytics display type has been removed with this release.

## New feature

* Added Subscription Approver as an assignable team role allowing more granular control when granting Marketplace Subscription and Access Request permissions. See the [Team roles documentation](https://docs.axway.com/bundle/platform-management/page/docs/management_guide/organizations/organization_roles_and_features/index.html#team-roles) for more information.
* Added Stream as a display type on the *Custom Query* view when Find is the selected method.

## Fixed issues

* Fixed an issue where users authenticating to various Axway portals may not be returned to their initial destination after logging in.
* Fixed an issue where the *Events* metric overview may not display event names when grouped by name.
* Fixed an issue where navigating between app analytics views may not function as expected.
