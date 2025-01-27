---
title: Organization roles and features
linkTitle: Organization roles and features
weight: 20
date: 2021-08-12
---
This section is about organization user roles and features. Users can be assigned different roles that grant them the rights to the Platform associated with their assigned roles and capabilities. A user always needs to be assigned one platform role and can be assigned zero, one, or more of the other roles.

Amplify provides several types of roles: 

* Organization roles: These roles provides access to core functionality of Amplify Plaform, organization and user management.
* Team Roles: Roles that are used to control the access level of users inside a team.

## Organization roles and capabilities

The following table shows the available roles and capabilities they grant access to.

| Role                      | Short Description                        | Platform | Central | Marketplace |  Teams       | Assignable in Provider Organization | Assignable in Consumer Org | Team roles can be used with |
| ------------------------- | -----------------------------------------| -------- | ------- | ----------- | ------------ | ----------------------------------- |  -------------------------- |--------------------------- |
| Administrator             | Use for platform administrative tasks, such as managing users and teams, and configuration of platform settings| X        |         |             | X            | Yes  |  Yes   | Provider team roles  |
| Developer                 | Use for development and integration projects                                                                   | X        | X       | X           | X (my teams) | Yes  |  No    | Any                  |
| Consumer                  | Use for browsing Marketplace(s) and consumption of published products                                          |          |         | X           |              | Yes  |  Yes   | Consumer, Subscriber |
| Auditor **Coming soon**   | USe to access the plaform capabilities with read-only permissions, without the ability to modify anything      | X        | X       | X           | X 			     | Yes  |  No    | None                 |  
| **Platform Roles**        |                                                                                                                |          |         |             |              |      |        |                      |
| Usage Reporter            | Use for registering usage environments and reporting usage                                                     | X        |         |             |              | Yes  |  No    | N/A                  |
| **Central Roles**         |                                                                                                                |          |         |             |              |      |        |                      |
| Central Admin             | Use for all-encompassing access to the management plane (i.e Service Registry, Assets Catalog etc              |          | X       | X           |              | Yes  |  No    | None                 | 

## Team roles

Users can have one or more roles in each team they belong to.

| Team Role | Short Description | Provider | Consumer |
| --- | --- | --- | --- |
| Team Manager | Use this role to manage the members of the team and their role assignments | x | x |
| Consumer | Enables a user to view and consume Marketplace products under a free plan, as well as manage their own reviews. |   | x |
| Developer | Gives users full read/write permissions to API Services and Assets | x |   |
| Marketplace Manager | Use this role to manage Marketplace settings, appearance, and content | x |   |
| Catalog Manager | Use this role to manage products and create rate plans | x |   |
| Subscriber | Enables users to view and consume Marketplace products under free and paid plans, as well as manage their own reviews |   | x |
| Subscription Approver** | Use this role to review and approve subscription requests | x |   |
| Insights Viewer **Coming soon** | Use this role to access Business Insights dashboards| x |   |
| Environment Admin **Coming soon** | Use this role to create and manage environments | x |   |
| API Access Manager **Coming soon** | Use this role to approve and manage application registration requests and consumer credentials | x |   |

> [!NOTE]
> If a *Provider* user is part of a single team with the `x-private` tag, then they will not have access to the managagement plane to execute their tasks. Provider users should not use the `x-private` tag in their provider teams, as it meant to be used only for *Consumer* users.

## Provider Team roles and capabilities
The following table shows the available provider team roles and capabilities. The Central Admin role has access to all team capabilities. The Auditor role (coming soon) has read only access to all capabilities. 

| Role Type / Scope                 | Catalog Manager   | Developer     |Team Manager|Subscription Approver|Marketplace Manager|Insights Viewer <br/>**Coming soon**|Environment Manager<br/>**Coming soon**|API Access Manager|
|-----------------------------------|-------------------|---------------|------------|---------------------|-------------------|------------------------------------|---------------------------------------|------------------|
| **Team and Members**              |                   |               |            |                     |                   |                                    |                                       |                  |
| Create a team                     |                   |               |            |                     |                   |                                    |                                       |                  |
| Manage members and roles          |                   |               |x (my team) |                     |                   |                                    |                                       |                  |
| View teams                        |                   |               |x (my team) |                     |                   |                                    |                                       |                  |
| Delete team                       |                   |               |            |                     |                   |                                    |                                       |                  |
| **Environments**                  |                   |               |            |                     |                   |                                    |                                       |                  |
| Create environment                |                   |               |            |                     |                   |                                    |x (my team)                            |                  |
| View environment                  | x (my team)       | x (my team)   |            |                     |                   | x (my team)                        |x (my team)                            |x (my team)       |
| Edit environment                  |                   |               |            |                     |                   |                                    |x (my team)                            |                  |
| Delete environment                |                   |               |            |                     |                   |                                    |x (my team)                            |                  |
| **Services**                      |                   |               |            |                     |                   |                                    |                                       |                  |
| Create Service                    | x (my team)       | x (my team)   |            |                     |                   |                                    |x (my team)                            |                  |
| View Service                      | x (my team)       | x (my team)   |            |                     |                   | x (my team)                        |x (my team)                            |x (my team)       |
| Edit Service                      | x (my team)       | x (my team)   |            |                     |                   |                                    |x (my team)                            |                  |
| Delete Service                    | x (my team)       | x (my team)   |            |                     |                   |                                    |x (my team)                            |                  |
| **Stages**                        |                   |               |            |                     |                   |                                    |                                       |                  |
| Create Stages                     |                   |               |            |                     |                   |                                    |                                       |                  |
| View Stages                       | x (my team)       | x (my team)   |            |                     |                   |                                    |  x                                    |x (my team)       |
| Edit Stages                       |                   |               |            |                     |                   |                                    |                                       |                  |
| Delete Stages                     |                   |               |            |                     |                   |                                    |                                       |                  |
| **Agents**                        |                   |               |            |                     |                   |                                    |                                       |                  |
| View agents status                |                   |               |            |                     |                   |                                    |x                                      |                  |
| **Compliance Profiles**           |                   |               |            |                     |                   |                                    |                                       |                  |
| Create Compliance Profile         |                   |               |            |                     |                   |                                    |                                       |                  |
| View Compliance Profile           |                   |               |            |                     |                   |                                    |x                                      |                  |
| Edit Compliance Profile           |                   |               |            |                     |                   |                                    |                                       |                  |
| Delete Compliance Profile         |                   |               |            |                     |                   |                                    |                                       |                  |
| **Assets**                        |                   |               |            |                     |                   |                                    |                                       |                  |
| Create asset                      | x (my team)       | x (my team)   |            |                     |                   |                                    |                                       |                  |
| View asset                        | x (my team)       | x (my team)   |            |                     |                   | x (my team)                        |                                       | x (my team)      |
| Update asset                      | x (my team)       | x (my team)   |            |                     |                   |                                    |                                       |                  |
| Delete asset                      | x (my team)       | x (my team)   |            |                     |                   |                                    |                                       |                  |
| Share asset                       | x (my team)       | x (my team)   |            |                     |                   |                                    |                                       |                  |
| Change owner                      | x (my team)       |               |            |                     |                   |                                    |                                       |                  |
| **Products**                      |                   |               |            |                     |                   |                                    |                                       |                  |
| Create product                    | x (my team)       |               |            |                     |                   |                                    |                                       |                  |
| View products                     | x (my team)       |               |            | x (my team)         |                   | x (my team)                        |                                       |                  |
| Edit product                      | x (my team)       |               |            |                     |                   |                                    |                                       |                  |
| Delete product                    | x (my team)       |               |            |                     |                   |                                    |                                       |                  |
| Share product                     | x (my team)       |               |            |                     |                   |                                    |                                       |                  |
| Change owner                      | x (my team)       |               |            |                     |                   |                                    |                                       |                  |
| **Product Plans**                 |                   |               |            |                     |                   |                                    |                                       |                  |  
| Create plan                       | x (my team)       |               |            |                     |                   |                                    |                                       |                  |
| View plans                        | x (my team)       |               |            |  x (owned products) |                   | x (my team)                        |                                       |                  |
| Edit plan                         | x (my team)       |               |            |                     |                   |                                    |                                       |                  |
| Delete plan                       | x (my team)       |               |            |                     |                   |                                    |                                       |                  |
| **Categories**                    |                   |               |            |                     |                   |                                    |                                       |                  |
| Create category                   | x (my team)       |               |            |                     |                   |                                    |                                       |                  |
| View categories                   | x (my team)       |               |            |                     |                   |                                    |                                       |                  |
| Edit category                     | x (my team)       |               |            |                     |                   |                                    |                                       |                  |
| Delete category                   | x (my team)       |               |            |                     |                   |                                    |                                       |                  |
| **Subscription Approvals**        |                   |               |            |                     |                   |                                    |                                       |                  |
| View subscriptions                | x (owned products)|               |            | x (owned products)  |                   |                                    |                                       |                  |
| Approve / Decline subscriptions   |                   |               |            | x (owned products)  |                   |                                    |                                       |                  |
| Revoke & Delete subscriptions     |                   |               |            | x (owned products)  |                   |                                    |                                       |                  |
| **Application Registration Approvals**|               |               |            |                     |                   |                                    |                                       |                  |
| View application registration     | x (owned APIs)    |               |            |                     |                   |                                    |                                       | x (owned APIs)   |
| Approve application registration  |                   |               |            |                     |                   |                                    |                                       | x (owned APIs)   |
| Decline application registration  |                   |               |            |                     |                   |                                    |                                       | x (owned APIs)   |
| Delete application registration   |                   |               |            |                     |                   |                                    |                                       | x (owned APIs)   |
| **Credential Approvals**          |                   |               |            |                     |                   |                                    |                                       |                  |
| View credentials                  | x (owned APIs)    |               |            |                     |                   |                                    |                                       | x (owned APIs)   |
| Suspend credential                |                   |               |            |                     |                   |                                    |                                       | x (owned APIs)   |
| Enable credential                 |                   |               |            |                     |                   |                                    |                                       | x (owned APIs)   |
| Renew credential                  |                   |               |            |                     |                   |                                    |                                       | x (owned APIs)   |
| **Document Library**              |                   |               |            |                     |                   |                                    |                                       |                  |
| Create document                   | x (my team)       | x (my team)   |            |                     |                   |                                    |                                       |                  |
| View documents                    | x (my team)       | x (my team)   |            |                     |                   |                                    |                                       |                  |
| Edit document                     | x (my team)       | x (my team)   |            |                     |                   |                                    |                                       |                  |
| Delete document                   | x (my team)       |               |            |                     |                   |                                    |                                       |                  |
| Share document                    | x (my team)       |               |            |                     |                   |                                    |                                       |                  |
| **Business Insights**             |                   |               |            |                     |                   |                                    |                                       |                  |
| API Health                        |                   |               |            |                     |                   | x (my team)                        |                                       |                  |
| API Traffic                       |                   |               |            |                     |                   | x (my team)                        |                                       |                  |
| Provider Engagement               |                   |               |            |                     |                   | x (my team)                        |                                       |                  |
| Consumer Engagement               |                   |               |            |                     |                   | x (my team)                        |                                       |                  |
| Applications Dashboard            |                   |               |            |                     |                   | x (my team)                        |                                       |                  |
| Subscriptions Dashboard           |                   |               |            |                     |                   | x (my team)                        |                                       |                  |
| Leaderboard                       |                   |               |            |                     |                   | x (my team)                        |                                       |                  |
| Overview                          |                   |               |            |                     |                   | x (my team)                        |                                       |                  |
| **Marketplace**                   |                   |               |            |                     |                   |                                    |                                       |                  |
| Browse Products                   | x (my team)       | x (my team)   |            |                     |                   |                                    |                                       |                  |
| Subscribe                         | x (free plans)    | x (free plans)|            |                     |                   |                                    |                                       |                  |
| Manage subscriptions              | x (my team)       | x (my team)   |            |                     |                   |                                    |                                       |                  |
| Create applications               | x (my team)       | x (my team)   |            |                     |                   |                                    |                                       |                  |
| Manage applications               | x (my team)       | x (my team)   |            |                     |                   |                                    |                                       |                  |
| Create application registration   | x (my team)       | x (my team)   |            |                     |                   |                                    |                                       |                  |
| Manage application registration   | x (my team)       | x (my team)   |            |                     |                   |                                    |                                       |                  |
| Create credentials                | x (my team)       | x (my team)   |            |                     |                   |                                    |                                       |                  |
| Manage credentials                | x (my team)       | x (my team)   |            |                     |                   |                                    |                                       |                  |
| **Marketplace Configuration & Branding** |            |               |            |                     |                   |                                    |                                       |                  |
| Create Marketplace                   |                |               |            |                     |                   |                                    |                                       |                  |
| View Marketplace                     | x (publication preferences)    | x (consumption preferences)      | x (publication preferences) | x (admin preferences)    |                                       |                  |
| Settings & appearance                |                |               |            |                     |                   | x                                  |                                       |                  |
| **Consumer Insights**                |                |               |            |                     |                   |                                    |                                       |                  |
| API Health                           | x (my team)    | x (my team)   |            |                     |                   |                                    |                                       |                  |
| API Traffic                          | x (my team)    | x (my team)   |            |                     |                   |                                    |                                       |                  | 
| Applications Dashboard               | x (my team)    | x (my team)   |            |                     |                   |                                    |                                       |                  |
| Subscription Dashboard               | x (my team)    | x (my team)   |            |                     |                   |                                    |                                       |                  |

## Consumer Team roles and capabilities
The following table shows the available consumer roles and capabilities. The Central Admin role has access to all team capabilities. 

| Role Type / Scope                 | Consumer                     | Subscriber                    |
|-----------------------------------|------------------------------|-------------------------------|
| **Marketplace**                   |                              |                               |
| View Marketplace                  | x (consumption preferences)  | x (consumption preferences)   |
| Browse Products                   | x (visibility settings apply)| x (visibility settings apply) |
| Subscribe                         | x (free plans)               | x (free & paid plans)         |
| Manage subscriptions              | x (my team)                  | x (my team)                   |
| Create applications               | x (my team)                  | x (my team)                   |
| Manage applications               | x (my team)                  | x (my team)                   |
| Create application registration   | x (my team)                  | x (my team)                   |
| Manage application registration   | x (my team)                  | x (my team)                   |
| Create credentials                | x (my team)                  | x (my team)                   |
| Manage credentials                | x (my team)                  | x (my team)                   |
| **Consumer Insights**             |                              |                               |
| API Health                        | x (my team)                  | x (my team)                   |
| API Traffic                       | x (my team)                  | x (my team)                   |
| Applications Dashboard            | x (my team)                  | x (my team)                   |
| Subscription Dashboard            | x (my team)                  | x (my team)                   |

