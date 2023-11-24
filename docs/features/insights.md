---
sidebar_position: 7
title: Insights
description: Testing metrics are collated inside the Insights tab.
---

# Insights

When you execute tests from the Testing application or via the CI runner, metrics are collected for reporting purposes. We surface these metrics via the **Insights** tab from within a [Test Scenario](building-tests/test-scenarios).

**Collected metrics:**

| Metric                   | Dimensions                                  | Description                                                                                                                 |
| ------------------------ | ------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------- |
| Passed/Failed Executions | <ul><li>Total (%)</li><li>By Date</li></ul> | Details the number of passed/failed executions.                                                                             |
| Scenario Duration        | <ul><li>By Date</li></ul>                   | Details the end-to-end duration for the test execution.                                                                     |
| Task Duration            | <ul><li>By Task</li><li>By Date</li></ul>   | Details the duration of each [Task](building-tests/tasks) that makes up the [Test Scenario](building-tests/test-scenarios). |

:::note
When there are more than 1 executions for an interval, the **average** time across all executions will be shown for the session and task duration.
:::

## View Insights

From within the editor view of a Test Scenario, navigate to the **Insights tab.**

**Hover** over the series to see more granular detail. 

![](<../assets/image (75).png>)
