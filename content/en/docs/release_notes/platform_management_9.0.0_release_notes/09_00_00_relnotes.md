---
title: Platform Management 9.0.0 release notes
linkTitle: Platform Management 9.0.0 release notes
weight: 94
date: 2021-12-09
Hide_readingtime: true
---

## Platform Management 9.0.0 - 9 December 2021

Platform Management 9.0.0 is a major release which includes several improvements and one bug fix.

With this release, use of the [https://dashboard.appcelerator.com](https://platform.axway.com) URL to access Platform Management UI or API is no longer supported and requests will issue a redirect to the current URL of [https://platform.axway.com](https://platform.axway.com).

Also, with this release, the _Event Funnels_ feature in _App Analytics_ is no longer available. Users can retrieve event counts using the _Custom Queries_ feature.

## Improvements

* Updated the Platform Management user interface to provide more consistent look and feel, page layouts, tables, and form views with other Amplify Platform services' UIs.
* Updated the layout of the organization _Usage_ view to group entitlements and their usage and quotas under each subscribed product.
* Added improved form validation interactions; fields are now validated during interaction and display messages to help guide users to provide valid inputs.
* Added "dirty form" detection; users are now presented with a confirmation when attempting to navigate away from a form view in which changes have been provided without saving.
* Added Agent and Central asset events to organization _Activity_ view.
* Improved consistency and completeness of response samples in Platform Management API documentation.

## Fixed issue

* Fixed an issue where filters may not apply on the **Mobile Backend Services** Push Notification _Subscribed Devices_ table view.
