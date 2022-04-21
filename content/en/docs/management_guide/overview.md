---
title: Overview
linkTitle: Overview
weight: 5
date: 2021-08-12
---

The Amplify Platform Overview left navigation comprises the following menu items:

{{% alert title="Note" color="primary" %}}The available menus on the Amplify Platform Overview may vary based on your role and your organization's subscriptions.{{% /alert %}}

![Amplify Platform Overview left navigation](/Images/dashboard_left_menu.png)

* **Overview** - displays  key metric information relevant to a product line to which your organization is subscribed. All users will see the Overview link.
* **Business Insights** - navigates you to [Business Insights](https://docs.axway.com/bundle/amplify-central/page/docs/get_actionable_insights/index.html). Users with the Central Admin and Developer roles will see the Business Insights link.
* **Search Audit** - navigates you to the Search Audit. Users with the Auditor role will see the Search Audit link.
* **Apps** - displays the list of applications for your organization and where you can [manage your applications](/docs/management_guide/managing_applications/). Organizations with Application Development, Cloud Capacity, or Runtime Services subscriptions will see the Apps link.
* **Custom Queries** - if configured, displays custom query summary information and enables the creation of custom analytics queries.

## Overview

The **Overview** displays key metric information relevant to the product line to which your organization is subscribed. For additional information on the key metrics, refer to [Viewing Metrics](/docs/management_guide/managing_applications/viewing_metrics/).

![Overview page](/Images/dasbhoard_home_overview_tab.png)

## Business Insights

**Business Insights** redirects you to [Business Insights](https://docs.axway.com/bundle/amplify-central/page/docs/get_actionable_insights/index.html).

## Search Audit

<!-- TODO: link to Search Audit page in Flow Manager docs -->
**Search Audit** redirects you to Search Audit.

## Apps

**Apps** displays the list of applications for the selected organization. Select the **Show only my apps** checkbox to limit the displayed list of applications to only display your projects or applications. The list of apps can also be filtered by app type. You can also search the list of apps by app name, ID, or creator and select and pin apps from the list of apps.

{{% alert title="Note" color="primary" %}}Mobile Backend Services and Runtime Services are deprecated and will be discontinued effective September 1, 2022.{{% /alert %}}

![Apps page](/Images/dashboard_apps_home_tab.png)

To manage an application, select the application to manage from the list of applications.

If you haven't created any applications yet, you will be directed to the _You don't have any apps yet!_ page. Don't worry. It's easy to get started creating apps using the Platform. It should take you only a few minutes to create an app. Once you do, your Overview will have data here. To get started creating applications, click one of the following options:

* **Get the latest tools -** You will be forwarded to the _Get started with {{% variables/apibuilder_prod_name %}}_ page where you can select to get started building apps with either [Axway Appcelerator Studio](https://docs.axway.com/bundle/Appcelerator_Studio_allOS_en/page/axway_appcelerator_studio.html) or [Appcelerator CLI](https://docs.axway.com/bundle/Appcelerator_CLI_allOS_en/page/appcelerator_cli.html).
* **Register App for Services** \- You will be forwarded to the _Register App for Services_ page.
* **Create MBS Datasource** \- If you do not have a subscription, you will be forwarded to the _Billing_ page where you can upgrade your plan to access locked items. Refer to [Managing Billing](/docs/management_guide/managing_billing/). If you have a subscription, you will be forwarded to the _Create Mobile Backend Services Datasource_ page.

![You don't have any apps yet page](/Images/dashboard_home_no_apps.png)

Once you have apps created, you can add new apps from the apps list page. Click the **Actions** ( **...** ) menu in the upper right, and then select **Register App for Services** or **Create MBS Datasource**.

### App list filtering

The apps list can be filtered by:

* All Apps
* Titanium SDK Apps
* APS SDK Apps
* Runtime Services
* Mobile Backend Services
* APIs/Microservices
* Website/Web Apps
* Other

To filter the apps list by a selected app type:

1. Select **All Apps**.
2. Select an app type from the _All Apps_ down-down menu.

The displayed apps list will be updated and will only display the apps matching the selected application type.

### Apps list sorting

The Name, Type, and Created columns in the apps list can be sorted either in ascending and descending order. Note that pinned apps will always appear at the top of the apps list in the sorted order.

### Apps list paging

The number of displayed applications per page can be selected using the _per page_ drop-down menu.

![Apps list paging](/Images/application_list_paging.png)

The number of applications displayed per page can be set to:

* 10 per page
* 25 per page (default)
* 50 per page
* 100 per page

### Select favorite apps

To pin an app or add an app as a favorite:

1. Click the **Actions** (**...**) menu associated with the app to pin.
2. Select **pin**.

The app will be updated to indicate it is pinned and it will be displayed at the beginning of the apps list.

To unpin an app or remove an app as a favorite:

1. Click the **Actions** (**...**) menu associated with the app to unpin.
2. Select **unpin**.

The app will be unpinned and will display alphabetically in the apps list.

### Delete apps

You must have the administrator role for the organization or team to see the **Delete** option and to delete apps.

To delete a single app:

1. Click the **Actions (...)** menu associated with the app to delete.
2. Select **Delete**.
3. Enter the name of application or datasource to delete.
4. To confirm the deletion, click **I understand that this a permanent and irreversible action. Continue**.

To delete multiple apps:

1. Select the apps to delete by using multi-select methods for your Operating System.
2. Click the **Actions (...)** menu located at the upper right of the apps list page.
3. Enter your Amplify Platform password.
4. To confirm the deletion, click **I understand that this a permanent and irreversible action. Continue**.

## Custom queries

**Custom Queries** displays custom query summary information and enables the creation of custom analytics queries. For information on creating custom queries, refer to [Creating Custom Queries](/docs/management_guide/managing_applications/creating_custom_queries/).

![Custom queries page](/Images/dashboard_home_custom_queries_tab.png)
