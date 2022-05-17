---
title: Platform Management 10.4.0 release notes
linkTitle: Platform Management 10.4.0 release notes
weight: 77
date: 2022-05-17
Hide_readingtime: true
---

## Platform Management 10.4.0 - 17 May 2022

Platform Management 10.4.0 is a minor release which includes three new features, two improvements, and two fixed issues.

## New features

* Organizations using a configured identity provider for authentication may now select an Identity Provider on the _New User_ or _Manage User_ forms. This will require that the user authenticate with the selected identity provider in order to access the organization.
* Organizations which use **Amplify Platform** as their identity provider may now establish password policies for its users. These settings are found on the new _Security_ settings view.
* Privacy conscious organizations may now enable redaction (masking) of users' personal information, such as email addresses. This setting is found on the new _Security_ settings view.

## Improvements

* Added a banner to the _Environments_ view to clarify that environments managed in **Amplify Central** are shown on this view.
* Removed capture for phone number from user _Activation_ and _Account_ forms.

## Fixed issue

* Fixed an issue where environments may have been reported under the incorrect governance on the _Usage_ view.
* Fixed an issue on the _Manual Entry_ form where usage for subscriptions starting within the reported month was reported as first of the month. The usage will now be reported as the subscription start date.