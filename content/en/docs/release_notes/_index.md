---
title: Release notes
linkTitle: Release notes
description:
no_list: true
weight: 40
date: 2021-08-26
---

## Platform Management 8.8.2 - 26 August 2021

Platform Management 8.8.2 is a patch release which includes two improvements and two bug fixes.

This release updates the list of supported browser. Support for following browsers has been removed:
- Google Chrome Enterprise 61
- iOS Safari 10.2

Please note this release contains a deprecation notice for the _Event Funnels_ feature which will be removed in the 9.0.0 release (Oct 2021).

## Improvements

* Simplified the display of entitlements on the _Organization_ overview's Subscriptions table.
* Display Organization GUID on the _Organization_ overview for organizations which have a Support Access Code set.

## Fixed issues

* Fixed an issue where members of organizations with no active subscriptions authenticating using **Axway CLI** may not be prompted to select organization.
* Fixed an issue where users may not be able to view information of other members of their organization.
