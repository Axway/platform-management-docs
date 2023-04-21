---
title: Platform Management 13.3.0 release notes
linkTitle: Platform Management 13.3.0 release notes
weight: 51
date: 2023-04-05
Hide_readingtime: true
---

## Platform Management 13.3.0 - 5 Apr 2023

Platform Management 13.3.0 is a minor release which includes four improvements.

## Improvements

* Added a new Usage Reporter organization level role. This role can be assigned to service accounts and users within your organization to allow them to register environments and report usage without granting additional administrative roles or permissions.
* Improved clarity of uploaded file statuses on the *Usage Report History* view. Files containing at least one valid metric will now be shown with a status of "Partially Accepted". Files containing no valid metrics will have a status of "Invalid Metrics". Both provide an icon which will list the invalid metrics contained in the file when hovered over.
* Readded the Switch Org menu to the common navigation header for consumer role users.
* Added an option on the *Identity Providers* view to bypass email verification for subdomains of parent domains associated to an identity provider.
