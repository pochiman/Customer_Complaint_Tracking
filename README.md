# Customer Complaint Tracking

## The Situation
You've just been hired as a Business Intelligence (BI) Developer for the Compliance department at Bank of America.

## The Assignment
Your team receives consumer complaints from the Consumer Financial Protection Bureau (CFPB) and is expected to handle them appropriately and swiftly.
You've been asked to create a report to track open and closed complaints for a specific period and visualize the weekly trend to avoid overdue complaints.

## The Objectives
1. Create calculated columns
2. Calculate top-level KPIs
3. Visualize the weekly trend

## The Data Set

#### Financial Consumer Complaints
Consumer complaints on financial products & services for Bank of America from 2017 to 2023, including the dates the complaint was submitted to the CFPB and then sent to the company, the product and issue mentioned in the complaint, and the company's response.

#### Recommended Analysis
1. Do consumer complaints show any seasonal patterns?
2. Which products present the most complaints? What are its most common issues?
3. How are complaints typically resolved?
4. Can you learn anything from the complaints with untimely responses?

#### Objective 1: Calculate top-level KPIs
Your first objective is to calculate top-level KPIs by flagging complaints as "Open" or "Closed" and creating a PivotTable to count the complaints for each status.

* Create a Status column that flags complaints as "Open" or "Closed" based on the values in the Company Response to Consumer column ("In progress" = "Open", others are "Closed").
* Create a Week start column with the date for the corresponding Monday of each Date received (for example, if the “Date received” is Wednesday, Jan 4th, then the “Week start” is Monday, Jan 2nd).
* Extract the Year, Month, and Day of the Week start column.
* Change the formula for the Month column so that it returns the text for the month name in the “mmm” format (1=“Jan”, 2=“Feb”, etc.).

#### Objective 2: Visualize the weekly trend
Your second objective is to create a new PivotTable that shows the "Open" and "Closed" complaints by week, then visualize the trend using a stacked column chart.

* Calculate the count of Complaint ID by Status, including the grand total.
* Place the results, or KPIs, in a single row with “Complaints:” to their left.
* Add a title on top (“Consumer Complaints Tracking”) and apply formatting to the title & KPIs.
* Insert a timeline with the Week start field to filter the results.

#### Objective 3: Finalize the report
Your final objective is to add formatting and polish to the report by modifying the KPIs, chart, and timeline filter.

* Calculate the count of Complaint ID by Status (columns) and Year, Month, and Day (rows) and create a stacked column chart with the results to visualize the weekly trend.
* Connect the chart to the Week start timeline filter.
* Place the “Open” column in the chart at the baseline to improve readability.
* Use the colors in the “Open” and “Closed” KPIs as a legend for the chart and apply additional formatting and alignment to finalize the report.

#### [Project Link]()