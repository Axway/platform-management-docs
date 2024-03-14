---
title: Platform Management 8.0.0 - 8.9.3 release notes
linkTitle: Platform Management 8.0.0 - 8.9.3 release notes
weight: 100
simple_list: true
date: 2021-10-21
---
<!-- markdownlint-disable  MD024/no-duplicate-heading/no-duplicate-header --->

New features, improvements, and bug fixes for releases 8.0.0 - 8.9.3.

---

## Platform Management 8.9.3 - 21 October 2021

Platform Management 8.9.3 is a patch release which includes one improvement.

{{% alert title="Note" color="primary" %}}
As of this release, all Support, Community, and other Axway portal user accounts have now been merged with their corresponding **Amplify Platform** accounts. For users which did not yet have an **Amplify Platform** account, an **Amplify Platform** account has been created and their credentials will remain the same. For existing users with both portal and **Amplify Platform** accounts, their **Amplify Platform** account credentials should now be used to sign in.
{{% /alert %}}

### Improvement

* Added messaging on the _Sign In_ form shown after a failed sign-in attempt guiding portal users to use their **Amplify Platform** account credentials to sign in.

---

## Platform Management 8.9.2 - 15 October 2021

Platform Management 8.9.2 is a patch release which includes one fixed issue.

### Fixed issue

* Updated documentation links for API Builder on the _Offerings_ view and common navigation header's services list.

---

## Platform Management 8.9.1 - 6 October 2021

Platform Management 8.9.1 is a patch release which includes one new feature.

### New feature

* For **Amplify Runtime Services** applications created after October 5, 2021, the hosted URL will now be on the ``.ars.us.axway.com`` domain. For applications created prior to this date, the app's _Overview_ view will list both its ``.cloudapp-enterprise.appcelerator.com`` and ``.ars.us.axway.com`` URLs.

---

## Platform Management 8.9.0 - 4 October 2021

Platform Management 8.9.0 is a minor release which includes one new feature, one improvement, and one bug fix.

### New feature

* Added indicator of days remaining in trial and control to launch _Guided Tours_ to page header for organizations currently subscribed to **API Management Platform trial**.

### Improvement

* Added **API Management Platform** trial features and FAQs to _Amplify Platform Signup_ view when linked from marketing site.

### Fixed issue

* Fixed issue where application table views may not be updated after an application is updated or deleted.

---

## Platform Management 8.8.3 - 15 September 2021

Platform Management 8.8.3 is a patch release which includes two improvements.

### Improvements

* Added a link to the [Appcelerator Modules GitHub organization's repositories](https://github.com/orgs/appcelerator-modules/repositories) on the _Premium Module Downloads_ view where the modules are now accessible as open source projects.
* Improved Usage reporting _Manual Entry_ form to only show entitlements which correspond to the governance of the selected environment.

---

## Platform Management 8.8.2 - 30 August 2021

Platform Management 8.8.2 is a patch release which includes two improvements and two bug fixes.

{{% alert title="Note" color="primary" %}}
Please note this release contains a deprecation notice for the _Event Funnels_ feature which will be removed in the 9.0.0 release.
{{% /alert %}}

{{% alert title="Note" color="primary" %}}
This release updates the list of browsers support by **Amplify Platform**. Please see [About Browser Support](https://platform.axway.com/browser) for more information.
{{% /alert %}}

### Improvements

* Simplified the display of entitlements on the _Organization_ overview's Subscriptions table.
* Display Organization GUID on the _Organization_ overview for organizations which have a Support Access Code set.

### Fixed issues

* Fixed an issue where members of organizations with no active subscriptions authenticating using **Axway CLI** may not be prompted to select an organization.
* Fixed an issue where users may not be able to view information of other members of their organization.

---

## Platform Management 8.8.1 - 4 August 2021

Platform Management 8.8.1 is a patch release which includes several improvements and two bug fixes.

### Improvements

* Added events and details for Identity Provider and Branding changes to the organization _Activity_ view.
* Added events for when new user invitation emails are resent to the organization _Activity_ view.
* Simplified the Runtime Services app overview and relocated resource utilization charts (CPU and memory use) to a new _Resources_ view.
* Changed the Account _Orgs & Roles_ view to include inactive organizations the user is a member of.

### Fixed issues

* Fixed an issue where the Support tile on the _Platform Home_ view may not be clickable.
* Fixed an issue on the organization _Users_ view when unassigning a user's role if the table is filtered by role.

---

## Platform Management 8.8.0 - 22 July 2021

Platform Management 8.8.0 is a minor release which includes a new feature, several improvements, and a bug fix.

### New features

* Introduced Service Accounts in Platform organization and user management.  Service Accounts may be created and assigned Service Roles and as members of your organization's teams. Please see the [managing service accounts documentation](/docs/management_guide/organizations/managing_organizations/#managing-service-accounts) for more information.

### Improvements

* Added new service links and tasks on _Platform Home_ for managing your organization and its users and visiting **Repository** and **Support**. For organizations only subscribed to non-Amplify offerings, Platform Home is now available to access _Getting Started_ content and these services.
* Simplified signup and account activation process. Signup now requests first and last name, password, organization name, and region. Activation is now a one-click step by following the link in the "Activate your account" email. For users signing up from API Management marketing resources, **API Management Platform** and **Integration Builder** trials will be automatically subscribed once activated.
* Improved layout and consistency of authentication views.

### Fixed issues

* Fixed an issue where updating organization _Users_ and _Teams_ views with members assigned roles that are no longer available may not be able to update a user or team. This issue arises due to expiry of subscription and loss of entitled services for assigned Service Roles. A banner is now displayed at the top of these views indicating which roles are no longer available and provides a means to search for members by role in order to correct the assignment.

---

## Platform Management 8.7.3 - 7 July 2021

Platform Management 8.7.3 is a patch release which includes an improvement and a bug fix.

### Improvements

* For organizations using their own Identity Provider, improved the verbiage on the _Credentials_ view to clarify scope of use of tooling credentials. Added a link to the corresponding documentation.

### Fixed issues

* Fixed an issue where the _Organization Overview_ Subscription status dropdown table may not include the correct set of statuses or allow filtering the subscriptions within the table.

---

## Platform Management 8.7.2 - 24 June 2021

Platform Management 8.7.2 is a patch release which includes two improvements.

### Improvements

* Added an Actions dropdown to the _Usage Report History_ table entries. The menu includes a "View Usage Events" link for a _Custom Query_ to view events for files with a status of "Processed."
* Central Services, Central Environments, and Catalog Entries entitlement quotas and usage are no longer shown on _Usage_ view. The Analytics Events entitlement is no longer shown for organizations with no quota.

---

## Platform Management 8.7.1 - 21 June 2021

Platform Management 8.7.1 is a patch release which includes an improvement.

### Improvements

* Added the ability to select a date range for Transactions, Connected Environments, asset, team, and user counts on _API Management Overview_.

---

## Platform Management 8.7.0 - 17 June 2021

Platform Management 8.7.0 is a minor release which includes several new features, improvements, and bug fixes.

### New features

* Introduced a new _Dashboard_ experience. _Dashboard_ on _Platform Home_ links to a new _Overview_ page with content based on your organization's subscriptions.
* Added a new _Transactions_ analytics view for **API Management** subscribers.
* Organization _Activity_ view now includes events for **Central** environments and API services and **Unified Catalog** assets and subscriptions.

### Improvements

* Central Admin service role may now be assigned to Developer Platform role users.
* Added friendly names for events related to **Central** environments and API services and **Unified Catalog** assets and subscriptions on analytics views.
* Added a legal disclaimer to the _Usage_ view.
* Renamed the _Members_, _Add New Member_, and _Edit Member Teams_ views to _Users_, _Add New User_, and _Edit User Teams_ respectively.

### Fixed issues

* Fixed an issue on analytics views where selecting the "Last 3 Months" date range option may cause the view to not display as expected.
* Fixed usability issues with date range selection on _Custom Query_ view.

---

## Platform Management 8.6.2 - 01 June 2021

Platform Management 8.6.2 is a patch release which includes a bug fix.

### Fixed issues

* Fixed an issue where organizations with private cloud **Amplify Runtime Services** environments may not see apps deployed in those environments listed in the _All Apps_ table.

---

## Platform Management 8.6.1 - 27 May 2021

Platform Management 8.6.1 is a patch release which includes several improvements.

### Improvements

* Added session creation and sign-out events to _Org_ and _User Activity_ views.
* Added introductory content and link to Documentation to _Custom Query_ view.
* Improved verbiage on Region selection and added Terms of Use and Privacy Statement acceptance to _Sign Up_ view.

---

## Platform Management 8.6.0 - 18 May 2021

Platform Management 8.6.0 is a minor release which includes several new features and improvements.

### New features

* Updated **Amplify API Management Platform** offering and added **Integration Builder** offering and added support for their trials on the _Explore Products & Services_ view.
* Updated onboarding questions during activation to initiate **Amplify API Management Platform** and **Integration Builder** trials if the respective capabilities are selected.
* Updated usage aggregation for third-party gateways and Agent SDK to have transactions for all environments count towards entitlement quota or tokens.
* Added a link to the Axway GitHub organization in the header's Help & Resources dropdown.

### Improvements

* Improved loading time for the _All Apps_ table view.
* Updated validation on the **Mobile Backend Services** _Apple iOS Push Configuration_ form to require Bundle ID regardless of selected certificate format.

---

## Platform Management 8.5.1 - 04 May 2021

Platform Management 8.5.1 is a patch release, which includes several improvements and bug fixes.

### Improvements

* First time visitors to Amplify Platform (or return visitors using Incognito mode, private browsing, etc.) will no longer be redirected to marketing content.
* Improved performance of authentication flows.
* Added app ID as an available column on the All Apps table.

### Fixed issues

* Fixed an issue where Central Admin may have been an assigned role on org members which were not Administrator Platform role.
* Fixed an issue where the date range selection controls on analytics views may not present time range options.

---

## Platform Management 8.5.0 - 27 April 2021

Platform Management 8.5.0 is a minor release, which includes several improvements and bug fixes.

### Improvements

* Improved layout and visualization of consumption of quota on _Usage_ view.
* Added access to _Custom Queries_ functionality for all orgs and users.
* Added ability to remove association of a domain to an Identity Provider configuration.
* Added organization name to the _Add New Member_ view for administrators that are members of multiple organizations.
* Improved consistency of column and detail view labels for **Mobile Backend Services** and **Amplify Runtime Services** logs.

### Fixed issues

* Fixed an issue where Logout URI for OpenID Connect Identity Provider configurations may not be shown correctly.
* Fixed an issue where **Amplify Runtime Services** app analytics may not render as expected for orgs with no retention policy entitlement.
* Fixed an issue where shifting to an adjacent date range on analytics view may not select the correct date range.

---

## Platform Management 8.4.4 - 1 April 2021

Platform Management 8.4.4 is a patch release, which includes several improvements and bug fixes.

### Improvements

* Added End-of-Support badge on **App Builder** capability and Discontinuance badge on **Mobile Backend Services** capability on _Platform Home_ view.  Added End-of-Support badge on **Application Development** offering and Discontinuance badge on **Mobile Backend Services** offering on _Explore Products_ view. See [Product Update: Changes to Application Development Services](https://devblog.axway.com/featured/product-update-changes-to-application-development-services-appcelerator/) on Axway Developer Blog for more information.
* Added ability to group _Custom Query_ chart data by arbitrary time intervals using the "From/To" or "Period" date range options. E.g., you can now query 14 days in 6 hour intervals, 12 hours in 15 minute intervals, etc.
* Changed date format in analytics chart series exported CSV to improve recognition in spreadsheet applications. The format was changed from ISO-8601 UTC format to "yyyy-MM-dd HH:mm:ss".

### Fixed issues

* Fixed an issue where viewing a saved _Custom Query_ may not select the previously selected date range.
* Fixed an issue where Download Descriptor XML and Download Signing Certificate buttons on the _Identity Provider_ view for SAML protocol identity providers may cause a 404 error instead of prompting download of the desired resource.

---

## Platform Management 8.4.3 - 18 March 2021

Platform Management 8.4.3 is a patch release, which includes two improvements and two bug fixes.

### Improvements

* Updated the _Usage_ view to only show consumption for Axway Managed and Customer Managed governance entitlements if a quota was set.
* Updated the _Identity Provider Settings_ view's Domain Verification modal to clarify the TXT record value should be empty if allowed by the DNS provider.

### Fixed Issues

* Fixed an issue where new Mobile Backend Services datasources may not be created as expected.
* Fixed an issue where platform icons for an application may not be shown in the _All Apps_ or _Add/Edit Team_ tables.

---

## Platform Management 8.4.2 - 1 March 2021

Platform Management 8.4.2 is a patch release, which includes a new feature and an improvement.

### New features

* Organizations entitled to use their own Identity Provider for authenticating to **Amplify Platform** may now configure more than one Identity Provider. See the [Configuring and Managing Identity Providers documentation](https://docs.axway.com/csh?context=62555476) for more information.

### Improvements

* Added specific browser vendors and versions supported by **Amplify Platform** to the [Supported Browsers](https://platform.axway.com/browser) page.

---

## Platform Management 8.4.1 - 5 February 2021

Platform Management 8.4.1 is a patch release, which includes new features, improvements, and bug fixes.

### New features

* Organizations using their company's Identity Provider to authenticate to **Amplify Platform** can now select the default roles and teams to which members are assigned when initially signing in. User attributes from their Identity Provider can also be used to manage assigned roles and teams. See the [Identity Provider Configuration documentation](https://docs.axway.com/csh?context=62555476) for more information.

### Improvements

* Added an option to the organization _Usage_ view to show usage for all environments or production environments only.
* Updated organization _Usage_ view to no longer show entitlements for which the organization has no quota or usage.
* Updated the _Usage Report History_ view to show the user who performed usage upload or manual entry and includes entries for both Axway-managed and customer-managed environments.

### Fixed issues

* Fixed an issue where **Amplify Crash Analytics** views permitted selection of a date range more than the allowed 30 day retention for crash events.
* Fixed an issue where organizations with one or more available VPC environments may not be able to deselect environments during **Mobile Backend Services** app creation.
* Fixed an issue on the _Usage Report History_ view where filtering report history by selected date range may not function as expected.
* Fixed an issue where the **Mobile Backend Services** Friends object type form view may not render properly.

---

## Platform Management 8.4.0 - 14 January 2021

Platform Management 8.4.0 is a minor release, which includes several improvements and bug fixes.

### Improvements

* Updated UI colors and icons for improved visibility and clarity.
* Improved error messaging when a **Mobile Backend Services** datasource is not accessible.
* Added a column on the _Usage_ _Report History_ table indicating which user performed the upload or entry.

### Fixed issues

* Fixed an issue where navigating away from views containing tables using the browser's back button or history may not function as expected.
* Fixed an issue where the _Events_ analytics view may not correctly link to **Amplify Runtime Services** apps hosted in VPC environments.

---

## Platform Management 8.3.2 - 17 December 2020

Platform Management 8.3.2 is a patch release, which includes an improvement and a bug fix.

### Improvement

* Improved handling of redirects after sign-in or activation when initiated from portals or other services.

### Fixed Issue

* Fixed an issue when configuring P8 format certificates on iOS Push Notification settings for **Mobile Backend Services** datasources.

---

## Platform Management 8.3.1 - 15 December 2020

Platform Management 8.3.1 is a patch release, which includes a new feature and two improvements.

### New features

* Added the ability to configure P8 certificates in _iOS Push Notification settings_ for **Mobile Backend Services** datasources.

### Improvements

* Improved restrictions for Consumer role users to no longer allow access to view organization, team, or organization member information.
* Relocated the App Preview link to the actions dropdown on _App Overview_.

---

## Platform Management 8.3.0 - 3 December 2020

Platform Management 8.3.0 is a minor release which includes several improvements and bug fixes.

### Improvements

* Updated the _Identity Provider Configuration_ setup to use a DNS entry for domain ownership verification.
* Added the capability to automatically add all users with email addresses on a verified domain to an organization.
* Provided one-click downloads for the SAML descriptor and signing certificate files on the _Identity Provider Configuration_ view.
* Added the ability for organization administrators to perform manual usage entry for Customer Managed environments.
* Improved the month/year and subscription selectors on the organization _Usage_ view.
* Improved the redirect handling on signup and when signing in from **Amplify** services other than **Platform**.

### Fixed issues

* Fixed an issue where product Category names on the _Organization_ overview's _Subscriptions_ table may not be displayed properly.
* Fixed an issue where **Mobile Backend Services** _Push Notification_ form may not allow sending a one-time push notification.
* Removed support for SVG images for branding logos.

---

## Platform Management 8.2.3 - 6 November 2020

Platform Management 8.2.3 is a patch release, which includes an improvement and two bug fixes.

### Improvements

* Simplified the _Organization_ overview's _Subscriptions_ table.

### Fixed issues

* Fixed an issue where the _Explore More Products & Services_ view may not indicate a trial subscription is expired.
* Fixed an issue where users with existing accounts attempting to sign up may receive an error rather than the "You already have an account" email.

---

## Platform Management 8.2.2 - 15 October 2020

Platform Management 8.2.2 is a patch release, which includes a new feature and several bug fixes.

{{% alert title="Note" color="primary" %}}
With this release, support for Internet Explorer 11 has been officially sunset.
{{% /alert %}}

### New features

* Added two settings to the user _Account Settings_ view. The "Inactivity Sign-out" setting lets users select how long to allow browser sessions to be inactive before signing the user out. This default setting is 30 minutes. This behavior may also be disabled. The "Restore page on next sign-in" setting lets users choose whether to be redirected to the page previously viewed once signed back in after being signed out due to inactivity. This setting is disabled by default (do not restore previous page on next sign-in).

### Fixed issues

* Fixed an issue where **Runtime Services** app names may not appear in chart and table data saved on analytics views. Additionally, fixed an issue where some columns for **Mobile Backend Services** datasources may be empty in saved table data.
* Fixed an issue where starting a free trial from the _Explore More Products & Services_ view may not redirect users to the _Platform Home_ view showing the newly available capabilities.
* Fixed an issue where clicking **Amplify Platform** in the page header while on the _Signup_ view may cause an error.

---

## Platform Management 8.2.1 - 1 October 2020

Platform Management 8.2.1 is a patch release, which includes a new feature and bug fixes.

### New features

* Added support for configuring Firebase Cloud Messaging (FCM) HTTP v1 to **Mobile Backend Services** Push Notifications _Android_ _Cloud Messaging Configuration_ view.

### Fixed issues

* Fixed an issue where the _Organization_ overview may not render properly for some organizations.
* Fixed an issue where a user who does not select any interests during activation may not be properly redirected to the _Explore Products & Services_ view after activation.

---

## Platform Management 8.2.0 - 30 September 2020

Platform Management 8.2.0 is a minor release, which includes two new features and an improvement.

### New features

* Signing up for **Amplify Platform** now allows new users to select the data privacy region in which their organization's customer data will reside.
* Added a _Download Center_ menu in the common header's _Help & Resources_ menu replacing the previous _Marketplace_ link and linking to product and product extension resources.

### Improvement

* Consolidated **Amplify** **Central** and **Flow Manager** service roles for _Analytics Specialist_ into a single **Visibility** service role. The existing _Auditor_ role has also been relocated to **Visibility** services roles.

---

## Platform Management 8.1.0 - 23 September 2020

Platform Management 8.1.0 is a minor release, which includes new features, improvements, and bug fixes.

### New features

* Introduced a new _Activity_ view accessible from the notifications (bell) icon in the common header or the left-hand menu on the user's _Account_ view. The _Activity_ view shows additions, deletions, and changes performed by or on the user and changes to the organization and its apps and services for the user's current organization.
* Introduced a new org _Activity_ view accessible from the left-hand menu on the _Organization_ view. The _Activity_ view shows changes to the organization, its subscriptions, and its apps and services.
* Introduced a new app _Activity_ view accessible from the left-hand menu on any app view. The _Activity_ view shows events related to the apps.
* Added the ability to download _Analytics_ view charts as an image.
* Added modules used by _Titanium_ applications to the _App Overview_.
* Added four widgets to the _Metric Overview_ available for organizations which have **Amplify Central** provisioned showing occurrences of Central Asset, Central Environment, Catalog Item, and Catalog Subscription events.
* Selecting a time range on _Analytics_ view charts will now "zoom in" on that date range.

### Improvements

* Revised the _Latest Activity_ and _Notifications_ accessible from the notifications icon in the common header. Their entries are now combined into a single list of _Recent Activity_. Clicking on an entry in this list takes the user to the user _Activity_ view to see more details about the event.
* Improved resolution (i.e., number of data points shown) on _Analytics_ view charts.
* Improved labels on the x-axis of charts on _Analytics_ views.
* Changed the _Subscriptions_ section of the _Organization_ overview to show only active subscriptions on initial load. Terminated, inactive, and pending subscriptions can be viewed by selecting that status from the dropdown above the table.
* Added a link to the _Titanium SDK Prerequisites_ documentation on the _Get Started with App Builder_ guide. This documentation shows supported dependency versions and their download locations.
* All applications deployed using **Amplify Runtime Services** now show a type value of "Runtime Service" on the all apps table.

### Fixed issues

* Fixed an issue where users may not be able to edit their _Account_ information in Safari.
* Fixed an issue where Firefox for Android was shown as an unsupported browser (it's totally supported!)
* Fixed an issue where the organization _Usage_ view may not have shown the correct entitlement quotas when viewing usage for prior months.
* Fixed an issue where **Amplify Runtime Services** application access logs may not have been properly format response times greater than one second.
* Fixed an issue where application names may not have been included in exported chart or table data.

---

## Platform Management 8.0.4 - 24 August 2020

Platform Management 8.0.4 is a patch release, which includes two improvements and a bug fix.

### Improvements

* Added a guided product tour for Amplify Platform Home and Offerings views.
* Added Governance to Organization overview's Subscriptions table.

### Fixed issues

* Fixed an issue where Devices and OS Versions charts on Amplify Crash Analytics detail view may not be visible for applications with a large number of devices or OS versions.

---

## Platform Management 8.0.3 - 10 August 2020

Platform Management 8.0.3 is a patch release, which includes two bug fixes.

With this release, integration with Appcelerator DevLink is no longer supported. Appcelerator DevLink has been discontinued and will no longer be available.

### Fixed issues

* Fixed an issue where long-time Appcelerator community members who never set their name on their {{% variables/platform_prod_name %}} account may see an unexpected message when attempting to sign in.
* Fixed an issue in the _Custom Query_ view where changing a custom date range for a previously saved or previewed query may not show the correct date range for the returned data on a subsequent preview.
* Fixed an issue where users attempting to sign up using their GitHub account may receive an error.

---

## Platform Management 8.0.2 - 4 August 2020

Platform Management 8.0.2 is a patch release, which includes two improvements and two bug fixes.

{{% alert title="Note" color="primary" %}}
Please note that browser support for **Amplify Platform** has changed. Support for Microsoft Internet Explorer 11 has been deprecated and and will no longer function after September 30, 2020. Please visit [https://platform.axway.com/browser](https://platform.axway.com/browser) for the list of supported browsers and versions.
{{% /alert %}}

### Improvements

* For organizations subscribed to Application Integration, the Integration Builder link in the common header's services menu now provides links to available environments.
* Overview and app analytics chart/table views now link to open the corresponding query in the Custom Query view (requires Application Development Pro or Enterprise subscription or monthly Cloud Capacity subscription).

### Fixed issues

* Fixed an issue where organizations with a large number of applications may experience intermittent browser instability or long load times when viewing their list of apps.
* Fixed an issue where attempting to navigate to a specific view when not signed in may experience a "page not found" error after signing in rather than being successfully redirected to the requested view.

---

## Platform Management 8.0.1 - 23 July 2020

Platform Management 8.0.1 is an incremental release, which includes a few improvements and a bug fix.

### Improvements

* Performed minor revisions and usability improvements to the common header and the _Amplify Platform Home_, _Organization_, and _Account_ views.
* Reordered "My Capabilities" and key tasks sections of _Amplify Platform Home_ to promote Central, Catalog, and Integration Builder offerings.
* Removed the Applications, Mobile Backend Services Datasources, and Amplify Runtime Services counts on the organization _Usage_ view.

### Fixed issues

* Fixed an issue where the services listed in the common header's service (left most) menu and capabilities and tasks shown on _Amplify Platform Home_ may not include all services subscribed or provisioned for the organization or available for the user's role.

---

## Platform Management 8.0.0 - 17 July 2020

Platform Management 8.0.0 is a major release, which includes new features, improvements, and one bug fix.

{{% alert title="Note" color="primary" %}}
Please note that browser support for Amplify Platform has been changed to no longer support Apple Safari 11.0 and below (version 11.1 or later is supported) or Microsoft Edge 16 and below. Please visit [https://platform.axway.com/browser](https://platform.axway.com/browser) for the list of supported browsers and versions.
{{% /alert %}}

### New features

* This release introduces a new **Amplify Platform** on-boarding experience and an all-new _Amplify Platform_ Home. _Amplify Platform Home_ now lists the capabilities to which your organization has access as well as common tasks available for those capabilities. Users can explore more offerings on a streamlined _Products and Services_ page.
* The common header (aka Unified Nav) has also been improved. A new _Help & Resources_ dropdown provides links to document, support, and other resources. Once signed in, the header now shows new services menu on the left, allowing users to quickly switch between various Platform capabilities and their UIs, and a simplified user menu on the right, now showing your assigned role.
* During activation of newly signed up users, a new page is now presented, asking which Amplify Platform capabilities the org wishes to use. Feature trials will be automatically requested for the selected capabilities.
* For organizations primarily using **API Management** capabilities, the Dashboard link on the _Amplify Platform Home_ page will now link to the new _Amplify Visibility_ UI. This new UI requires assignment of the "Analytics Specialist" role in order to access it.

### Improvements

* Navigation between the _Dashboard_, _Overview_, and _Custom Queries_ views has changed from a left-hand menu.
* The link for the _Download Premium Modules_ view has been relocated to the Dashboard left-hand menu.
* Display of long app names of the Apps table is improved.
* The Add (+) menu items for "Register App for Services" and "Create MBS Datasource" previously in the common header have been relocated to the _Apps_ view's right-hand actions menu.
* Added a "Manage Subscriptions" link to the _Organization Overview_ above the Subscriptions table for on-demand organizations to manage their subscriptions.
* Added support for indicating which administrator member of an organization is its primary contact on the organization _Members_ view.
* The organization _Members_ view's Roles list now displays the reason why a role may not be available. E.g, if all seats for a given role are occupied, a "Seat limit reached" message is shown.

### Fixed Issues

* Fixed an issue where attempting to add an existing platform user to a new or different organization may not behave as expected.
