---
title: Platform Management 13.9.2 release notes
linkTitle: Platform Management 13.9.2 release notes
weight: 33
date: 2023-09-01
Hide_readingtime: true
---

## Platform Management 13.9.2 - 1 Sep 2023

Platform Management 13.9.2 is a patch release which includes one changed behavior and one fixed issue.

## Changed behavior

* **Amplify Platform** password policy now enforces a maximum length of 128 characters.

## Improvement

* Fixed an issue where providing an invalid code when attempting setup of multi-factor authentication using an Authenticator app may result in an error message. With this fix, it will now respond with a message indicating the code was invalid.
