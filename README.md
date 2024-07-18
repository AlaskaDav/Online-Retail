# Online-Retail

#### Project Overview

I have been asked by the CEO and CMO to provide visuals on the metrics that they wish to analyse for the online retail store. Ensure to gather the requirements and provide them with the type of visual that would be best suited to the scenario. The senior management wants to understand how their business is performing and what areas are the key strengths of the company. They are also focused on identifying opportunities that would lead to growth and generate more revenue in the future as expansion is top of mind for these leaders and they’re keen to understand where the most lucrative opportunities are in their business. They would also like to view different metrics based on the demographic information that is available in the data.

## Table of Content 

- [Data Source](#data-source)
- [Tools Used](#tools-used)
- [ETL Processing](#etl-processing)
- [Recommendations](#recommendations)
- [Data Analysis Procedures](#data-analysis-procedures)
- [Project Dashboard](#project-dashboard)
- [Results and Findings](#results-and-findings)
- [Recommendations](#recommendations)

#### Data Source
This is a real life data (.xlsx file) which is provided by TATA was gotten from Forage site.

#### Tools Used 

- Microsoft Excel: for easy access to the contents of the file, viewing and understanding of the components of the data.
    - [Download here](http://microsoft.com)
- Power Querry : This is used to carry out the ETL process on the data.
- PowerBI: For visualization and creating reports.

#### ETL Processing

In the initial data preparation process, the following process was performed
1. Data Extraction: The downlaoaded .xlsx file from TATA/forage site was extracted from Microsoft Excel. Although the data  file was a single file but It was a pretty dirty data set with a lot of cleaning process and transformation.
2. Cleaning and Transformation process taken place involves:
   - Promoting headers
   - Changing data types
   - Replacing null values with N/A(Not Available)
   - Removing non relevant columns to the business problems/questions.
   - Added conditional column to:
     (a) Create a check that the quantity should not be below 1 unit.
     (b) Create a check that the Unit price should not be below $0.
     (c) Create a check that contains some returns to the store which are provided in negative quantities.
   - Renaming the data columns
   - Inserted a revenue column by creating a measure using DAX formula
   - Created a new table by extraction  for Date/Calendar with the following columns :
     (a) Date Column (b) Year Column (c) Month Column (d) Month Number 
   - 
4. Loading process involves loading the completely transformed and cleaned data into Pivot table to build dashboard for reporting and visualizations.
 
#### Key Insights to consider

- Question 1
The CEO of the retail store is interested to view the time series of the revenue data for the year 2011 only. He would like to view granular data by looking into revenue for each month. The CEO is interested in viewing the seasonal trends and wants to dig deeper into why these trends occur. This analysis will be helpful for the CEO to forecast for the next year.

- Question 2
The CMO is interested in viewing the top 10 countries which are generating the highest revenue. Additionally, the CMO is also interested in viewing the quantity sold along with the revenue generated. The CMO does not want to have the United Kingdom in this visual.

- Question 3
The CMO of the online retail store wants to view the information on the top 10 customers by revenue. He is interested in a visual that shows the greatest revenue generating customer at the start and gradually declines to the lower revenue generating customers. The CMO wants to target the higher revenue generating customers and ensure that they remain satisfied with their products.

- Question 4
The CEO is looking to gain insights on the demand for their products. He wants to look at all countries and see which regions have the greatest demand for their products. Once the CEO gets an idea of the regions that have high demand, he will initiate an expansion strategy which will allow the company to target these areas and generate more business from these regions. He wants to view the entire data on a single view without the need to scroll or hover over the data points to identify the demand. There is no need to show data for the United Kingdom as the CEO is more interested in viewing the countries that have expansion opportunities.

#### Data Analysis Procedures:

- Downloaded the file from youtube (.xlsx files in MsExcel).
- Loading and opened the data using Microsoft Excel for Cleaning and analysing the contents of the data
- Ensure data clarification and data validity.
- Created new sheets for my pivot analysis and the visualizations
- Created a new sheet for dashboard for report presentation. 
- Providing insights, presenting informations and advice.
- Creating outstanding reports for end user understanding, board of directors and shareholders.

- ### Project Dashboard

 ![Coca Cola USA dashboard](https://github.com/AlaskaDav/Cola-Cola-USA-Retailer/assets/155531290/c5e0303c-5700-4464-9587-3cc4f55c8db9)

#### Results and Findings

The analysis results are summarized as follows;
1. The total Sales for each brand and each retailer for the year 2022 and 2023 is visualized below: ![Brand by Sales Revenue](https://github.com/AlaskaDav/Cola-Cola-USA-Retailer/assets/155531290/64540b03-012d-4c21-a1bc-0a1bf614e7b9)

![Retailer by Sales Revenue](https://github.com/AlaskaDav/Cola-Cola-USA-Retailer/assets/155531290/7d62a659-e29c-432b-97c4-973c6ebea6e2)

2. The amount of units sold for both years is recorded to be *24,788,610 units*, average price is *$0.45* and the overall Operating profit is *$4,722,497*

#### Recommendations

Based on the analysis, I recommend the following actions:
 - Measuring the performance of each brands and retailers is a great approach to selecting the best performing brand ad retailer. However, Coca-cola organization should regularly consider population and potential customers in each state, the level of satisfaction each brands offer.
 - Trade discount can be effected on percentage of purchase by the retailers to serve as an encouragement to higher purchase.
 - Strategies for retailer retention should also be developed; this could include effective communication, ensure customer satisfaction, credit allowance, building trust, bonus on referral, product differentiation, price reduction, cost leadership, yearly bonus sales etc
 - Put into Consideration the educational background and business acumen of retailer or potential retailers (offering business advices) would also indirectly contribute to revenue generation.
 
🖥️
🍹


  Question 1
   - The CEO of the retail store is interested to view the time series of the revenue data for the year 2011 only. He would like to view granular data by looking into revenue for each month. The CEO is interested in viewing the seasonal trends and wants to dig deeper into why these trends occur. This analysis will be helpful for the CEO to forecast for the next year.

 Question 2
   - The CMO is interested in viewing the top 10 countries which are generating the highest revenue. Additionally, the CMO is also interested in viewing the quantity sold along with the revenue generated. The CMO does not want to have the United Kingdom in this visual.

 Question 3
   - The CMO of the online retail store wants to view the information on the top 10 customers by revenue. He is interested in a visual that shows the greatest revenue generating customer at the start and gradually declines to the lower revenue generating customers. The CMO wants to target the higher revenue generating customers and ensure that they remain satisfied with their products.

 Question 4 
  - The CEO is looking to gain insights on the demand for their products. He wants to look at all countries and see which regions have the greatest demand for their products. Once the CEO gets an idea of the regions that have high demand, he will initiate an expansion strategy which will allow the company to target these areas and generate more business from these regions. He wants to view the entire data on a single view without the need to scroll or hover over the data points to identify the demand. There is no need to show data for the United Kingdom as the CEO is more interested in viewing the countries that have expansion opportunities.
