---
title: Platform Management 7.3.4 release notes
linkTitle: Platform Management 7.3.4 release notes
weight: 3
date: 2021-08-12
Hide_readingtime: true
---

## Platform Management 7.3.4 - 29 May 2020

Platform Management 7.3.4 is a patch release, which includes an improvement and a bug fix.

## Improvements

* Improved password validation to disallow values containing personally identifiable information and implemented stronger password hashing based on [PBKDF2](https://www.pbkdf2.com/).

## Fixed Issues

* Fixed an issue where users may not be able to upload iOS push certificates for Mobile Backend Services datasources.
* Fixed an issue where Mobile Backend Services Database Storage and File Storage usage may show as zero GB on the organization's _Usage_ view.
