# Online-Retail

#### Project Overview

I have been asked by the CEO and CMO to provide visuals on the metrics that they wish to analyse for the online retail store. Ensure to gather the requirements and provide them with the type of visual that would be best suited to the scenario. The senior management wants to understand how their business is performing and what areas are the key strengths of the company. They are also focused on identifying opportunities that would lead to growth and generate more revenue in the future as expansion is top of mind for these leaders and they’re keen to understand where the most lucrative opportunities are in their business. They would also like to view different metrics based on the demographic information that is available in the data.

## Table of Content 

- [Data Source](#data-source)
- [Tools Used](#tools-used)
- [ETL Processing](#etl-processing)
- [CMO and CEO questions to consider](#CMO-and-CEO-questions-to-consider)
- [Data Analysis Procedures](#data-analysis-procedures)
- [Results and Findings](#results-and-findings)
- [MY SCRIPT PRESENTATION](#my-script-presentation)
- [Project Dashboard](#project-dashboard)
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
   - Promoting first row as headers
   - Changing data types
   - Replacing null values with N/A (Not Available).
   - Removing non relevant columns to the business problems/questions.
   - Added conditional column to:
     (a) Create a check that the quantity should not be below 1 unit.
     (b) Create a check that the Unit price should not be below $0.
     (c) Create a check that contains some returns to the store which are provided in negative quantities.
   - Renaming the data columns
   - Inserted a revenue column by creating a measure using DAX formula
   - Created a new table by extraction  for Date/Calendar with the following columns :
     (a) Date Column (b) Year Column (c) Month Column (d) Month Number 
4. Finally, I loaded the completely transformed and cleaned data into PowerBI report page to build dashboard for reporting and visualizations.
 
#### CMO and CEO questions to consider

 Question 1
   - The CEO of the retail store is interested to view the time series of the revenue data for the year 2011 only. He would like to view granular data by looking into revenue for each month. The CEO is interested in viewing the seasonal trends and wants to dig deeper into why these trends occur. This analysis will be helpful for the CEO to forecast for the next year.

 Question 2
   - The CMO is interested in viewing the top 10 countries which are generating the highest revenue. Additionally, the CMO is also interested in viewing the quantity sold along with the revenue generated. The CMO does not want to have the United Kingdom in this visual.

 Question 3
   - The CMO of the online retail store wants to view the information on the top 10 customers by revenue. He is interested in a visual that shows the greatest revenue generating customer at the start and gradually declines to the lower revenue generating customers. The CMO wants to target the higher revenue generating customers and ensure that they remain satisfied with their products.

 Question 4 
  - The CEO is looking to gain insights on the demand for their products. He wants to look at all countries and see which regions have the greatest demand for their products. Once the CEO gets an idea of the regions that have high demand, he will initiate an expansion strategy which will allow the company to target these areas and generate more business from these regions. He wants to view the entire data on a single view without the need to scroll or hover over the data points to identify the demand. There is no need to show data for the United Kingdom as the CEO is more interested in viewing the countries that have expansion opportunities.

#### Data Analysis Procedures:

- Downloaded the file from youtube (.xlsx files in MsExcel).
- Loading and opened the data using Microsoft Excel for Cleaning and analysing the contents of the data
- Ensure data quality and data validity for effective analysis.
- I created new measures, columns and tables using DAX for my visualizations and reporting.
- Providing insights, presenting informations and advice.
- Creating outstanding reports for CMO and CEO.
 
#### Results and Findings

My analysis results are summarized as follows;
1. From the analysis of the data, the Online Retail sales has improved over the years from (about **$885,000**) in year 2010 to ( over **$10 million**) in year 2011 and this resulted into generating a total revenue of over **$11 Million**. This is also due to the increase in the sales quantity for the years. In addition, the increase in revenue generated over the month in the year 2011 is as a resulting effect of increase in order/quantity, except the slight reduction both in revenue and quantity sold in the month of December.
2. In October and November 2011, more revenue was realised wtih an increase in sales, this could be because of the festive period or possibly be that an event was held by the retail store or any other organization.
3. The top 10 countries generating the highest revenue and quantities sold are: Germany, France, EIRE, Spain, Netherlands, Belgium, Switzerland, Portugal, Australia and Norway.
4. The top 10 customers with highest revenue are : An Anonymous Customer(with over **$2M revenue**),
5. A record showing that out of all the goods sold, a percentage of **1.96%** was returned back to the store either because of spoilage, wrong address, or customer dissatisfaction etc. This also affected the level of revenue generated in a little proportion in the period.

####  MY SCRIPT PRESENTATION
    I’m David O Folagbade, and I’m excited to share some insights about your business. Thank you for providing the guiding questions. It was helpful to see what types of insights you are looking to gain from the data. I hope you find the analysis compelling and helpful as you make decisions regarding future business opportunities.
    First off, I want to assure you that I’ve provided the most up to date and error free analysis. After I loaded the data into my software, I scrubbed any records that have negative quantities and unit price, as these records needed to be removed in order to provide helpful analysis.
    As for your first question, the CEO has requested a trend of the revenue to see if there is any seasonality in the store sales. My analysis shows that there are some months of the year where exceptional growth is witnessed. The data shows that the revenue in the first 8 months is fairly constant as the average revenue generated for these 8 months is around $685k. The increase in revenue starts in the month of September, where the revenue increases by 40% over the previous month. This trend continues till the month of November where it reached 1.5 million USD, the highest during the entire year. The data is incomplete for the month of December, therefore, no conclusion can be drawn from it, unfortunately. This analysis shows that the retail store sales are impacted by the seasonality which usually occurs in the last 4 months of the year.
    The second visual shows how the top 10 countries which have opportunities for growth are performing. This data does not include the UK as the country already has high demand and I’ve been told you’re more focused on the countries where demand can be increased. The analysis shows that countries such as the Netherlands, Ireland, Germany and France have high volumes of units bought and revenue generated. I would suggest that these countries should be focused on to ensure that measures are taken to capture these markets even more.
    The third analysis has been performed on the top 10 customers who have purchased the mos from the store. The data shows that there is not much of a difference between the purchases made by the top 10 customers. The highest revenue generating customer only purchased 17% more than the 2nd highest which shows that the business is not relying only on a few customers to generate the revenue. This shows that the bargaining power of customers is low and the business is in a good position.
    Finally, the map chart shows the regions that have generated the most revenue compared with the regions that have not. It can be seen that apart from the UK, countries such as Netherlands, Ireland, Germany, France and Australia are generating high revenue and the company should invest more in these areas to increase demand for products. The map also shows that most of the sales are only in the European region with very few in the American region. Africa and Asia do not have any demand for the products, along with Russia. A new strategy targeting these areas has the potential to boost sales revenues and profitability.
    Thanks so much for your time. If you have any questions about the analysis or would like to see anything additional after you’ve had time to digest this information, I’d be happy to develop that for you.

### Project Dashboard



#### Recommendations

Based on the analysis, I recommend the following actions for as an expansion strategy:
 - Measuring the performance of each country and customer is a great approach to selecting the best performing brand ad retailer. However,the Online Retail company should regularly consider population and potential customers in each country, the level of satisfaction each products offers.
 - Trade discount can be effected on percentage of purchase by the retailers to serve as an encouragement for higher purchase.
 - Strategies for customer retention should also be developed; this could include effective communication, ensure customer satisfaction, credit allowance, building trust, bonus on referral, product differentiation, price reduction, cost leadership, yearly bonus sales etc
 - I would recommend that Online Retail store should also focus more on these following potential countries to increase the number of sales channel to those countries:
   (a) Netherland
   (b) Austalia
   (c) Sweden
   (d) Ireland
   (e) Switzerland
    This is because, despite the fact that little quanties were sold in those countries, much revenue were still generated. I was able to achieve this by comparing the total revenue to total order for the countries to determine the average revenue by price.
   - Finally, i would recommend that the Online Retail store should endeavour to ensure an improved customer satisfaction for an increase in customer base and also to expand operations lower revenue generating contries.


🖥️
🍹
