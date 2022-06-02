---
title: Platform Management 10.3.0 release notes
linkTitle: Platform Management 10.3.0 release notes
weight: 78
date: 2022-04-28
Hide_readingtime: true
---

## Platform Management 10.3.0 - 28 April 2022

Platform Management 10.3.0 is a minor release which includes two new features and several improvements and fixed issues.

Please note that SMS-base multi-factor authentication has been disabled and will be removed in a future release. If you previously had SMS selected as your preferred MFA method, device authorization codes will be sent by email instead. It is recommended that you configure Authenticator App support on your account [*Credentials*](https://platform.axway.com/user/credentials) view.

## New features

* Identity provider configurations and their associated email domains can be used by multiple organizations. See [Enabling an Identity Provider for multiple organizations](/docs/management_guide/configuring_and_managing_identity_providers/enabling_identity_provider_multiple_orgs) for more information.
* Added tags to *Service Accounts* to aid grouping and searching.

## Improvements

* Changed date range selection and dates displayed for Date Received and Reporting Period columns on the *Usage Report History* view to UTC.
* Added the ability to select a SAML Descriptor file to prefill values on the *Identity Provider* configuration form.
* Added the ability to delete multiple devices associated to your account on the *Devices* view.

## Fixed issue

* Fixed an issue where activation links shown on the *Usage Manual Entry* form displayed its units incorrectly.
