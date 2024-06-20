# E- Commerce Sales Analysis
## Table of Content
- [Project-Overview](#project-overview)
- [Recommendation](#recommendation)


### Project-Overview

This data analysis project aims to provide **insight** into the sales performance of an e-commerce company over the last year.
### Data Sources
**Sales Data:** The primary dataset used for this analysis is the "Sales_data.csv" file. 
### Tools:
- Excel 
  - [Download here](www.microsoft.com)
- SQL Server
- Powerbi
### Data Cleaning/Preparation
In the initial data preparation, we performed the following tasks:
1. Data loading and inspection
2. Handling Missing values
3. Data cleaning and formatting
### Exploratory Data Analysis
EDA involve exploring the sales to answer key questions, such as
- What is the overall sales trend
- which products are top sellers
- What are the peak sales period
### Data Analysis
---
Finding the top 5 total sales by country
  ```sql
  select Top 5 countries from salesproject
where gender='M'
  ```
### Results/Findings
The analysis results are summarised as follows
1. The company sales last long but requires urgent steps from management
2. Product Category A is the most promising product for the company for now,
3. customer segment for now with a high penchant for the product during peak sales

### Recommendation
---
Based on the analysis we recommend the following actions:
- Invest in marketing and promotions during peak sales
- Implement a customer feedback program to get feedback from customer to enable improvement on the products.

###Limitations:
i had to remove all zero values from budget and revenue column because they would have affected the accurracy of my conclusion from the analysis
### References
1. SQL for Business Analysis
2. [Stack-Overflow](www.stackoverflow.com)


















