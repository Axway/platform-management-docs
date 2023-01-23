---
title: Overview
linkTitle: Overview
weight: 5
date: 2021-08-12
---

The Amplify Platform Overview left navigation comprises the following views:

{{% alert title="Note" color="primary" %}}The available menus on the Amplify Platform Overview may vary based on your role and your organization's subscriptions.{{% /alert %}}

![Amplify Platform Overview left navigation](/Images/dashboard_left_menu.png)

* **Overview** - displays  key metric information relevant to a product line to which your organization is subscribed. All users will see the Overview link.
* **Business Insights** - navigates you to [Business Insights](https://docs.axway.com/bundle/amplify-central/page/docs/get_actionable_insights/business_insights/index.html). Users with the Central Admin and Developer roles will see the Business Insights link.
* **Search Audit** - navigates you to the Search Audit. Users with the Auditor role will see the Search Audit link.
* **Apps** - displays the list of applications for your organization and where you can [manage your applications](/docs/management_guide/managing_applications/). Organizations with registered apps will see this link.
* **Custom Queries** - if configured, displays custom query summary information and enables the creation of custom analytics queries.

## Overview

The **Overview** displays key metric information relevant to the product line to which your organization is subscribed. For additional information on the key metrics, refer to [Viewing Metrics](/docs/management_guide/managing_applications/viewing_metrics/).

![Overview page](/Images/dasbhoard_home_overview_tab.png)

## Business Insights

**Business Insights** redirects you to [Business Insights](https://docs.axway.com/bundle/amplify-central/page/docs/get_actionable_insights/business_insights/index.html).

## Apps

**Apps** displays the list of applications for the selected organization. Select the **Show only my apps** checkbox to limit the displayed list of applications to your projects or applications. The list of apps can be filtered by app type. You can also search the list of apps by app name, ID, or creator and select and pin apps from the list of apps.

To manage an application, select one from the list.

If you haven't created any applications yet, you will be directed to the *You don't have any apps yet!* page.

Once you have apps created, you can add new apps from the apps list page. Click the **Actions** ( **...** ) menu in the upper right, and then select **Register App for Services**.

### App list filtering

The apps list can be filtered by:

* APIs/Microservices
* Website/Web Apps
* Other

To filter the apps list by a selected app type:

1. Select **All Apps**.
2. Select an app type from the *All Apps* down-down menu.

The displayed apps list will be updated and will only display the apps matching the selected application type.

### Apps list sorting

The Name, Type, and Created columns in the apps list can be sorted either in ascending and descending order. Note that pinned apps will always appear at the top of the apps list in the sorted order.

### Apps list paging

The number of displayed applications per page can be selected using the *per page* drop-down menu.

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
