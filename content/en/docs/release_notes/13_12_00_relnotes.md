---
title: Platform Management 13.12.0 release notes
linkTitle: Platform Management 13.12.0 release notes
weight: 28
date: 2023-11-07
Hide_readingtime: true
---

## Platform Management 13.12.0 - 7 Nov 2023

Platform Management 13.12.0 is a minor release which includes two new features, one improvement, and two fixed issues.

## New features

* Added social authentication options to the *Marketplace Settings* view. This allows for OAuth-based integration with GitHub, Gitlab, or Google to allow authentication and sign-up for consumer org users.
* Added the ability to customize the *Help & Resources Menu* on the organization *Manage* view.

## Improvement

* Removed *Runtime Services Admin* role from all users to which it was assigned. This role is no longer valid or grants no permissions.
* Improved handling of email address fields to be permissive of mixed case values.

## Fixed issues

* Fixed an issue where users assigned *Developer* role in teams to which marketplace access has been granted may not see the marketplace on the *Marketplaces* view or in navigation elements.
* Fixed an issue where performing manual entry of usage data may not function as expected.
