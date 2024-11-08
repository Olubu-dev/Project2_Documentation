# Project2_Documentation

### Project Title: Customer Segmentation Analysis

[Project Overview](#project-overview)

[Data Sources](#data-sources)

[Tools Used](#tools-used)

[Data Cleaning and Preparations](#data-cleaning-and-preparations)

[Exploratory Data Analysis](#exploratory-data-analysis)

[Data Analysis](#data-analysis)

[Data Visualization](#data-visualization)

[Key Findings](#key-findings)

[Recommendations](#recommendations)

[Conclusion](#conclusion)

[Appendix](#appendix)

### Project Overview
---
This project aims to analyze the customer data for a subscription service to identify customer segments and uncover trends in subscription behavior.The goal is to optimize subscription offers,understand customers preferences, and improve overall service deliverables to customer based on the key insights by analyzing various parameters.By leveraging data-driven insights, the project seeks to enhance customer satisfaction within the subscription service.

### Data Sources 
---
The primary source of data used for this analysis is LITA Capstone Dataset.xlsx and this is an open source data that can be downloaded from any repository site.

### Tools Used
---
- Microsoft Excel
  1. For Data Cleaning
  2. For Analysis
  3. For Data Visualization
     
-Structured Query Language for Querying of the Data

-Power BI 
  1. To build interactive dashboard
  2. For Data Visualization

### Data Cleaning and Preparations
---
This phase includes cleaning and preparing the data before visualizing it. The following steps was adopted:
  1. Data loading and Inspection
  2. Data Cleaning and formatting

### Exploratory Data Analysis
---
This involves the exploration of the data to answer some basic questions about the data such as;
- How many customers canceled and those that did not cancel their subscription?
- What are the trends in subscription types and cancellations over time?
- How does renewals compare to cancellations across different customer segments?
- How do these segments differ in terms of revenue generated, subscription types, and cancellation rates?

### Data Analysis
---
```Excel
=SUMIF(C2:C75001,C2,H2:H75001)
```
```
=AVERAGEIF(D2:D75001,D2,H2:H75001)
```
  1. Pivot tables was used to summarize total sales by product, region, and month;top selling products
  2. Formulas was used to calculate metrics such as average revenue per product and total revenue by each region


```SQL
SELECT * FROM [dbo].[Project2]
```
The xlsx file was converted to a csv file and  imported to SQL server environment before creating a databasea and validating the following queries;
  - 
  - Retrieving the total number of customers from each region
  - To find the most popular subscription type by number of customers
  - To find customers who canceled their subscription within 6 months
  - To calculate average subscription duration for all customers
  - To find customers with subscription longer than 12  months
  - To calculate revenue by subscription type
  - To find top 3 regions by subscription cancellations
  - To find the total number of active and canceled subscriptions

- Power BI
  Here, a dashboard was created to visualize the insights found in Excel and SQL which includes the following;
  - Key customer segments
  - Cancellation trends
  - Subscription types and trends
  - Slicers to filter the customer data to identify subscription trends based on cancellation status,region and subscription type.
  - Bar charts, line chart, tree map, donot chart, and cards was also used to visualize trends in the data

### Data Visualization
---									
![image](https://github.com/user-attachments/assets/4e17c83a-7b0e-40d1-839c-3a0671f51419)

![image](https://github.com/user-attachments/assets/492b2810-0bb8-4df1-9842-84ee4e89c59f)

![image](https://github.com/user-attachments/assets/eeca6757-996a-4a9a-95bb-40ff4cbe1537)

### Key Findings
---
The analysis revealed that active customers contributed a total revenue of ₦82 million, with an average subscription duration of 365days. Subscription types varied, with Basic being the most popular (64%), followed by Premium and Standard (18% each). Revenue trends showed a peak at ₦15 million but fluctuated, ending the year at ₦7 million. Regionally, the East led with ₦37 million in revenue, while other regions generated ₦15 million each. Cancellation patterns were also irregular, with spikes in March and the third quarter. Revenue trends peaked at ₦15 million mid-year, closing at ₦7 million in December. Interactive slicers for subscription type, region, and cancellation status allowed a dynamic exploration of insights across the dashboard, adjusting visualizations in real-time for a comprehensive view of customer behaviour.

### Recommendations
---
- To have specific offers and promotions at seasons like December in order to have consistent sales and stabilize revenue.
- There should be marketing campaigns and special offers in the East region to maximize revenue and explore areas to improve on the revenue in other regions.
- The service should timely observe the trends in the regions, monitor subscription types and adapt methods based on regional performance to enhance overall customer satisfaction.

### Conclusion
---
In conclusion, this analysis shows key areas for optimizing the subscription service, enhanced offerings for the popular Basic subscription type, and focused marketing in high revenue regions. By addressing seasonal revenue dips and leveraging key insights, the subscription service can drive growth, reduce cancellations, and improve customer satisfaction across segments.

### Appendix
---
![image](https://github.com/user-attachments/assets/7cc04865-c037-4bf9-b9b6-027d649d7582)

![image](https://github.com/user-attachments/assets/df471cec-f984-4ba1-b18f-2885d1d5f95a)



