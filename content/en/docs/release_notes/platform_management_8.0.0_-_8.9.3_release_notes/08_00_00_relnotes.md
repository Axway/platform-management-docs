---
title: Platform Management 8.0.0 release notes
linkTitle: Platform Management 8.0.0 release notes
weight: 224
date: 2021-08-12
Hide_readingtime: true
---

## Platform Management 8.0.0 - 17 July 2020

Platform Management 8.0.0 is a major release, which includes new features, improvements, and one bug fix.

Please note that browser support for Amplify Platform has been changed to no longer support Apple Safari 11.0 and below (version 11.1 or later is supported) or Microsoft Edge 16 and below. Please visit [https://platform.axway.com/browser](https://platform.axway.com/browser) for the list of supported browsers and versions.

## New features

* This release introduces a new **Amplify Platform** on-boarding experience and an all-new _Amplify Platform_ Home. _Amplify Platform Home_ now lists the capabilities to which your organization has access as well as common tasks available for those capabilities. Users can explore more offerings on a streamlined _Products and Services_ page.
* The common header (aka Unified Nav) has also been improved. A new _Help & Resources_ dropdown provides links to document, support, and other resources. Once logged in, the header now shows new services menu on the left, allowing users to quickly switch between various Platform capabilities and their UIs, and a simplified user menu on the right, now showing your assigned role.
* During activation of newly signed up users, a new page is now presented, asking which Amplify Platform capabilities the org wishes to use. Feature trials will be automatically requested for the selected capabilities.
* For organizations primarily using **API Management** capabilities, the Dashboard link on the _Amplify Platform Home_ page will now link to the new _Amplify Visibility_ UI. This new UI requires assignment of the "Analytics Specialist" role in order to access it.

## Improvements

* Navigation between the _Dashboard_, _Overview_, and _Custom Queries_ views has changed from a left-hand menu.
* The link for the _Download Premium Modules_ view has been relocated to the Dashboard left-hand menu.
* Display of long app names of the Apps table is improved.
* The Add (+) menu items for "Register App for Services" and "Create MBS Datasource" previously in the common header have been relocated to the _Apps_ view's right-hand actions menu.
* Added a "Manage Subscriptions" link to the _Organization Overview_ above the Subscriptions table for on-demand organizations to manage their subscriptions.
* Added support for indicating which administrator member of an organization is its primary contact on the organization _Members_ view.
* The organization _Members_ view's Roles list now displays the reason why a role may not be available. E.g, if all seats for a given role are occupied, a "Seat limit reached" message is shown.

## Fixed Issues

* Fixed an issue where attempting to add an existing platform user to a new or different organization may not behave as expected.
