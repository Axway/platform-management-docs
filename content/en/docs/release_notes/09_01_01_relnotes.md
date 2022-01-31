---
title: Platform Management 9.1.1 release notes
linkTitle: Platform Management 9.1.1 release notes
description: Improvement and bug fixes for the release.
weight: 87
date: 2022-01-31
Hide_readingtime: true
---

## Platform Management 9.1.1 - 31 January 2022

Platform Management 9.1.1 is a patch release which includes an improvement and several fixed issues.

Supported browser versions have been updated with the release. Support for Firefox ESR 91 has been reinstated. Support for Google Chrome Enterprise versions prior to 87 has been ended. Please see the [Supported Browsers page](https://platform.axwaytest.net/browser) for more information.

With the upcoming [End-of-Support for Titanium SDK](https://blog.axway.com/mobile-apps/changes-to-application-development-services), subscriptions for **Application Development** have been updated to set a termination date of March 1, 2022. Please see the [End-of-Support accouncement](https://blog.axway.com/mobile-apps/changes-to-application-development-services) for more information.

## Improvements

* Improved usability of left menu on small screen sizes.

## Fixed issues

* Fixed an issue where users authenticating in Axway CLI using an Identity Provider may experience a timeout error.
* Fixed an issue on the _Usage Report History_ table view where the number of files may be incorrectly reported on initial access.
* Fixed an issue on the _New User_ and _Manage User_ views where the Central Admin role may have been assignable on users which were not assigned a Platform role of Developer or Administrator.
