---
title: Platform Management 14.0.0 - 14.2.1 release notes
linkTitle: Platform Management 14.0.0 - 14.2.1 release notes
weight: 49
simple_list: true
date: 2024-09-25
---

New features, improvements, and bug fixes for release 14.0.0 - 14.2.1.

---

## 14.2.1 - 25 Sep 2024

Platform Management 14.2.1 is a patch release which includes one fixed issue.

__Fixed issue__

* Fixed an issue where notifications shown in *Recent Activity* in the top navigation for newly invited or recently removed users may not indicate which user.

---

## 14.2.0 - 18 Sep 2024

Platform Management 14.2.0 is a minor release which includes one improvement and one fixed issue.

__Improvement__

* To enhanced data privacy, *Activity* events will no longer include any personally identifiable information.

__Fixed issue__

* Fixed an issue where Onboarding data captured for consumer orgs may be shown in event details on the *Marketplace Activity* view.

---

## 14.1.0 - 26 Aug 2024

Platform Management 14.1.0 is a minor release which includes one new feature, one improvement, and two fixed issues.

__New feature__

* Added feature to require __Enteprise Marketplace__ to provide additional *Onboarding* data during signup. This information is presented on the *Consumer Orgs* view for organization Administrators and Marketplace Manager users during the approval process.

__Improvement__

* Reduced the frequency of account confirmation challenges a user may receive when navigating between various Axway services.

__Fixed issues__

* Fixed an issue where some organizations subscribed to __Amplify API Mananagement Platform__ may not have been provisioned for access to __Amplify Central__ services.
* Fixed an issue where users selected to confirm domain ownership may have received redundant email notifications when an associated identity provider was updated.

---

## 14.0.0 - 8 Aug 2024

Platform Management 14.0.0 is a major release which includes two fixed issues.

{{% alert title="Note" color="primary" %}}
With this release, all navigation elements, *Platform Home* tasks and capabilities, and metrics on the *Overview* page related to __Unified Catalog__ have been removed.
{{% /alert %}}

__Fixed issues__

* Fixed an issue where the organization *Users* table may show an incorrect date of creation for certain users which have been migrated from older __Support Portal__ accounts.
* Fixed an issue where an authentication attempt which fails due to expiry of its grant may cause the user to be shown an unformatted error message.
