AtliQ Hardware is growing rapidly in the recent years, and they have decided to implement the data analytics using PowerBi in their company for the first time to surpass their competitors in the market and to make data driven decisions. This project is hoped to give answers to the questions of stakeholder in terms all the aspects like finance, sales, marketing and supply chain.

[live report](https://app.powerbi.com/view?r=eyJrIjoiOTQzNDNjZTgtNDYzOS00ZjllLWJiZTAtMTBkZWIxYmMyOGVjIiwidCI6ImM2ZTU0OWIzLTVmNDUtNDAzMi1hYWU5LWQ0MjQ0ZGM1YjJjNCJ9)


**TECH STACKS**

SQL


PowerBi Desktop


Excel




















**POWERBI TECHNIQUES LEARNT**





What are all the questions should be asked before staring the project

Creating calculated columnS

creating measure using DAX language

Data modeling

Using Bookmarks to switch between two visuals

Page navigation with buttons

Using divide function to prevent zero division errors

creating date table using m language

Dynamic titles based on the applied filters

Using KPI indicators

Conditional formatting the values in visuals using icons or background color

Data validation techniques

PowerBi services

Publishing reports to PowerBi services

Setting up personal gateway to set up the auto refresh of data

PowerBi App creation

Collaboration, workspace, access permissions in PowerBi services






**BUSINESS RELATED TERMS**





Gross price

Pre-invoice deductions

Post-Invoice deductions

Net Invoice sale

Gross Margin

Net sales

Net profit

COGC - cost of goods sold

YTD - Year to Date

YTG - Year to Go

Direct

Retailer

Distributors

Consumer





**DATASET OVERVIEW**


Understanding what data is available will be more helpful while doing analysis. before jumping on to the analysis get good understanding of what are data available.

Dimension table : It will have the static data like details of customer and products

Fact table : It will have the data about the transactions

gdb041:

dim_customer
          
  27 distinct markets (ex India, USA, spain)
 
  75 distinct customers thorough out the market

  2 types of platforms

Brick & Motors - Physical/offline store

E-commerce - Online Store (Amazon, flipkart)


Three channels

Retailer

Direct

Distributors


dim_market

  27 distinct markets (ex India, USA, spain)
 
  7 sub-zones
  
  4 regions

APAC

EU

nan

LATAM



dim_product

Divisions

P & A

Peripherals

Accessories

PC

Notebook

Desktop

N & S

Networking

Storage

There are 14 different categories, Like Internal HDD, keyboard

There are different variants available for the same product



fact_forecast_monthly

This table is used to forecast the customer’s need in advance, which can help in

Higher customer satisfaction

Reduced cost in warehouses for storage purpose

The table is denormalized by data engineering team, as it is a data warehouse which is aimed to be used for analytical work.

All the date of the month will be replaced by the start date of the month

It will have all the column names and in the end it will have the forecast quantity need of the customer



fact_sales_monthly

This table is more or less is same as fact_forecase_monthly table, but the last column has the value of sold quantity instead of forecast value.



gdb056

freight_cost

This table has details of travel cost and other cost for each market with fiscal year


gross_price

Has the details of gross prices with product code


manufacturing_cost

Has the details of manufacturing cost with product code with year



Pre_invoice_dedutions

Has the details of pre invoice deductions percentage for each cutomer with year


Post_invoice_deductions

Post invoice deductions and other deductions details




[LIVE DASHBOARD LINK](https://app.powerbi.com/view?r=eyJrIjoiOTQzNDNjZTgtNDYzOS00ZjllLWJiZTAtMTBkZWIxYmMyOGVjIiwidCI6ImM2ZTU0OWIzLTVmNDUtNDAzMi1hYWU5LWQ0MjQ0ZGM1YjJjNCJ9)



[OVER ALL VIEW](https://github.com/Sarathreddy333/PowerBI_Business_360/blob/main/Screenshot%202025-05-28%20180211.png)

[FINANCE VIEW](https://github.com/Sarathreddy333/PowerBI_Business_360/blob/main/Screenshot%202025-03-22%20233255.png)

[SALES VIEW](https://github.com/Sarathreddy333/PowerBI_Business_360/blob/main/Screenshot%202025-03-22%20233305.png)

[MARKETING VIEW](https://github.com/Sarathreddy333/PowerBI_Business_360/blob/main/Screenshot%202025-03-22%20233315.png)

[SUPPLY CHAIN VIEW](https://github.com/Sarathreddy333/PowerBI_Business_360/blob/main/Screenshot%202025-03-22%20233325.png)


