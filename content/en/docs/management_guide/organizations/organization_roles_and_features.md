---
title: Organization roles and features
linkTitle: Organization roles and features
weight: 20
date: 2021-08-12
---
This section is about organization user roles and features. Users can be assigned different roles that grant them the rights to the Platform associated with their assigned roles and capabilities. A user always needs to be assigned one platform role and can be assigned zero, one, or more of the other roles.

## Roles and capabilities

The following table shows the available roles and capabilities.

| Role                      | Short Description                                     | Platform | Central | Catalog |  Teams |
| ------------------------- | ----------------------------------------------------- | -------- | ------- | ------- | ------ |
| Administrator             | Use for platform administrative tasks                 | X        |         |         | X      |
| Developer                 | Use for development and integration projects          | X        | X       | X       | X (my teams) |
| Consumer                  | Use for the consumption of services from the catalog  |          |         | X       |        |
| **Platform Roles**        |                                                       |          |         |         |        |
| Usage Reporter            | Use for registering usage environments and reporting usage | X   |         |         |        |
| **Central Roles**         |                                                       |          |         |         |        |
| Central Admin             | Use for all-encompassing access to Central            |          | X       | X       |        |

## Team roles

Users also have a role in each team they belong to.

| Team Role | Short Description | Provider | Consumer |
| --- | --- | --- | --- |
| Team Manager | Use this role to manage the members of the team and their role assignments | x | x |
| Consumer | Use this role to view and consume products in the Marketplace |   | x |
| Developer** | Use this role to manage assets in Amplify | x |   |
| Marketplace Manager | Use this role to manage Marketplace settings, appearance, and content | x |   |
| Catalog Manager** | Use this role to manage product and approve subscriptions and Access Requests | x |   |
| Subscriber | Use this role to manage Marketplace subscriptions and view usage |   | x |
| Subscription Approver** | Use this role to approve Marketplace Subscriptions and Access Requests | x |   |

** If a *Provider* user is part of a single team with the `x-private` tag, then they will not have access to Amplify Central to execute their tasks. Provider users should not use the `x-private` tag in their provider teams, as it meant to be used only for *Consumer* users.

## Team roles and capabilities

The following table shows the available team roles and capabilities. The Central Admin role has access to all team capabilities.

| Capabilities                            | Catalog Manager         | Subscription Approver   | Subscriber              | Marketplace Manager     | Developer               | Consumer           | Team Manager            |
| --------------------------------------- | ----------------------- | ----------------------- | ----------------------- | ----------------------- | ----------------------- | ------------------ | ----------------------- |
| **Marketplace**                         |                         |                         |                         |                         |                         |                    |                         |
| View products                           | x (my team)             |                         | x (my team)             |                         | x (my team)             | x (my team)        |                         |
| Subscribe                               | x (free plan only)      |                         | x (free plan only)      |                         | x (free plan only)      | x (free plan only) |                         |
| View application subscriptions          | x (my team)             | x (my team)             | x (my team)             |                         | x (my team)             | x (my team)        |                         |
| Manage subscriptions                    | x (my team)             |                         | x (my team)             |                         | x (my team)             | x (my team)        |                         |
| Approve/reject subscriptions            | x (my team)             | x (my team)             | x (my team)             |                         |                         |                    |                         |
| View consumer access request            | x (my team)             |                         | x (my team)             |                         | x (my team)             | x (my team)        |                         |
| Approve/reject access requests          | x (my team)             | x (my team)             |                         |                         |                         |                    |                         |
| Delete consumer access request          | x (my team)             | x (my team)             | x (my team)             |                         | x (my team)             | x (my team)        |                         |
| View my subscription                    | x (my team)             |                         | x (my team)             |                         | x (my team)             | x (my team)        |                         |
| Create application                      | x (my team)             |                         | x (my team)             |                         | x (my team)             | x (my team)        |                         |
| View application                        | x (my team)             |                         | x (my team)             |                         | x (my team)             | x (my team)        |                         |
| Delete application                      | x (my team)             |                         | x (my team)             |                         | x (my application)      | x (my application) |                         |
| Update application                      | x (my team)             |                         | x (my team)             |                         | x (my application)      | x (my application) |                         |
| **Environments**                        |                         |                         |                         |                         |                         |                    |                         |
| Create environments                     |                         |                         |                         |                         |                         |                    |                         |
| View environments                       | x (my team)                      |                         |                         |                 |  x (my team)                        |                    |                         |
| Delete environments                     |                         |                         |                         |                         |                         |                    |                         |
| Update environments                     |                         |                         |                         |                         |                         |                    |                         |
| **Services**                            |                         |                         |                         |                         |                         |                    |                         |
| Create a service                        |                         |                         |                         |                         | x (my team              |                    |                         |
| View a service                          |                         |                         |                         |                         | x (my team)             |                    |                         |
| Delete a service                        |                         |                         |                         |                         | x (my team)             |                    |                         |
| Update a service                        |                         |                         |                         |                         | x (my team)             |                    |                         |
| **Assets**                              |                         |                         |                         |                         |                         |                    |                         |
| Create an asset                         |                         |                         |                         |                         | x (my team)             |                    |                         |
| View an asset                           |                         |                         |                         |                         | x (my team)             |                    |                         |
| Delete an asset                         |                         |                         |                         |                         | x (my team)             |                    |                         |
| Update an asset                         |                         |                         |                         |                         | x (my team)             |                    |                         |
| **Products**                            |                         |                         |                         |                         |                         |                    |                         |
| Create a product                        | x (my team)             |                         |                         |                         |                         |                    |                         |
| View a product                          | x (my team)             |                         |                         |                         |                         |                    |                         |
| Delete a product                        | x (my team)             |                         |                         |                         |                         |                    |                         |
| Update a product                        | x (my team)             |                         |                         |                         |                         |                    |                         |
| Set product visibility                  | x (my team)             |                         |                         |                         |                         |                    |                         |
| Publish a product to the Marketplace    | x (my team)             |                         |                         |                         |                         |                    |                         |
| **Categories**                          | *Team level/Enterprise* |                         |                         |                         | *Team level/Enterprise* | *Enterprise level* | *Team level/Enterprise* |
| Create a category                       |                         |                         |                         |                         |                         |                    |                         |
| View a category                         |                         |                         |                         |                         |                         |                    |                         |
| Delete a category                       |                         |                         |                         |                         |                         |                    |                         |
| Update a category                       |                         |                         |                         |                         |                         |                    |                         |
| Assign to a category                    |                         |                         |                         |                         |                         |                    |                         |
| **Business Insights**                   |                         |                         |                         |                         |                         |                    |                         |
| View transactions for my subscriptions  | x (my team)             |                         |                         |                         | x (my team)             | x (my team)        |                         |
| View transactions for my assets         | x (my team)             |                         |                         |                         | x (my team)             | x (my team)        |                         |
| **Marketplaces (Platform)**             |                         |                         |                         |                         |                         |                    |                         |
| Update marketplace settings/appearance  |                         |                         |                         | x (my team)             |                         |                    |                         |
| **Teams & Members (Platform)**          |                         |                         |                         |                         |                         |                    |                         |
| Create a team                           |                         |                         |                         |                         |                         |                    |                         |
| View teams                              | x (my team)             |                         |                         |                         | x (my team)             |                    | x (my team)             |
| Update team                             |                         |                         |                         |                         |                         |                    | x (my team)             |
| Delete team                             |                         |                         |                         |                         |                         |                    |                         |
