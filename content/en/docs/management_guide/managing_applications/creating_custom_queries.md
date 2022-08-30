---
title: Creating custom queries
linkTitle: Creating custom queries
weight: 60
date: 2021-08-12
---

By default, analytics are provided for Average Session Length, Installs, Events, Push Notifications, Sessions, and Unique Devices. The Custom Queries feature enables you to create custom queries based on your application-specific metrics and analytical needs or expand upon the provided default analytics to meet your specific analytics needs.

## Queries overview

To access the _Queries Overview_ view, select the **Custom Queries** link on the Overview left menu.

![Queries overview](/Images/custom_queries_overview.png)

If you have not created any custom queries, selecting the **Custom Queries** link will transfer you to the _Queries_ view. The _Queries_ view enables creating, previewing, editing, saving, and deleting custom analytics queries. You can also filter custom queries. To access the _Queries_ view from the _Queries Overview_ view, click the **Query** button or click on a custom query tile. To navigate from the _Queries_ view to the _Queries Overview_ view, select **All Queries** from the Saved Queries drop-down menu.

![Queries page](/Images/custom_queries.png)

## Creating queries without filtering

To create a custom query without filtering:

1. Enter a query name in the **Name** field.
2. Select a line chart, bar chart, or events stream for the **Display**.
3. Select a **Method**. The Method drop-down menu selections are:
    * Count
    * Cardinality
    * Average
    * Sum
    * Min
    * Max
    * Find - If selected, select the fields to include in the events and the limit, offet, and sort options.
4. Select a **Field**. The Field drop-down menu selections are:
    * Custom - If selected, enter the custom field information.
    * Event
    * Application
    * Platform
    * Platform Version
    * Environment
    * Country
    * Session
    * Session Length
5. Select a **Grouping**. The Grouping drop-down menu selections are:
    * Custom - If selected, enter the custom grouping information.
    * Event
    * Application
    * Platform
    * Platform Version
    * Environment
    * Country
    * Session
    * Session Length - If selected, enter an **Interval**. The entered interval is the range to use when grouping numeric values.
6. Select a **Date Range**. The Date Range drop-down menu selections are:
    * Last 3 Months
    * Last 30 Days
    * Last 7 Days
    * Last 24 Hours
    * Last 60 Minutes
    * Custom - If selected, select a custom date range. **Queries with a specific date ranges cannot be saved.**
7. (Optional) Click **Preview** to preview your custom query. The Custom Query section will be updated to display your custom query analytics preview.
8. Click **Save** to save your custom query. Your custom query will be saved, the Saved Queries drop-down menu will be updated to include your saved custom query, the Custom Query section will be updated to display your custom query analytics, and your custom query will be available on the _Queries Overview_ screen.

## Creating queries with filtering

To create a custom query with filtering:

1. Enter a query name in the **Name** field.
2. Select a line chart, bar chart, or events stream for the **Display**.
3. Select a **Method**. The Method drop-down menu selections are:
    * Count
    * Cardinality
    * Average
    * Sum
    * Min
    * Max
    * Find - If selected, select the fields to include in the events and the limit, offet, and sort options.
4. Select a **Field**. The Field drop-down menu selections are:
    * Custom - If selected, enter the custom field information.
    * Event
    * Application
    * Platform
    * Platform Version
    * Environment
    * Country
    * Session
    * Session Length
5. Select a **Grouping**. The Grouping drop-down menu selections are:
    * Custom - If selected, enter the custom grouping information.
    * Event
    * Application
    * Platform
    * Platform Version
    * Environment
    * Country
    * Session
    * Session Length - If selected, enter an **Interval**. The entered interval specifies the range to use when grouping numeric values.
6. Select a **Date Range**. The Date Range drop-down menu selections are:
    * Last 3 Months
    * Last 30 Days
    * Last 7 Days
    * Last 24 Hours
    * Last 60 Minutes
    * Custom - If selected, select a custom date range. **Queries with a specific date ranges cannot be saved.**
7. (Optional) Click **Preview** to preview your custom query. The Custom Query section will be updated to display your custom query analytics preview.
8. Select **Basic**.
9. For Match, select either **All** or **Any**.
10. Click the **Plus** icon to add a filter.
11. Select the type of filter. The type of filter drop-down menu selections are:
    * Custom - If selected, enter the custom field information.
    * Event
    * Application
    * Platform
    * Platform Version
    * Environment
    * Country
    * Session
    * Session Length
12. Select a filter operand. The filter operand selections are:
    * Equals
    * Is not
    * Exists
    * Is one of
    * Starts with
    * Doesn't start with
    * Ends with
    * Doesn't end with
    * Is greater than
    * Is greater than or equal to
    * Is less than
    * Is less than or equal to
13. Complete the operand field or make a selection from the drop-down menu. The field selections are based on the selected filter type. To fetch the available field selections over the selected time range, click the **Magnify** icon. Optionally, you can select **Advanced** and enter the JSON coded filter.
14. Click **Save** to save to save your custom query. Your custom query will be saved, the Saved Queries drop-down menu will be updated to include your saved custom query, the Custom Query section will be updated to display your custom query analytics, and your custom query will be available on the _Queries Overview_ screen.

## Previewing queries

To preview a custom query and not save it, click **Submit**. The Custom Query section will be updated to display your custom query analytics.

## Saving queries

To save a custom query, click **Save**. Your custom query will be saved, the Saved Queries drop-down menu will be updated to include your saved custom query, the Custom Query section will be updated to display your custom query analytics, and your custom query will be available on the _Queries Overview_ view.

## Clearing queries

To clear the custom query selections and fields, click **Clear**.

## Editing queries

To edit a custom query:

1. Select the custom query to edit from the Saved Queries drop-down menu or from the _Queries Overview_ view.
    ![Edit a query](/Images/custom_queries_edit.png)
2. Edit the **Name**, **Display**, **Method**, **Field**, **Grouping**, and **Date Range** selections as needed.
3. (Optional) Click **Preview** to preview your custom query changes. The Custom Query section will be updated to display your custom query analytics changes.
4. Click the **Actions** (**...**) menu to edit the chart display. You can also refresh the data and download chart data.
5. Edit the filtering as needed.
6. Click **Save** to save your custom query changes. The Custom Query section will be updated to display your custom query analytics changes.

## Deleting queries

To delete a custom query:

1. Select the custom query to delete from the Saved Queries drop-down menu or from the _Queries Overview_ view.
2. Click **Delete**.
3. Enter the name of the query to delete in the _Delete Confirmation_ view.
4. To confirm the query deletion, click **I understand that this is a permanent and irreversible action. Continue**.

## Filtering queries

You can filter queries using either basic filtering or advanced filtering.

### Basic Filtering

To configure basic filtering:

1. Select **Basic**.
2. For Match, select either **All** or **Any**.
3. Click the **Plus** icon to add a filter.
4. Select the type of filter. The type of filter drop-down menu selections are:
    * Custom - If selected, enter the custom field information.
    * Event
    * Application
    * Platform
    * Platform Version
    * Environment
    * Country
    * Session
    * Session Length
5. Select a filter operand. The filter operand selections are:
    * Equals
    * Is not
    * Exists
    * Is one of
    * Starts with
    * Doesn't start with
    * Ends with
    * Doesn't end with
    * Is greater than
    * Is greater than or equal to
    * Is less than
    * Is less than or equal to
6. Complete the operand field or make a selection from the drop-down menu. The selections are based on the selected filter type. To fetch the available field selections over the selected time range, click the **Magnify** icon.
7. (Optional) To add additional filters, click the **Plus** icon.
8. To save the configured filtering as part of a custom query, click **Save**.

### Advanced filtering

To configure advanced filtering:

1. Select **Advanced**.
2. Enter a JSON coded filter in the code field. Note that the code field will be highlighted unless a valid filter code is entered. For example, to create a filter to match application installation in the production environment, enter the following code in the field:

    ```
    {
        "$match": {
            "event": "app.install",
            "distribution.environment": "production"
        }
    }
    ```

3. To save the configured filtering as part of a custom query, click **Save**.

### Delete filters

To delete a filter, select the **Delete** icon associated with the filter to delete.

## Custom data query example

If a `featureEvent` is specified:

```javascript
function doClick(e) {
  Ti.Analytics.featureEvent('testFeature',
{
    testString: 'hello world'
  }
);
  alert($.label.text);
}
$.index.open();
```

The query to filter on the data `testString` that is attached to the `featureEvent` would be a `data.testString` equal to hello world.
