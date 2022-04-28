---
title: Platform Management 10.0.0 release notes
linkTitle: Platform Management 10.0.0 release notes
weight: 83
date: 2022-03-01
Hide_readingtime: true
---

## Platform Management 10.0.0 - 1 March 2022

Platform Management 10.0.0 is a major release which includes several changed behaviors as well as an improvement and a fixed issue.

This release corresponds with the [Appcelerator and Application Developement offering End-of-Support](https://www.axway.com/en/appcelerator-end-of-life) initially [announced February 24, 2021](https://blog.axway.com/mobile-apps/changes-to-application-development-services). Support for development workflow actions such as use of **Appcelerator CLI** for building **Titanium SDK** applications are no longer supported.

For continued management of **Amplify Runtime Services** applications, please use the [Amplify Cloud Services CLI](https://docs.axway.com/bundle/AMPLIFY_Runtime_Services_2_0_allOS_en/page/amplify_runtime_services_getting_started.html).

## Changed behaviors

* Renamed the _Dashboard_ tile on the _Platform Home_ view to _Overview_.
* Changed availability of the Auditor role to only be assignable for organizations subscribed to **Flow Manager**. This role has been unassigned from members of organizations with no **Flow Manager** subscription.
* Changed availability of the Runtime Services Admin to only be assignable for organizations with a **Cloud Capacity** or **Amplify Runtime Services** subscription.
* Deprecated the Analytics Specialist role. This role has been unassigned from all users.
* Added a **Business Insights** tile on the _Platform Home_ view and link in the Service Links menu in in the top navigation for orgs provisioned for **Amplify Central**. This link is also shown in the _Overview_ menu, replacing the previous _API Observer_ link.
* Removed the **App Builder** tile from the _Platform Home_ view and link from the Service Links menu in the top navigation.
* Removed the ability to request feature trials in **Application Development**, **Mobile Backend Services**, and **Amplify Runtime Services** offerings from the _Explore Products & Services_ view.
* Removed the _Download Premium Modules_ view. Premium modules are available as open source software from the corresponding [Appcelerator Modules GitHub repository](https://github.com/orgs/appcelerator-modules/repositories).
* Removed the _Get Started with App Builder_ view.
* Removed the **App Preview** link on the _App Overview_ view.
* Removed the option to sign into **Amplify Platform** using GitHub OAuth integration.
* Changed the top navigation to consistently link to the _Platform Home_ view.

## Improvements

* Added support for logarithmic scaling of _Analytics_ and _Custom Query_ view charts.

## Fixed issues

* Fixed an issue where org administators attempting to upload usage for an environment not previously registered may experience an error.