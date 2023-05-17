---
title: Platform Management 13.5.1 release notes
linkTitle: Platform Management 13.5.1 release notes
weight: 45
date: 2023-05-17
Hide_readingtime: true
---

## Platform Management 13.5.1 - 17 May 2023

Platform Management 13.5.1 is a patch release which includes one behavior change and one improvement.

## Changed behavior

* Organizations which have no activity in greater than 180 days will be notified of their inactivity and potential removal if no activity occurs within the organization in the next 30 days. Previously, this process only occurred if the organization had all its subscriptions expired for more than the inactivty window. With this change, since organizations created via signup may have no subscriptions, they will also be subject to this process. Organizations marked as license or contract holders or those which have a Support Access Code set are excluded from this process.

## Improvement

* Improved visibility of recently uploaded usage files when uploading on the *Report History* view. Added a "Refresh" control on the *Usage* and *Report History* views to fetch latest data.
