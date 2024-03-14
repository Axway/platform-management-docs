---
title: Platform Management 12.0.0 - 12.8.2 release notes
linkTitle: Platform Management 12.0.0 - 12.8.2 release notes
weight: 60
simple_list: true
date: 2023-03-09
---
<!-- markdownlint-disable  MD024/no-duplicate-heading/no-duplicate-header --->

New features, improvements, and bug fixes for releases 12.0.0 - 12.8.2.

---

## Platform Management 12.8.2 - 09 Mar 2023

Platform Management 12.8.2 is an incremental release which includes one improvement and one fixed issue.

### Improvement

* Improved performance when searching within the *Usage Report History* view.

### Fixed issue

* Fixed an issue on the *Edit User* view where a user designated as the organization's primary contact could previously be demoted from the required Administator role.

---

## Platform Management 12.8.1 - 28 Feb 2023

Platform Management 12.8.1 is an incremental release which includes one improvement and two fixed issues.

{{% alert title="Note" color="primary" %}}
With this release, Platform Management API endpoints related to use of **Mobile Backend Services** and **Amplify Runtime Services** have been marked as deprecated and will be removed in a future release.
{{% /alert %}}

### Improvement

* Added informative modals to the *Edit User* view when an organization administrator changes the user's Identity Provider restriction. These modals indicate when next steps must be performed by the user in order for the change to apply.

### Fixed issues

* Fixed an issue on the *Edit User* view where a previously selected Identity Provider restriction may not be correctly displayed.
* Fixed an issue on the *Marketplace Homepage* settings view where the Hero Banner background gradient options may be incorrectly displayed.

---

## Platform Management 12.8.0 - 21 Feb 2023

Platform Management 12.8.0 is a minor release which includes one new feature and two fixed issues.

### New feature

* Administrators of organizations which are entitled to multiple marketplaces may now remove unneeded marketplaces from the *Marketplaces* view.

### Fixed issues

* Fixed an issue on the *Custom Query* view where non-numeric fields could be selected for numeric methods, such as average or sum, which may have resulted in an error. Field selection is now limited to known numeric event fields.
* Fixed an issue on the *Real Time Analytics* view where data in the charts may not be displayed correctly.

---

## Platform Management 12.7.0 - 31 Jan 2023

Platform Management 12.7.0 is a minor release which includes two improvements and one fixed issue.

### Improvements

* Improved authentication flow experience when signing in from a marketplace and the provided user's email is associated with a **Platform** organization. If the address is associated with one or more consumer organizations for the marketplace, the user will be prompted to select which account they wish to sign in to.
* Added counts for published products and subscriptions on the *Marketplaces* view.

### Fixed issue

* Fixed an issue where user event type was selectable on the organization *Activity* view and may cause unexpected behavior when selected. User events are displayed on the user's *Activity* view.

---

## Platform Management 12.6.0 - 23 Jan 2023

Platform Management 12.6.0 is a minor release which includes one changed behavior, one new feature, and two fixed issues.

### Changed behavior

* With the **Flow Manager** 2.0 release, the Auditor role assignment is no longer available. The common navigation header's service switcher no longer contains a link to **Flow Manager** SaaS service. The *Overview* menu no longer contains links to the *Audit Search* UI.

### New feature

* The *Edit Identity Provider* form view now provides the ability to export and import its configuration.

### Fixed issues

* Fixed an issue where some details in *Activity* views may display an entity's identifier rather than its name.
* Fixed an issue where attempting to navigate away from the *Marketplace Settings* view after saving changes may cause an unexpected confirmation dialog that the form has unsaved changes to show.

---

## Platform Management 12.5.1 - 12 Jan 2023

Platform Management 12.5.1 is a patch release which includes two improvements and one changed behavior.

### Improvements

* The *Usage* view now includes all usage which has been reported regardless of whether the organization has a qualifying quota for the metric. Usage for unentitled metrics is displayed in a separate *Unentitled* section below usage for the subscribed offerings and their metrics.
* Improved validation for certificates uploaded for URL configured on the *Marketplace Settings* view.

### Changed behavior

* The ability to enable and configure *Marketplace Homepage* content is now limited to organizations which have a Public Marketplace entitlement.

---

## Platform Management 12.5.0 - 15 Dec 2022

Platform Management 12.5.0 is a minor release which includes one new feature, two improvements, and one fixed issue.

### New feature

* With this release, organizations which are entitled may configure multiple marketplaces. See the document for more information on [publishing products to one or more marketplaces](https://docs.axway.com/bundle/amplify-central/page/docs/manage_marketplace/publish_to_marketplace/index.html).

### Improvements

* Organizations which were previously entitled and had established marketplaces may still access the *Marketplaces* view.
* Non-administrator role users may now access the *Marketplaces* view in order to navigate to the organization's marketplaces.

### Fixed issue

* Fixed an issue where users logging into marketplaces which have been configured to run on a custom URL may not be redirected to the marketplace after authenticating.

---

## Platform Management 12.4.0 - 8 Dec 2022

Platform Management 12.4.0 is a minor release which includes one feature and one improvement.

### New feature

* Added an option on *Marketplace Settings* to require approval for newly registered consumer orgs before allowing access to the corresponding marketplace.

### Improvement

* Added counts for Asset Catalog assets, Product Foundry products, Marketplace subscriptions, and consumer organizations, teams, and users to the **API Management** *Overview* view.

---

## Platform Management 12.3.1 - 5 Dec 2022

Platform Management 12.3.1 is a patch release which includes one new feature, one improvement, and one fixed issue.

### New feature

* Asia-Pacific (Singapore) is now an available region during sign-up.

### Improvement

* Limited organization metadata will now always be included when selecting any organization related data types during account data export.

### Fixed issue

* Fixed an issue where the *Homepage* action link on the *Marketplaces* view inadvertently linked to the *Appearances* view.

---

## Platform Management 12.3.0 - 1 Dec 2022

Platform Management 12.3.0 is a minor release which includes four new features and two improvements.

### New features

* Added the ability to assign a custom title to featured content setting in *Marketplace Homepage* settings view.
* Introduced session management features to the *Account* allowing users to revoke their sessions and see their corresponding activity.
* Added data export features to the organization *Manage* view allowing users to download their organization's metadata and related data.
* Added data export features to the user account *Settings* view allowing users to download their user and organizations' metadata and related data.

### Improvements

* Added a *Marketplaces* view and updated related views to use tabbed navigation.
* Added controls to table views to toggle layout between tabular and card layouts.

---

## Platform Management 12.2.0 - 21 Nov 2022

Platform Management 12.2.0 is a minor release which includes two new features, one improvement, and one fixed issue.

### New features

* Added the ability to configure a custom marketplace URL and matching certificate on the *Marketplace Settings* view.
* Added a new Rate method to the *Custom Query* view to calculate event rates per unit of time.

### Improvement

* Users assigned Consumer role in an organization entitled to **Amplify Enterprise Marketplace** will now be redirected to the marketplace after signing in.

### Fixed issue

* Fixed an issue where users signing into a marketplace with an external Identity Provider may not redirected back to the marketplace afterward.

---

## Platform Management 12.1.0 - 1 Nov 2022

Platform Management 12.1.0 is a minor release which includes several new features and one improvement.

### New features

* Added a Consumer Organizations toggle to *Marketplace Settings* view to allow consumers outside of your organization to access your Marketplace.
* Added settings for a new Navigation Menu in *Marketplace Appearance* view.
* Added settings for a new Call To Action block in *Marketplace Homepage* view.

### Improvement

* Improved navigation within organization *Users* table and *Manage User* views.

---

## Platform Management 12.0.1 - 20 Oct 2022

Platform Management 12.0.1 is a patch release which includes one behavior change.

### Changed behavior

* Previously new users activating their account would be automatically signed in. Now users will be redirected to sign in after activation.

---

## Platform Management 12.0.0 - 19 Oct 2022

Platform Management 12.0.0 is a major release which includes one new feature, one improvement, and one fixed issue.

### New feature

* Added new *Consumer Orgs* view for organizations entitled to **Marketplace** listing organizations which have signed up for their marketplace along with their counts of teams and users.

### Improvement

* Users may now be assigned multiple roles within a team. Some team roles have been renamed. See the [Team roles documentation](https://docs.axway.com/bundle/platform-management/page/docs/management_guide/organizations/organization_roles_and_features/index.html#team-roles) for more information.

### Fixed issue

* Fixed an issue where users attempting to switch their signed-in organization to an inactive or invalid organization would regenerate a session in their prior signed-in organization.
