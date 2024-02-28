# Bike-Sales-Performance

## Table of Content
- [Project Overview](#project-overview)
- [Data Sources](#data-sources)
- [Tools](#tools)
- [Cleaning/Transformation](#cleaning/transformation)
- [EDA](#eda)
- [Data Analysis](#data-analysis)
- [Result/Findings](#result/findings)
- [Recommendations](#recommendations)

## Project Overview
---

This data analysis aims to understand the trend of the product purchase, what influences the buyers, how improve on their occupation and distances covered to and fro work determines the demand of bikes.


### Data Sources

Sales Data: The primary dataset used for this analysis is the 'Data survey.xlsx' file, containing detiled infromation about each regional sales made.

### Tools

- Excel - Data cleaning
  - Data Analysis
  - Creating reports
 



### Cleaning/Transfromations

In the initial data prepaeration phase, we performed the foolowing tasks:
1. Data Loading and inspection
2. Handling missing values
3. Data cleaning and formatting


### EDA

EDA involved in exploring the sales data to answer questions such as:

- What is the over all sales trend?
- Does educational  backgroud inflence demand for bike?
- Does distance covered per customer influecece bike demands?
- What is the regional sales trend?
- What is the sales trend by economic status?
- What is the age bracket of customers?
- What does marital status affect bike purcahse across all regional?

  ### Data Analysis

  ```Excel
  =IF(L3>55,"Old",IF(L3>=31,"Middle Age",IF(L3<31,"Adolescents")))
  ```

  ### Result/Findings
  The analysis resultss rae summarized as follows:
  - The bike sales perfomance in Europe, North America and Pacific varies dues to uneven customers preferences
  - Demand for bikes amongst the adolescents is steadily high in all regions
  - Distance  coommute per customer upto 10+ miles saw a decline all through the region
  - Generally, peopel with higher pay and adults should be targeted for marketing efforts.

### Recommendations

Based on the analysis, we recommend the following actions:
- Focus should be in promos and marketing to increase revenue
- Implement a customer segmentation strategy to target high income earners
- Invest in marketing to female gender for higher patronage.
