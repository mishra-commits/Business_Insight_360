# Business_Insight_360
# **Project Overview**
AltiQ Hardware, a fast-growing company expanding globally, specializes in selling computers and accessories through three main channels: retailers, direct sales, and distributors.

Despite its growth, the company faced unexpected losses after opening a store in America. These setbacks were identified through surveys, intuition, and basic Excel analysis. With competitors boasting robust analytics teams, AltiQ Hardware recognizes the urgent need to develop its analytics capabilities to thrive in the industry.

To surpass competitors and enable data-driven decision-making, the company has decided to implement Power BI for analytics. This project aims to provide stakeholders with insights into finance, sales, marketing, and supply chain, ensuring informed decisions at all levels.

I worked on this project by following the Codebasics PowerBi Course,

Explore the live dashboard : [View Here](https://app.powerbi.com/view?r=eyJrIjoiNjc3YzA1ZDEtNThjYS00NDQyLTk3YmYtMWZiMGRlM2QwOTEwIiwidCI6ImM2ZTU0OWIzLTVmNDUtNDAzMi1hYWU5LWQ0MjQ0ZGM1YjJjNCJ9)


# Datasets:
Before diving into analysis, understanding the datasets is crucial. The datasets consist of two tables:

**Dimension table:** Static data like customer and product details.

**Fact table:** Transaction data.

gdb041:

* dim_customer
* dim_market
* dim_product
* fact_forecast_monthly - This table is used to forecast the customer’s need in advance, which can help in Higher customer satisfaction and reduced cost in warehouses for storage purposes
*fact_sales_monthly - This table is more or less is same as the fact_forecast_monthly table, but the last column has the value of the sold quantity instead of the forecast value.

gdb056:

* freight_cost
* gross_price
* manufacturing_cost
* Pre_invoice_dedutions
* Post_invoice_deductions
# Importing Data and Data Modeling:
Data was imported from MySQL into Power BI, and a data model was created after cleaning and transforming the data. But why data modeling is very important for analysis right??

If you break down the whole work of a data analyst then you will come up with 4 steps of work

✅ Data Extract ---> ✅ Data Cleaning---> ✅ Data Modelling ---> ✅ Data Analysis

See you can't skip the 3rd step if you want to reach the last step (analysis part), Data modeling is essential because it lays the foundation for reports. All visuals are built upon the data model, and poor modeling can affect report performance.

In this project, we have followed the Snowflake schema data modeling method.
![](https://github.com/mishra-commits/Business_Insight_360/blob/main/Data%20Model.PNG.png)
# PowerBI Dashboard Overview
The dashboard comprises six pages-->
**Home Page: A landing page with buttons to navigate to different pages.**
![](https://github.com/mishra-commits/Business_Insight_360/blob/main/Landing_page.PNG.png)

**Finance Page: Focuses on improving financial planning, budgeting processes, and cost control. Includes Profit and Loss statements, Top and Bottom Products and Customers by Net Sales, and more.**
![](https://github.com/mishra-commits/Business_Insight_360/blob/main/Finance_View.PNG.png)

**Sales Page: Aims to increase sales revenue and market share. Features Customer performance by Net Sales, Gross Margin, Gross Margin %, and more.**
![](https://github.com/mishra-commits/Business_Insight_360/blob/main/Sales_View.PNG.png)

**Marketing Page: Aims to increase brand visibility and customer engagement. Provides Segment Performance by Gross Margin% and Net Profit%, and more.**
![](https://github.com/mishra-commits/Business_Insight_360/blob/main/Marketing_View.PNG.png)

**Supply Chain Page: Aims to optimize inventory management and enhance supplier relationships for cost savings. Includes details about Forecast Accuracy, Net error, and more.**
![](https://github.com/mishra-commits/Business_Insight_360/blob/main/SupplyChain_View.PNG.png)

**Executive Page: Provides an overview of the organization's performance for top management. Includes Net Sales, Gross Margin%, Net Profit%, Revenue Contribution by channel, Top 5 Customer and Product, Sub Region performance, and more.**
![](https://github.com/mishra-commits/Business_Insight_360/blob/main/Executive_View.PNG.png)
  # Skills
  ## Learnt Power BI fundamentals
  1. creating calcualting columns and DAX measures
  2. Data Modelling ,data validation techniques and using KPI indicators
  3. using bookmarks to switch between two visuals and conditional formatting
  4. page navigation with buttons
  5. using tooltips to save page area
  6. Dynamic titles based on the applied filters
  7. PowerBI services for publishing and sharing reports online
  8. Auto refresh setup for data through gateway
  9. Creating date table using M language
## Tech Stacks
1. SQL
2. PowerBI Desktop
3. DAX language
4. Dax studio( TO REDUCE FILE SIZE)
5. Project Charter file
## Business Related Terms
1. Gross Margin,Gross Margin %
2. Gross Sales , Gross Sales %
3. Pre _ invoice deductions and Post _ invoice deductions
4. Net sales , Net Invoice Sales
5. Net Profit and Net Profit %
6. COGS(cost of goods sold)
7. YTG (year to go)
8. YTD ( year to date)
9. Direct ,retailer, consumer and distributor
## Soft Skills
1. Stakeholders mapping analysis
2. Effective communication with stakeholders feedback and management
3. Business and domain knowledge in sales,finance,marketing and supply chain.
# Conclusion :
This report empowers decision-making based on data, addressing numerous "why" questions across various scenarios. It serves as a tool to extract insights and guide actions, ultimately aiming to enhance AltiQ's profitability through data-driven decisions.
    


