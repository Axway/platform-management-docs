---
title: Platform Management 10.3.0 release notes
linkTitle: Platform Management 10.3.0 release notes
weight: 78
date: 2022-04-28
Hide_readingtime: true
---

## Platform Management 10.3.0 - 28 April 2022

Platform Management 10.3.0 is a minor release which includes two new features and several improvements and fixed issues.

Please note that SMS-base multi-factor authentication has been disabled and will be removed in a future release. If you previously had SMS selected as your preferred MFA method, device authorization codes will instead be sent via email. It is recommended that you configure Authenticator App support on your account [_Credentials_](https://platform.axway.com/user/credentials) view.

## New features

* Users who are members of multiple organizations and wish to use their Identity Provider to provision and authenticate users in those orgs can now configure their email domain(s) and associate them to a shared Identity Provider configuration. Please see Enabling Identity Provider for multiple orgs in the [Configuring and managing Identity Providers documentation](https://docs.axway.com/bundle/platform-management/page/docs/management_guide/configuring_and_managing_identity_providers/index.html) for more information.
* Added tags to _Service Accounts_ to aid grouping and searching.

## Improvements

* Changed date range selection and dates displayed for Date Received and Reporting Period columns on the _Usage Report History_ view to UTC.
* Added the ability to select a SAML Descriptor file to prefill values on the _Identity Provider_ configuration form.
* Added the ability to delete multiple devices associated to your account on the _Devices_ view.


## Fixed issue

* Fixed an issue where activation links shown on the _Users_ view may be incorrectly formatted and not allow the user to complete activation.
* Fixed an issue where fields for Volume usage on the _Usage Manual Entry_ form displayed its units incorrectly.
