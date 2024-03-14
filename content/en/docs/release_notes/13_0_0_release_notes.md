---
title: Platform Management 13.0.0 - 13.18.0 release notes
linkTitle: Platform Management 13.0.0 - 13.18.0 release notes
weight: 50
simple_list: true
date: 2024-03-13
---
<!-- markdownlint-disable  MD024/no-duplicate-heading/no-duplicate-header --->

New features, improvements, and bug fixes for releases 13.0.0 - 13.18.0.

---

## Platform Management 13.18.0 - 13 Mar 2024

Platform Management 13.18.0 is a minor release which includes two new features and two fixed issues.

### New features

* The *Usage* view now includes charts showing daily usage per entitlement and per environment by clicking the corresponding icon.
* Administrator and Marketplace Manager role users can now view the organizations, teams, and users by following the corresponding organization's link on the *Consumer Orgs* view under each marketplace.

### Fixed issues

* Fixed an issue where signing in and signup using GitHub, GitLab, or Google OAuth integrations enabled for a marketplace may not function as expected.
* Fixed an issue where the Catalog Asset, Marketplace Subscription, and Marketplaces counts may have shown as zero on the *Overview* and *Usage* views.

---

## Platform Management 13.17.3 - 29 Feb 2024

Platform Management 13.17.3 is a patch release which includes two improvements and one fixed issue.

### Improvements

* Administrator role members of an organization can reassign any administrator to Primary Contact on the *Users* table view. Previously only the current Primary Contact could reassign that designation.
* Improved verbiage in Platform sent email notifications.

### Fixed issue

* Fixed an issue where review instructions may not be able to be saved on the *Marketplace Ratings & Reviews* view.

---

## Platform Management 13.17.2 - 14 Feb 2024

Platform Management 13.17.2 is a patch release which includes one fixed issue.

### Fixed issue

* Fixed an issue where consumer org users of marketplaces which have identity provider configuration enabled may not be redirected back to the marketplace after authenticating.

---

## Platform Management 13.17.1 - 13 Feb 2024

Platform Management 13.17.1 is a patch release which includes one fixed issue.

### Fixed issue

* Fixed an issue where users who have been removed from an organization may experience an error on next sign-in.


---

## Platform Management 13.17.0 - 12 Feb 2024

Platform Management 13.17.0 is a minor release which includes one new feature and two fixed issues.

### New feature

* Relocated the *Ratings & Reviews* settings from the *Marketplace Settings* view to its own view.

### Fixed issues

* Fixed an issue where managing service account credentials using Axway CLI may not function as expected.
* Fixed an issue where the *Reset Your Password* form view may be initially shown in an error state.

---

## Platform Management 13.16.0 - 01 Feb 2024

Platform Management 13.16.0 is a minor release which includes one new feature and one improvement.


### New feature

* Added *Custom Version Display* settings to the *Marketplace Settings* view.

### Improvement

* Service accounts may now be assigned any role a user may be assigned.

---

## Platform Management 13.15.1 - 25 Jan 2024

Platform Management 13.15.1 is a patch release which includes one new feature.

{{% alert title="Note" color="primary" %}}
With this release, organizations which are currently entitled to access Unified Catalog have been granted an _Amplify Enterprise Marketplace_ subscription.
{{% /alert %}}


### New feature

* Added *Activity* view event definitions to the _Platform_ API documentation.

---

## Platform Management 13.15.0 - 18 Jan 2024

Platform Management 13.15.0 is a minor release which includes five improvements and one fixed issue.

{{% alert title="Note" color="primary" %}}
With this release, self-service account creation has been temporarily disabled. This ability will be restored in a future release.
{{% /alert %}}

{{% alert title="Note" color="primary" %}}
Subscriptions for deprecated Axway products will no longer be shown under the organization *Overview* view.
{{% /alert %}}

### Improvements

* The organization name is now persistently shown in the breadcrumbs at the top of *Teams*, *Users*, and other views under the organization menu.
* The date range filter on the *Usage Report History* view may now be applied to the date reported or the reporting period of the file.
* Added the product name and version for which the file was reported as available columns on the *Usage Report History* view.
* Added support for Axway license products to be shown on the organzation *Overview* view.
* Improved table sorting for undefined or empty values.

### Fixed issue

* Fixed an issue with the date range selection component where selecting ranges across years may not behave as expected.

---

## Platform Management 13.14.1 - 12 Dec 2023

Platform Management 13.14.1 is a patch release which includes two fixed issues.

### Fixed issues

* Fixed an issue where the *Identity Provider Configuration* views may not be visible if the feature was previously configured, but is no longer entitled.
* Fixed an issue where the *Consumer Org* creation form view may not show the initial administrator email form input and could not be submitted.

---

## Platform Management 13.14.0 - 07 Dec 2023

Platform Management 13.14.0 is a minor release which includes one new feature, one improvement, and two fixed issue.

{{% alert title="Note" color="primary" %}}
With this release, _Application Integration_ and _Integration Builder_ capabilities are no longer available or navigable from the *Platform Home* view.
{{% /alert %}}

### New feature

* Added *Ratings & Reviews* settings to the *Marketplace Settings* view.

### Improvement

* Ad-hoc or previously saved queries created on the *Custom Query* view are now sharable via its URL.

### Fixed issues

* Fixed an issue where users assigned Team Manager role, but not organization Administrator role, may not be able to edit their teams.
* Fixed an issue where *Platform Home* and *Overview* view links were shown for Consumer role users, but would error when followed.

---

## Platform Management 13.13.0 - 29 Nov 2023

Platform Management 13.13.0 is a minor release which includes one new feature, one improvement, and two fixed issues.

### New features

* Added an option to the *Marketplace Settings* view to require Consumer role marketplace users to authenticate with a configured Identity Provider.

### Improvement

* Improved usability of the date range selector on analytics views.

### Fixed issue

* Fixed an issue where users attempting to sign up for a marketplace using the GitHub, GitLab, or Google OAuth integrations, but do not have a name set in those services, may encounter an error.
* Fixed an issue where a banner containing a warning about unavailable roles being assigned may flash as the organization *Users* view was loading.

---

## Platform Management 13.12.1 - 7 Nov 2023

Platform Management 13.12.1 is a patch release which includes one fixed issue.

### Fixed issue

* Fixed an issue where attempting to update organization settings on the *Manage* view may not function as expected.

---

## Platform Management 13.12.0 - 7 Nov 2023

Platform Management 13.12.0 is a minor release which includes two new features, one improvement, and two fixed issues.

### New features

* Added social authentication options to the *Marketplace Settings* view. This allows for OAuth-based integration with GitHub, Gitlab, or Google to allow authentication and sign-up for consumer org users.
* Added the ability to customize the *Help & Resources Menu* on the organization *Manage* view.

### Improvement

* Removed *Runtime Services Admin* role from all users to which it was assigned. This role is no longer valid or grants no permissions.
* Improved handling of email address fields to be permissive of mixed case values.

### Fixed issues

* Fixed an issue where users assigned *Developer* role in teams to which marketplace access has been granted may not see the marketplace on the *Marketplaces* view or in navigation elements.
* Fixed an issue where performing manual entry of usage data may not function as expected.


---

## Platform Management 13.11.1 - 17 Oct 2023

Platform Management 13.11.1 is a patch release which includes one fixed issue.

### Fixed issue

* Fixed an issue where events may not be shown as expected on the organization *Activity* view.


---

## Platform Management 13.11.0 - 12 Oct 2023

Platform Management 13.11.0 is a minor release which includes one new feature, two improvements, and one fixed issue.

### New feature

* Added links to **Document Library** in the common navigation service switcher and *Platform Home* view.

### Improvements

* Added *Support Access Code* to the *Organization* view.
* Improved validation for email addresses to enforce a maximum length for local segment independent of domain length.

### Fixed issue

* Fixed an issue where exporting *Marketplace Appearance* settings may not work as expected.


---

## Platform Management 13.10.1 - 27 Sep 2023

Platform Management 13.10.1 is a patch release which includes one changed behavior and two fixed issues.

### Changed behavior

* Increased number of users that may be invited before hitting invitation limit.

### Improvement

* Fixed an issue where environments removed from *Central* may still show in the **Platform** *Environments* view.
* Fixed an issue where attempting to remove color settings on the *Marketplace Footer* view may put the form in a bad state.


---

## Platform Management 13.10.0 - 7 Sep 2023

Platform Management 13.10.0 is a minor release which includes one new feature and one improvement.

### New feature

* Added the ability to opt out of third-party support services to the organization *Security & Privacy Settings* view.

### Improvement

* Simplified grouping and improved organization, labels, and hints for *Theme* fields on the *Marketplace Appearance* view.


---

## Platform Management 13.9.2 - 1 Sep 2023

Platform Management 13.9.2 is a patch release which includes one changed behavior and one fixed issue.

### Changed behavior

* **Amplify Platform** password policy now enforces a maximum length of 128 characters.

### Fixed issue

* Fixed an issue where providing an invalid code when attempting setup of multi-factor authentication using an Authenticator app may result in an error message. With this fix, it will now respond with a message indicating the code was invalid.


---

## Platform Management 13.9.1 - 25 Aug 2023

Platform Management 13.9.1 is a patch release which includes one fixed issue.

### Fixed issue

* Fixed an issue where the *Marketplaces* view may incorrectly display a published product count of zero.


---

## Platform Management 13.9.0 - 24 Aug 2023

Platform Management 13.9.0 is a minor release which includes one new feature and several fixed issues.

### New feature

* Extended theme settings captured on *Marketplace Appearance* to support page background and container colors. Improved grouping and clarity of labeling for existing theme settings.

### Fixed issues

* Fixed an issue where the *Usage* view may have displayed the API Gateway Outbound Volume usage for non-production environments as counting against entitled quota.
* Fixed an issue where removing teams from Administration, Publication, or Consumption Preference on *Marketplace Settings* view may not save as expected.
* Fixed an issue where the *Edit User* view may not display breadcrumbs correctly for users that are not yet activated.


---

## Platform Management 13.8.5 - 9 Aug 2023

Platform Management 13.8.5 is a patch release which includes one fixed issue.

### Fixed issue

* Fixed an issue where malformed certificates uploaded on the *Marketplace Settings* view may have not been properly validated.


---

## Platform Management 13.8.4 - 7 Aug 2023

Platform Management 13.8.4 is a patch release which includes one fixed issue.

### Fixed issue

* Fixed an issue where editing content in textareas may not behave as expected.


---

## Platform Management 13.8.3 - 17 Jul 2023

Platform Management 13.8.3 is a patch release which includes one improvement.

### Improvement

* Extended Cache-Control headers for static assets in an attempt to improve caching behavior for proxy servers.


---

## Platform Management 13.8.2 - 29 Jun 2023

Platform Management 13.8.2 is a patch release which includes one fixed issue.

### Fixed issue

* Fixed an issue where volume entitlements' quotas and usage on the *Monthly Usage* view may be inadvertently rounded to integer values.


---

## Platform Management 13.8.1 - 22 Jun 2023

Platform Management 13.8.1 is a patch release which includes several fixed issues.

### Fixed issues

* Fixed an issue where an invalid or unregistered URL entered on the *Marketplace Settings* view may receive a generic error response. The response now indicates that the URL was invalid.
* Fixed an issue on the *Monthly Usage* view where numeric entitlements for renewing subscriptions may show an incorrect quota.
* Fixed an issue where changes on the *Marketplace Settings* view when no Sitename value is set may cause Sitename to show as changed on the *Activity* view.
* Fixed an issue where users in certain versions of Safari may experience issues viewing the *Users* or *Account* views.


---

## Platform Management 13.8.0 - 12 Jun 2023

Platform Management 13.8.0 is a minor release which includes several new features, one improvement, several changed behaviors, and several fixed issues.

### New features

* Added a *Marketplace Activity* view containing events related to the management of your marketplace and its assets as well as actions performed by consumer org members. The events can be filtered by date range, event type, or consumer org.
* Added an *Activity* link from the *Marketplace Consumer Orgs* view linking to the *Marketplace Activity* view for the selected consumer org.
* Added a toggle to the *Marketplace Settings* view allowing organization Administrator and Marketplace Manager role users to enable *Identity Provider* support for the marketplace's consumer orgs.

### Improvement

* Added the ability for Platform-managed usage environments for which no usage has been reported to be deleted.

### Changed behaviors

* Removed **Unified Catalog** branding capabilities under organization settings.
* Relocated organization logo upload to the organization settings *Manage* view.
* Removed "Featured Products" option from the "Featured Content" selection on *Marketplace Homepage* view.

### Fixed issues

* Fixed an issue where an "Unentitled Usage" section may be shown on the *Usage Report* view showing usage for Analytics Events.
* Fixed an issue on the *Usage Report* view where usage not matching a subscription's governance may not be shown as "Unentitled Usage."
* Fixed an issue on the *Manage User* view where deselecting Administrator role for the organization's primary contact may put the roles list into a bad state.
* Fixed an issue where changing the "Publication Preference" on the *Marketplace Settings* view from "Included/Excluded Teams" to "Include Teams with Tags" may cause the previously selected team's identifiers to be shown as tags.
* Fixed an issue where malformed HTML content in an element on the *Marketplace Footer* view may disallow the element from being deleted.


---

## Platform Management 13.7.0 - 7 Jun 2023

Platform Management 13.7.0 is a minor release which includes one new feature.

### New feature

* Added Consumption Preference to the *Marketplace Settings* view to allow organization administrators to control which teams' Consumer role members are allowed to access that marketplace.


---

## Platform Management 13.6.1 - 1 Jun 2023

Platform Management 13.6.1 is a patch release which includes one fixed issue.

### Fixed issue

* Fixed an issue where users attempting to access marketplaces hosted on custom URLs may experience an error loading the common navigation header.


---

## Platform Management 13.6.0 - 31 May 2023

Platform Management 13.6.0 is a minor release which includes several new features, one improvement, several changed behaviors, and several fixed issues.

### New features

* Added a *Marketplace Activity* view containing events related to the management of your marketplace and its assets as well as actions performed by consumer org members. The events can be filtered by date range, event type, or consumer org.
* Added an *Activity* link from the *Marketplace Consumer Orgs* view linking to the *Marketplace Activity* view for the selected consumer org.
* Added a toggle to the *Marketplace Settings* view allowing organization Administrator and Marketplace Manager role users to enable *Identity Provider* support for the marketplace's consumer orgs.

### Improvement

* Added the ability for Platform-managed usage environments for which no usage has been reported to be deleted.

### Changed behaviors

* Removed **Unified Catalog** branding capabilities under organization settings.
* Relocated organization logo upload to the organization settings *Manage* view.
* Removed "Featured Products" option from the "Featured Content" selection on *Marketplace Homepage* view.

### Fixed issues

* Fixed an issue where an "Unentitled Usage" section may be shown on the *Usage Report* view showing usage for Analytics Events.
* Fixed an issue on the *Usage Report* view where usage not matching a subscription's governance may not be shown as "Unentitled Usage."
* Fixed an issue on the *Manage User* view where deselecting Administrator role for the organization's primary contact may put the roles list into a bad state.
* Fixed an issue where changing the "Publication Preference" on the *Marketplace Settings* view from "Included/Excluded Teams" to "Include Teams with Tags" may cause the previously selected team's identifiers to be shown as tags.
* Fixed an issue where malformed HTML content in an element on the *Marketplace Footer* view may disallow the element from being deleted.


---

## Platform Management 13.5.1 - 17 May 2023

Platform Management 13.5.1 is a patch release which includes one behavior change and one improvement.

### Changed behavior

* Organizations which have no activity in greater than 180 days will be notified of their inactivity and potential removal if no activity occurs within the organization in the next 30 days. Previously, this process only occurred if the organization had all its subscriptions expired for more than the inactivty window. With this change, since organizations created via signup may have no subscriptions, they will also be subject to this process. Organizations marked as license or contract holders or those which have a Support Access Code set are excluded from this process.

### Improvement

* Improved visibility of recently uploaded usage files when uploading on the *Report History* view. Added a "Refresh" control on the *Usage* and *Report History* views to fetch latest data.



---

## Platform Management 13.5.0 - 11 May 2023

Platform Management 13.5.0 is a minor release which includes one new feature and one fixed issue.

### New feature

* For organizations entitled to **Amplify Enterprise Marketplace**, a new *Marketplace Billing* view allows capture of billing integration settings with Stripe as the first supported vendor.

### Fixed issue

* Fixed an issue on the *Marketplace Footer* view where HTML markup entry in text blocks may not function as expected in some older browser versions.


---

## Platform Management 13.4.2 - 8 May 2023

Platform Management 13.4.2 is a patch release which includes one fixed issue.

### Fixed issue

* Fixed an issue on the *Devices* view where users may experience an error when selecting an action from the dropdown when no devices are listed.


---

## Platform Management 13.4.1 - 28 Apr 2023

Platform Management 13.4.1 is a patch release which includes one fixed issue.

### Fixed issue

* Fixed an issue where organizations with a large number of users may experience errors performing certain *Identity Provider* management actions.


---

## Platform Management 13.4.0 - 26 Apr 2023

Platform Management 13.4.0 is a minor release which includes one new feature and one fixed issue.

### New feature

* Organizations with active **Amplify Integration** subscriptions may now configured Integration environments. These environments will be linked to from a new capabilty on *Platform Home* and in the common navigation header's service switcher.

### Fixed issue

* Fixed an issue where marketplaces may show the organization branding's logo prior to a logo being uploaded on the *Marketplace Appearance* view.


---

## Platform Management 13.3.0 - 18 Apr 2023

Platform Management 13.3.0 is a minor release which includes four improvements.

### Improvements

* Added a new Usage Reporter organization level role. This role can be assigned to service accounts and users within your organization to allow them to register environments and report usage without granting additional administrative roles or permissions.
* Improved clarity of uploaded file statuses on the *Usage Report History* view. Files containing at least one valid metric will now be shown with a status of "Partially Accepted". Files containing no valid metrics will have a status of "Invalid Metrics". Both provide an icon which will list the invalid metrics contained in the file when hovered over.
* Readded the Switch Org menu to the common navigation header for consumer role users.
* Added an option on the *Identity Providers* view to bypass email verification for subdomains of parent domains associated to an identity provider.


---

## Platform Management 13.2.0 - 5 Apr 2023

Platform Management 13.2.0 is a minor release which includes three new features and one improvement.

### New features

* Added ability to set visibility in *Marketplace Menus* to control whether menu items are shown when marketplace visitors are signed in or out.
* Added *Identity Provider* configuration support for **Amplify Enterprise Marketplace** consumer organizations.
* Added an option on the *Identity Provider* configuration view to allow users which can sign in with the identity provider, but do not have email addresses on an associated domain, to be provisioned into the organization.

### Improvement

* Revised dark theme to increase contrast and brighten actionable elements.


---

## Platform Management 13.1.0 - 22 Mar 2023

Platform Management 13.1.0 is a minor release which includes two new features, one improvement, and several fixed issues.

### New features

* This release introduces a new Marketplace Manager role assignable on your organization's teams. A new Administration Preference captured on the *Marketplace Settings* view enables organization administrators to select when team's Marketplace Manager role members can modify settings, appearance, and menu, footer, and homepage content for that marketplace.
* Added Publication Preference to *Marketplace Settings* view to allow organization administrators to control which teams' Catalog Manager role members are allowed to publish products to that marketplace.

### Improvement

* Added pagination controls to the Environments view.

### Fixed issue

* Fixed an issue where analytics chart views may not display their series legends in the accompanying table.
* Fixed an issue where the left navigation for app views may not display the app name.
* Fixed an issue where *Apps* view table may not allow sorting by app name or type.


---

## Platform Management 13.0.0 - 14 Mar 2023

Platform Management 13.0.0 is a major release which includes one behavior change, one new feature, and one improvement.

{{% alert title="Note" color="primary" %}}
With this release, Platform Management API endpoints related to use of **Mobile Backend Services** and **Amplify Runtime Services** previously marked as deprecated have be removed. All remaining **Amplify Runtime Services* environments have been decommissioned. Application types served by those environments will no longer be visible with the Platform.
{{% /alert %}}

## Behavior change

* Removed filtering by application type on the *Apps* view.

### New feature

* Added a *Marketplace Footer* view to capture settings for a customizable footer displayed on all **Marketplace** and related authentication views.

### Improvement

* The Help Menu and Nav Items captured previously on the *Marketplace Appearance* view have been relocated to a new *Marketplace Menus* view.
