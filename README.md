# E-Commerce Sales Analysis

## Table of Contents

- [Project Overview](#project-overview)


### Project Overview 

This data analysis project aims to provide insight inot the sales performance of an e-commerce company over the past year. By analyzing variuos aspects of the sales data, we seek to identify trends, make data-driven recommendations, and gain a deepr understanding og the company's perfomance.

### Data Sources

Sales Date: The primary dataset used for this analysis is the "saless_data.csv" file, containing detailed information about each sle made by the company.

### Tools

- Excel - Data cleaning 
  - [Download_here](https://microsoft.com) 
- SQL Sever - Data Analysis
- PowerBI - Creating reports


### Data Cleaning/Preparation

In the intial data preparation phase, we performedd the following tasks:
1. Data loading and Inspections.
2. Handling missing values.
3. Data cleaning and forcastting.

### Exploratory Data Analysis 

EDA involved exploring the sales data to answer key questions, such as:

- What is the overall sales trend?
- Which products are top sallers?
- What are the peak sales periods?

### Data Analysis

Inculdes some interesting code/features worked with

```sql
SELECT * FROM table
WHERE cond = 2;
```

### Results/Findings

The analysis results are summarized as follows:
1. The companys sales have been steadily increasing over the past year, with a noticible peak during the holiday season.
2. Product Category A is the best performing category in terms of sales and revenue.
3. Customer segments with high lifetime value(LTV) should be targeted for marketing efforts.

### Recomendations 

Based on the analysis, we recommend the following actions:
- Invest in marketing and promotions during peak sales seasons to maximize revenue.
- Focus on expanding and promoting products in Category A.
- Implement a customer segmentation strategy to target high-LTV customers effectively.

### Limitations

I had to remove all zero values from budget and revenue colums because they would have affected the accuracy of my conclusions from the analysis. There are still a few outliers even  after the omissions but even then we can still see that there is a positive correlation between both budget and numbers of votes with revenue.

### References 

1. SQLfor businesses by werty.
2. [Stack Overflow](https://stack.com)
