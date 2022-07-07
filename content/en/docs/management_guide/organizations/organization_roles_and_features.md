---
title: Organization roles and features
linkTitle: Organization roles and features
weight: 20
date: 2021-08-12
---
This section is about organization user roles and features. Users can be assigned different roles that grant them the rights to the Platform associated with their assigned roles and capabilities. A user always needs to be assigned one platform role and can be assigned zero, one, or more of the other roles.

## Roles and capabilities

The following table shows the available roles and capabilities.

| Role                      | Short Description                                     | Platform | App Integration | Central | Catalog | ARS | MBaaS | Teams | Audit | Flow Manager |
| ------------------------- | -----------------------------------------------       | -------- | --------------- | ------- | ------- | --- | ----- | ----- | ----- | ------------ |
| **Platform Roles**        |                                                       |          |                 |         |         |     |       |       |       |              |
| Administrator             | Use for platform admin tasks                          | X        | X               | X       | X       |     |       | X     |       |              |
| Developer                 | Use for development and integration projects          | X        | X               | X       | X       | X   | X     | X     |       |              |
| Consumer                  | Use for the consumption of services from the catalog  |          |                 | X       | X       |     |       |       |       |              |
| **Runtime Services Roles**| **Runtime Services** is deprecated and will be discontinued effective September 1, 2022.     |         |     |       |       |       |              |     |     |     |
| Runtime Services Admin    | Use for all-encompassing access to Runtime Services   |          |                 |         |         | X   | X     |       |       |              |
| **Central Roles**         |                                                       |          |                 |         |         |     |       |       |       |              |
| Central Admin             | Use for all-encompassing access to Central            |          |                 | X       | X       |     |       |       |       |              |
| **Flow Manager Roles**    |                                                       |          |                 |         |         |     |       |       |       |              |
| Access Manager            | Use for full management of services, organizations, identity stores and users. Allows viewing and editing roles and privileges.      |              |                 |         |         |     |       |       |       | X            |
| Auditor                    | Allows access to Search Audit UI                     |          |                 |         |         |     |       |       |       | X            |
| Integration Specialist     | Use for management of applications, application groups, partners, flow patterns, templates, subscriptions, flows and transfers. Grants viewing of products, product configurations and partners.                                                        |          |                 |         |         |     |       |       |       | X            |
| IT Admin                   | Use for management of Flow Manager configurations, organizations, identity stores and users. Grants viewing of alerts management.<br /><br />Role enables access rights to user audit.                                                                      |          |                 |         |         |     |       |       |       | X            |
| Products Admin             | Use for full management of products, product configurations, policies, product groups. Grants viewing of user audit events.                                                                             |          |                 |         |         |     |       |       |       | X            |
| Promoter Specialist        | Use for forced deletion of templates and subscriptions.    |    |                 |         |         |     |       |       |       | X            |
| Special Operations Admin   | Use for forced deletion of templates and subscriptions.    |    |                 |         |         |     |       |       |       | X            |
| Subscription Approver      | Use to view published templates, approve subscriptions, and reject subscriptions. Grants viewing of partners, applications, and products. For business user for subscription approvals.                                                             |          |                 |         |         |     |       |       |       | X            |
| Subscription Specialist    | Use to manage subscriptions                          |          |                 |         |         |     |       |       |       | X            |
| Template Publisher         | Use to view, publish, and edit templates. For business user for template publishing. |   |     |      |     |       |      |     |  | X            |
| Transfer CFT Admin         | Use for full management of Transfer CFT              |          |                 |         |         |     |       |       |       | X            |

## Team roles

Users also have a role in each team they belong to.

| Team Role          | Short Description                                                         |
| ------------------ | ------------------------------------------------------------------------- |
| Administrator      | Use this role to manage the members of the team                           |
| Consumer           | Use this role to view and consume assets in the Unified Catalog           |
| Developer          | Use this role to manage assets in Amplify Central and the Unified Catalog |
| Catalog Manager    | Use this role to manage Unified Catalog items and approve subscriptions   |
| Subscription Admin | Use this role to manage Marketplace subscriptions and view usage          |

## Team roles and capabilities

The following table shows the available team roles and capabilities. The Central administrator role has access to all team capabilities.

| Capabilities                            | Catalog Manager         | Subscription Admin      | Developer               | Consumer           | Administrator           |
| --------------------------------------- | ----------------------- | ----------------------- | ----------------------- | ------------------ | ----------------------- |
| **Unified Catalog**                     |                         |                         |                         |                    |                         |
| Create catalog items                    | x (my team)             |                         | x (my team)             |                    |                         |
| View catalog items                      | x (my team)             |                         | x (my team)             | x                  |                         |
| Delete catalog items                    | x (my team)             |                         |                         |                    |                         |
| Share a catalog item                    | x (my team)             |                         |                         | x                  |                         |
| Edit a catalog item                     | x (my team)             |                         | x (my team)             |                    |                         |
| Create my subscriptions                 | x (my team)             |                         | x (my team)             | x (my team)        |                         |
| View my subscriptions                   | x (my team)             |                         | x (my team)             | x (my team)        |                         |
| Update my subscriptions                 | x (my team)             |                         | x (my team)             | x (my team)        |                         |
| View consumer's subscriptions           | x (my team assets)      |                         |                         |                    |                         |
| Delete consumer's subscriptions         | x (my team assets)      |                         |                         |                    |                         |
| Approve/reject consumer's subscriptions | x (my team assets)      |                         |                         |                    |                         |
| Delete my subscriptions                 | x (my team)             |                         | x (my team)             | x (my team)        |                         |
| **Marketplace**                         |                         |                         |                         |                    |                         |
| View products                           | x (my team)             | x (my team)             | x (my team)             | x (my team)        |                         |
| Subscribe                               | x (free plan only)      | x (free plan only)      | x (free plan only)      | x (free plan only) |                         |
| Manage subscriptions                    | x (my team)             | x (my team)             | x (my team)             | x (my team)        |                         |
| Approve/reject subscriptions            | x (my team)             | x (my team)             |                         |                    |                         |
| View consumer access request            | x (my team)             | x (my team)             | x (my team)             | x (my team)        |                         |
| View application subscriptions          | x (my team)             | x (my team)             | x (my team)             | x (my team)        |                         |
| Delete consumer access request          | x (my team)             | x (my team)             | x (my team)             | x (my team)        |                         |
| View my subscription                    | x (my team)             | x (my team)             | x (my team)             | x (my team)        |                         |
| Create application                      | x (my team)             | x (my team)             | x (my team)             | x (my team)        |                         |
| View application                        | x (my team)             | x (my team)             | x (my team)             | x (my team)        |                         |
| Delete application                      | x (my team)             | x (my team)             | x (my application)      | x (my application) |                         |
| Update application                      | x (my team)             | x (my team)             | x (my application)      | x (my application) |                         |
| **Environments**                        |                         |                         |                         |                    |                         |
| Create environments                     |                         |                         |                         |                    |                         |
| View environments                       |                         |                         |                         |                    |                         |
| Delete environments                     |                         |                         |                         |                    |                         |
| Update environments                     |                         |                         |                         |                    |                         |
| **Services**                            |                         |                         |                         |                    |                         |
| Create a service                        |                         |                         | x (my team              |                    |                         |
| View a service                          |                         |                         | x (my team)             |                    |                         |
| Delete a service                        |                         |                         | x (my team)             |                    |                         |
| Update a service                        |                         |                         | x (my team)             |                    |                         |
| **Assets**                              |                         |                         |                         |                    |                         |
| Create an asset                         |                         |                         | x (my team)             |                    |                         |
| View an asset                           |                         |                         | x (my team)             |                    |                         |
| Delete an asset                         |                         |                         | x (my team)             |                    |                         |
| Update an asset                         |                         |                         | x (my team)             |                    |                         |
| **Products**                            |                         |                         |                         |                    |                         |
| Create a product                        | x (my team)             |                         |                         |                    |                         |
| View a product                          | x (my team)             |                         |                         |                    |                         |
| Delete a product                        | x (my team)             |                         |                         |                    |                         |
| Update a product                        | x (my team)             |                         |                         |                    |                         |
| Set product visibility                  | x (my team)             |                         |                         |                    |                         |
| Publish a product to the Marketplace    | x (my team)             |                         |                         |                    |                         |
| **Categories**                          | *Team level/Enterprise* |                         | *Team level/Enterprise* | *Enterprise level* | *Team level/Enterprise* |
| Create a category                       |                         |                         |                         |                    |                         |
| View a category                         |                         |                         |                         |                    |                         |
| Delete a category                       |                         |                         |                         |                    |                         |
| Update a category                       |                         |                         |                         |                    |                         |
| Assign to a category                    |                         |                         |                         |                    |                         |
| **Business Insights**                   |                         |                         |                         |                    |                         |
| View transactions for my subscriptions  | x (my team)             |                         | x (my team)             | x (my team)        |                         |
| View transactions for my assets         | x (my team)             |                         | x (my team)             | x (my team)        |                         |
| **Teams & Members (Platform)**          |                         |                         |                         |                    |                         |
| Create a team                           |                         |                         |                         |                    |                         |
| View teams                              | x (my team)             |                         | x (my team)             |                    | x (my team)             |
| Update team                             |                         |                         |                         |                    | x (my team)             |
| Delete team                             |                         |                         |                         |                    |                         |