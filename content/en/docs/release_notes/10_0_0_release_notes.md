---
title: Platform Management 10.0.0 - 10.7.0 release notes
linkTitle: Platform Management 10.0.0 - 10.7.0 release notes
weight: 80
simple_list: true
date: 2022-08-11
---

New features, improvements, and bug fixes for releases 10.0.0 - 10.7.0.

---

## 10.7.0 - 11 Aug 2022

Platform Management 10.7.0 is a minor release which includes one new feature and two fixed issues.

__New feature__

* Added support for enabling and customizing homepage hero banner and featured content on the *Marketplace Homepage* settings view.

__Fixed issues__

* Fixed an issue where user and organization names with non-western characters may not be handled properly in common navigation.
* Fixed a few UI glitches on the *Custom Query* view. Also, improved the column labels for selected grouped fields.

---

## 10.6.1 - 26 Jul 2022

Platform Management 10.6.1 is a patch release which includes two improvements and one fixed issue.

__Improvements__

* Added deprecation reminder to *Platform Home* and *Overview* views for organizations subscribed to the __Cloud Capacity__ offering. Please see the [end-of-life announcement](https://blog.axway.com/product-insights/discontinued/appcelerator/changes-to-application-development-services#will-my-titanium-application-fail-after-the-end-of-support-date) for more information.
* Added deprecation notices to API endpoints and parameters no longer supported after the __Cloud Capacity__ end-of-life.

__Fixed issue__

* Fixed an issue where analytics views grouped by location may show larger event counts than expected.

---

## 10.6.0 - 15 Jul 2022

Platform Management 10.6.0 is a minor release which includes one improvement and two fixed issues.

{{% alert title="Note" color="primary" %}}
Please note with this release there is an announcement of deprecation for location based queries on analytics views. These will no longer be available as of the Platform Management 11.0.0 release in Sep 2022 corresponding to the __Cloud Capacity__ and __Mobile Backend Services__ [end-of-life announcement](https://blog.axway.com/product-insights/discontinued/appcelerator/changes-to-application-development-services#will-my-titanium-application-fail-after-the-end-of-support-date).
{{% /alert %}}

__Improvement__

* Org and User Activity views can now display more than 1000 events per query. Users can now page through all events matching their provided filters, search term, and selected date range.

__Fixed issues__

* Fixed an issue where *Crash Analytics* widgets and views may fail to load.
* Fixed an issue where entitlements with unlimited quota may have been displayed on the *Organization* overview's Subscriptions table as an arbitrarily large number (10T) instead of "Unlimited".

---

## 10.5.4 - 8 Jul 2022

Platform Management 10.5.4 is a patch release which includes one improvement and two fixed issues.

__Improvement__

* Custom help menu will consistently show in the common navigation header within the Marketplace UI regardless of the user's signed-in state. The service switcher and recent activity feed will only be visible for administrative role users.

__Fixed issues__

* Fixed an issue where the *Usage* view may not show comsumption values for Hybrid governance __Amplify API Management Platform__ subscriptions.
* Fixed an issue where left navigation menu items may not be shown for some __Mobile Backend Services__ datasources.

---

## 10.5.3 - 30 Jun 2022

Platform Management 10.5.3 is a patch release which includes two fixed issues.

__Fixed issues__

* Fixed an issue where the *Usage* view may not show comsumption values for some SaaS governance entitlements.
* Fixed an issue on the *Marketplace Appearance* view where users may not be able to update logo or favicon files when Help Menu items have been configured.

---

## 10.5.2 - 23 Jun 2022

Platform Management 10.5.2 is a patch release which includes two fixed issues.

__Fixed issues__

* Fixed an issue where the *Activity* view may not display the names of service accounts performing the action indicated by an event.
* Fixed an issue where non-Administrator users may not be shown the teams they are members of on the *Org User* or *Team* views.

---

## 10.5.1 - 16 Jun 2022

Platform Management 10.5.1 is a patch release which includes two improvements and one fixed issues.

__Improvement__

* *Identity Providers* view is now available under *Settings* to administrators of any organization with an active Enterprise subscription.
* Updated Password Policy verbiage on the *Security* view under *Settings* to more clearly state default policies.

__Fixed issue__

* Fixed an issue where the *Usage* view may not show usage values for SaaS governance entitlements.

---

## 10.5.0 - 1 Jun 2022

Platform Management 10.5.0 is a minor release which includes two new features, an improvement, and two fixed issues.

{{% alert title="Note" color="primary" %}}
Please note as of this release __Amplify API Management Platform__ trial subscriptions can no longer be requested on the *Explore Products & Services* view. Please [contact sales](https://go2.axway.com/GLOB-WR-Amplify-Trial-Contact-Us.html) to request custom trial assistance.
{{% /alert %}}

__New features__

* Service Accounts may now be assigned a Platform Role and inherit their permissions. For example, a service account assigned to a Platform role of Administrator can perform administrative functions such as managing users, teams, and role assignments.
* Customized help menu links can now be administered on the *Marketplace Appearance* view.

__Improvement__

* *Usage* view's Show Environments toggle will now persist between visits to this view.

__Fixed issue__

* Fixed an issue where users signing in from their marketplace may not be redirected back after signing in if their account's Sign-in Organization setting was set to "Always ask for organization".
* Fixed an issue where the *Users* table view would not update as newly invited users activated.

---

## 10.4.0 - 17 May 2022

Platform Management 10.4.0 is a minor release which includes three new features, two improvements, and two fixed issues.

__New features__

* Organizations using a configured identity provider for authentication may now select an Identity Provider on the *New User* or *Manage User* forms. This will require that the user authenticate with the selected identity provider in order to access the organization.
* Organizations which use __Amplify Platform__ as their identity provider may now establish password policies for its users. These settings are found on the new *Security* settings view.
* Privacy conscious organizations may now enable redaction (masking) of users' personal information, such as email addresses. This setting is found on the new *Security* settings view.

__Improvements__

* Added a banner to the *Environments* view to clarify that environments managed in __Amplify Central__ are shown on this view.
* Removed capture for phone number from user *Activation* and *Account* forms.

__Fixed issue__

* Fixed an issue where environments may have been reported under the incorrect governance on the *Usage* view.
* Fixed an issue on the *Manual Entry* form where usage for subscriptions starting within the reported month was reported as first of the month. The usage will now be reported as the subscription start date.

---

## 10.3.0 - 28 April 2022

Platform Management 10.3.0 is a minor release which includes two new features and several improvements and fixed issues.

{{% alert title="Note" color="primary" %}}
Please note that SMS-base multi-factor authentication has been disabled and will be removed in a future release. If you previously had SMS selected as your preferred MFA method, device authorization codes will be sent by email instead. It is recommended that you configure Authenticator App support on your account [*Credentials*](https://platform.axway.com/user/credentials) view.
{{% /alert %}}

__New features__

* Identity provider configurations and their associated email domains can be used by multiple organizations. See [Enabling an Identity Provider for multiple organizations](/docs/management_guide/configuring_and_managing_identity_providers/enabling_identity_provider_multiple_orgs) for more information.
* Added tags to *Service Accounts* to aid grouping and searching.

__Improvements__

* Changed date range selection and dates displayed for Date Received and Reporting Period columns on the *Usage Report History* view to UTC.
* Added the ability to select a SAML Descriptor file to prefill values on the *Identity Provider* configuration form.
* Added the ability to delete multiple devices associated to your account on the *Devices* view.

__Fixed issue__

* Fixed an issue where activation links shown on the *Usage Manual Entry* form displayed its units incorrectly.

---

## 10.2.1 - 14 April 2022

Platform Management 10.2.1 is a patch release which includes two improvements and one fixed issue.

__Improvements__

* Added *Environments* capability tile on *Platform Home* view for organizations with Marketplace entitlement.
* Provided support for non-administrator role users to fetch information about teams in their organization to improve *Asset Catalog* user experience.

__Fixed issue__

* Fixed an issue where organizations with non-trial API Management Platform subscriptions may have trial data generated in Central.

---

## 10.2.0 - 5 April 2022

Platform Management 10.2.0 is a minor release which includes one new feature.

__New features__

* Revised *Platform Home* layout and contents to provide easier access to Management Plane and Marketplace tasks and features. For organizations with Marketplace entitlement, new capabilities and tasks have been added linking to Services Registry, Asset Catalog, and Product Foundry both on *Platform Home* and in top navigation's Service Links.

---

## 10.1.0 - 25 March 2022

Platform Management 10.1.0 is a minor release which includes two new features and a fixed issue.

{{% alert title="Note" color="primary" %}}
With this release, Insights (read only admin) and Collaborator role support has been removed. These deprecated roles were only available for organizations with Pro or Enterprise Application Development subscriptions. As those offerings reached [end-of-support on March 1, 2022](https://www.axway.com/en/appcelerator-end-of-life), all users with these deprecated roles assigned have been removed from their respective organizations. Events dated March 25, 2022 are noted in the *Activity* view for these removed users. These users can be re-added with Administrator or Developer role if needed.
{{% /alert %}}

__New features__

* Added a Promoter Specialist service role available for subscribers of __Flow Manager__.
* Added a Subscription Admin team role available for subscribers of __Amplify API Management Platform__ or __Amplify Hub__.

__Fixed issue__

* Fixed an issue where organization administrators were unable to delete a team without selecting a team to reassign its assets to.

---

## 10.0.1 - 10 March 2022

Platform Management 10.0.1 is a patch release which includes an improvement and a fixed issue.

__Improvement__

* Added a series legend to chart images downloaded from *Analytics* and *Custom Query* views.

__Fixed issue__

* Restored ability to select a date range on *Analytics* and *Custom Query* view charts to show only data for that range.

---

## 10.0.0 - 1 March 2022

Platform Management 10.0.0 is a major release which includes several changed behaviors as well as an improvement and a fixed issue.

{{% alert title="Note" color="primary" %}}
This release corresponds with the [Appcelerator and Application Developement offering End-of-Support](https://www.axway.com/en/appcelerator-end-of-life) initially [announced February 24, 2021](https://blog.axway.com/mobile-apps/changes-to-application-development-services). Support for development workflow actions such as use of __Appcelerator CLI__ for building __Titanium SDK__ applications are no longer supported.
{{% /alert %}}

{{% alert title="Note" color="primary" %}}
For continued management of __Amplify Runtime Services__ applications, please use the [Amplify Cloud Services CLI](https://docs.axway.com/bundle/AMPLIFY_Runtime_Services_2_0_allOS_en/page/amplify_runtime_services_getting_started.html).
{{% /alert %}}

__Changed behaviors__

* Renamed the *Dashboard* tile on the *Platform Home* view to *Overview*.
* Changed availability of the Auditor role to only be assignable for organizations subscribed to __Flow Manager__. This role has been unassigned from members of organizations with no __Flow Manager__ subscription.
* Changed availability of the Runtime Services Admin to only be assignable for organizations with a __Cloud Capacity__ or __Amplify Runtime Services__ subscription.
* Deprecated the Analytics Specialist role. This role has been unassigned from all users.
* Added a __Business Insights__ tile on the *Platform Home* view and link in the Service Links menu in in the top navigation for orgs provisioned for __Amplify Central__. This link is also shown in the *Overview* menu, replacing the previous *API Observer* link.
* Removed the __App Builder__ tile from the *Platform Home* view and link from the Service Links menu in the top navigation.
* Removed the ability to request feature trials in __Application Development__, __Mobile Backend Services__, and __Amplify Runtime Services__ offerings from the *Explore Products & Services* view.
* Removed the *Download Premium Modules* view. Premium modules are available as open source software from the corresponding [Appcelerator Modules GitHub repository](https://github.com/orgs/appcelerator-modules/repositories).
* Removed the *Get Started with App Builder* view.
* Removed the __App Preview__ link on the *App Overview* view.
* Removed the option to sign in to __Amplify Platform__ using GitHub OAuth integration.
* Changed the top navigation to consistently link to the *Platform Home* view.

__Improvements__

* Added support for logarithmic scaling of *Analytics* and *Custom Query* view charts.

__Fixed issues__

* Fixed an issue where org administrators attempting to upload usage for an environment not previously registered may experience an error.
