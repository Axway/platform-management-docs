---
title: Platform Management 13.6.0 release notes
linkTitle: Platform Management 13.6.0 release notes
weight: 44
date: 2023-05-31
Hide_readingtime: true
---

## Platform Management 13.6.0 - 31 May 2023

Platform Management 13.6.0 is a minor release which includes several new features, one improvement, several changed behaviors, and several fixed issues.

## New features

* Added a *Marketplace Activity* view containing events related to the management of your marketplace and its assets as well as actions performed by consumer org members. The events can be filtered by date range, event type, or consumer org.
* Added an *Activity* link from the *Marketplace Consumer Orgs* view linking to the *Marketplace Activity* view for the selected consumer org.
* Added a toggle to the *Marketplace Settings* view allowing organization Administrator and Marketplace Manager role users to enable *Identity Provider* support for the marketplace's consumer orgs.

## Improvement

* Added the ability for Platform-managed usage environments for which no usage has been reported to be deleted.

## Changed behaviors

* Removed **Unified Catalog** branding capabilities under organization settings.
* Relocated organization logo upload to the organization settings *Manage* view.
* Removed "Featured Products" option from the "Featured Content" selection on *Marketplace Homepage* view.

## Fixed issues

* Fixed an issue where an "Unentitled Usage" section may be shown on the *Usage Report* view showing usage for Analytics Events.
* Fixed an issue on the *Usage Report* view where usage not matching a subscription's governance may not be shown as "Unentitled Usage."
* Fixed an issue on the *Manage User* view where deselecting Administrator role for the organization's primary contact may put the roles list into a bad state.
* Fixed an issue where changing the "Publication Preference" on the *Marketplace Settings* view from "Included/Excluded Teams" to "Include Teams with Tags" may cause the previously selected team's identifiers to be shown as tags.
* Fixed an issue where malformed HTML content in an element on the *Marketplace Footer* view may disallow the element from being deleted.
