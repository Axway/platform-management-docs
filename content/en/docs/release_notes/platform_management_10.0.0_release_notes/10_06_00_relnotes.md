---
title: Platform Management 10.6.0 release notes
linkTitle: Platform Management 10.6.0 release notes
weight: 71
date: 2022-07-15
Hide_readingtime: true
---

## Platform Management 10.6.0 - 15 Jul 2022

Platform Management 10.6.0 is a minor release which includes one improvement and two fixed issues.

Please note with this release there is an announcement of deprecation for location based queries on analytics views. These will no longer be available as of the Platform Management 11.0.0 release in Sep 2022 corresponding to the **Cloud Capacity** and **Mobile Backend Services** [end-of-life announcement](https://blog.axway.com/product-insights/discontinued/appcelerator/changes-to-application-development-services#will-my-titanium-application-fail-after-the-end-of-support-date).

## Improvement

* Org and User Activity views can now display more than 1000 events per query. Users can now page through all events matching their provided filters, search term, and selected date range.

## Fixed issues

* Fixed an issue where *Crash Analytics* widgets and views may fail to load.
* Fixed an issue where entitlements with unlimited quota may have been displayed on the *Organization* overview's Subscriptions table as an arbitrarily large number (10T) instead of "Unlimited".
