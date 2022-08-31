---
title: Managing applications
linkTitle: Managing applications
weight: 30
date: 2021-08-12
---

To manage your registered apps, select one from the table on the **Apps** page.

## App Overview and service keys

When you select an application from the **Apps** link, its **Overview** view opens. The **Overview** view displays basic information about the application, including its name, description, and application GUID, category, creator, admin, and assigned teams. It also includes [key metrics](/docs/management_guide/managing_applications/viewing_metrics/) collected by the Analytics service.

## Apps left navigation

The left navigation includes the following views:

![Apps left navigation](/Images/titanium_apps_left_menu.png)

![Apps overview](/Images/app_overview_latest.png)

The **App Info** view includes Category, Creator, and Admin information. Additionally, you can click the **Actions** (**...**) menu in the upper-right of the screen and select **Edit** to edit the Name, Category, and Description of your application for iOS and Android applications. Once you have completed your edits, click the **Save** button to save your edits. To return the **Overview** view without saving your edits, click the **Cancel** button.

![Edit iOS and Android apps](/Images/edit_app.png)

You can also permanently delete the selected application by clicking the **Action Menu** icon and selecting **Delete**. To confirm the deletion of the selected application, type the name of the application you would like to delete permanently, and then select, **I understand that this a permanent and irreversible action. Continue**.

## Crashes view

The **Crashes** view displays the total number of crashes of your application for the selected time frame and the crash rate for your application. The crash for your application is calculated by dividing the total number of crashes by the total number of sessions. Additionally, error messages, time of the first occurrence, time of the last occurrence, total occurrences, and triage status are displayed for each operating system (for example, Windows, iOS, and Android). The displayed crash analytics can be filtered by the environment, crash type, and crash status. To export the crash analytics information, click the **Actions** (**...**) menu, and select either **Chart** or **Table**.

![Crashes page](/Images/crashes.png)

To upload symbol files:

1. Click the **Actions** (**...**) menu icon and select **Upload Symbols**.
2. Select the **Platform**.
3. Select the **Version**.
4. Choose the symbol file to upload.
5. Click **Upload**.

To filter and search crashes by username:

1. Enter the username in the **Search by username** field.
2. Click **Search.**

## Viewing real-time and aggregated analytics

The **Analytics** view displays real-time analytics, such as the number of active users, the number of installs, the number of sessions, and the number of events.

For more information, see [Viewing Analytics](/docs/management_guide/managing_applications/viewing_analytics/).
