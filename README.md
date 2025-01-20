# AtliQ Hardware Business Insights 360

## Project Overview

Retailers, direct sales, and distributors are the three primary channels via which AltiQ Hardware, a rapidly developing business with a global presence, sells PCs and accessories.

After launching a store in America, the company experienced unanticipated losses despite its development. These setbacks were discovered using surveys, basic Excel analysis, and intuition. Given that its rivals have strong analytics teams, AltiQ Hardware understands how critical it is to advance its analytics capabilities in order to succeed in the market.


The business has chosen to use Power BI for analytics in order to outperform rivals and facilitate data-driven decision-making. The goal of this project is to give stakeholders knowledge about supply chain, marketing, sales, and finance so that decisions at all levels are well-informed.

I followed the Codebasics PowerBi Course while working on this project

Here is my report link - (https://app.powerbi.com/view?r=eyJrIjoiMmEyMjcyYmUtNmViMi00NDlhLTlmNzQtODNjMjgzYTIxZDZhIiwidCI6ImM2ZTU0OWIzLTVmNDUtNDAzMi1hYWU5LWQ0MjQ0ZGM1YjJjNCJ9&pageName=19d9377c199ca334a5e1)

## Datasets:

It is essential to become familiar with the datasets before beginning any analysis. There are two tables in the datasets:

**Dimension table:** Static data like customer and product details.

**Fact table:** Transaction data.

gdb041:
* dim_customer
* dim_market
* dim_product
* fact_forecast_monthly - This table is used to forecast the customer’s need in advance, which can help in Higher customer satisfaction and reduced cost in warehouses for storage purposes
* fact_sales_monthly - This table is more or less is same as the fact_forecast_monthly table, but the last column has the value of the sold quantity instead of the forecast value.

gdb056:
* freight_cost
* gross_price
* manufacturing_cost
* Pre_invoice_dedutions
* Post_invoice_deductions


### Importing Data and Data Modeling:

After the data was cleaned and transformed, it was imported into Power BI from MySQL and a data model was produced. However, why is data modeling so crucial to analysis?

Four steps of work will be identified if you break down the entire data analyst's job. 

✅ Extracting Data ---> Cleaning Data---> ✅ Modeling Data ---> ✅ Analysis of Data

As you can see, data modeling is crucial since it establishes the framework for reporting, therefore you cannot skip the third step if you wish to get to the final step (the analysis section). The data model serves as the foundation for all visualizations, and improper modeling can impact report performance.

 I used the Snowflake schema data modeling approach for this project. 

![data model](https://github.com/yc-harshan-reddy17/Business_Insights-360/blob/main/Data%20model%20view.png)

## Power BI Dashboard Overview:

The dashboard is made up of six pages-->

### Home Page: A landing page with buttons to navigate to different pages.

![home page](https://github.com/yc-harshan-reddy17/Business_Insights_360_transformed/blob/main/home.png)

### Finance Page: Focuses on improving financial planning, budgeting processes, and cost control. Includes Profit and Loss statements, Top and Bottom Products and Customers by Net Sales, and more.

![finance page](https://github.com/yc-harshan-reddy17/Business_Insights_360_transformed/blob/main/finance%20view.png)

### Sales Page: Aims to increase sales revenue and market share. Features Customer performance by Net Sales, Gross Margin, Gross Margin %, and more.

![sales page](https://github.com/yc-harshan-reddy17/Business_Insights_360_transformed/blob/main/sales%20view.png)

### Marketing Page: Aims to increase brand visibility and customer engagement. Provides Segment Performance by Gross Margin% and Net Profit%, and more.

![marketing page](https://github.com/yc-harshan-reddy17/Business_Insights_360_transformed/blob/main/marketing%20view.png)

### Supply Chain Page: Aims to optimize inventory management and enhance supplier relationships for cost savings. Includes details about Forecast Accuracy, Net error, and more.

![supply chain](https://github.com/yc-harshan-reddy17/Business_Insights_360_transformed/blob/main/supply%20chain%20view.png)

### Executive Page: Provides the top executives a summary of the organization's performance. Contains the following: Sub-region performance, Top 5 Customers and Products, Net Sales, Gross Margin%, Net Profit%, and Revenue Contribution by Channel.

![executive page](https://github.com/yc-harshan-reddy17/Business_Insights_360_transformed/blob/main/Executive%20view.png)

## Skills Learned:

In this project and the Codebasics Bootcamp training, I gained knowledge of 
* Power BI basics
* Calculated columns and DAX measures
* Data modeling, data cleaning, bookmarks, conditional formatting
* Using custom tooltips, creating dynamic titles, and more.

### Tools Used:

SQL, Power BI Desktop, DAX language, DAX studio (to reduce file size), Project Charter file.

### Business Terms Learned:

Gross Sales, Gross Sales %, Gross Margin, Gross Margin %, , Pre-invoice deductions, Net Invoice Sales, Post-invoice deductions, COGS (cost of goods sold), Net sales,  Net Profit, Net Profit %,  YTG (year to go), YTD (year to date), Direct, Retailer, Consumer, Distributors.

## Conclusion :
Using statistics to inform decision-making, this report answers several "why" questions in a variety of settings. It is used as a tool to draw conclusions and direct activities with the ultimate goal of increasing AltiQ's profitability by making data-driven choices.

