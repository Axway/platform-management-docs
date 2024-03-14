---
title: Platform Management 13.0.0 and later release notes
linkTitle: Platform Management 13.0.0 and later release notes
weight: 50
simple_list: true
date: 2024-03-13
---

New features, improvements, and bug fixes for releases 13.0.0 and later.

{{% alert title="Note" color="primary" %}}
{{% /alert %}}


---

## Platform Management 13.18.0 - 13 Mar 2024

Platform Management 13.18.0 is a minor release which includes .





---

## Platform Management 13.17.3 - 29 Feb 2024

Platform Management 13.17.3 is a patch release which includes one fixed issue.





---

## Platform Management 13.17.2 - 14 Feb 2024

Platform Management 13.17.2 is a patch release which includes one fixed issue.






---

## Platform Management 13.17.1 - 13 Feb 2024

Platform Management 13.17.1 is a patch release which includes one fixed issue.




---

## Platform Management 13.17.0 - 12 Feb 2024

Platform Management 13.17.0 is a minor release which includes .







---

## Platform Management 13.16.0 - 01 Feb 2024

Platform Management 13.16.0 is a minor release which includes .





---

## Platform Management 13.15.1 - 25 Jan 2024

Platform Management 13.15.1 is a patch release which includes one fixed issue.




---

## Platform Management 13.15.0 - 18 Jan 2024

Platform Management 13.15.0 is a minor release which includes .





---

## Platform Management 13.14.1 - 12 Dec 2023

Platform Management 13.14.1 is a patch release which includes one fixed issue.




---

## Platform Management 13.14.0 - 07 Dec 2023

Platform Management 13.14.0 is a minor release which includes .






---

## Platform Management 13.13.0 - 29 Nov 2023

Platform Management 13.13.0 is a minor release which includes .










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
