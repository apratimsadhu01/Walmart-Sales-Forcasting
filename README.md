# Walmart-Sales-Forcasting

## Objective
The objective is predicting store sales using historical markdown data. One challenge of modelling retail data is the need to make decisions based on limited history. If Christmas comes but once a year, so does the chance to see how strategic decisions impacted the bottom line.

Predicting future sales for a company is one of the most important aspects of strategic planning. And Walmart is the best example to work with as a beginner as it has the most retail data set. Also, Walmart used this sales prediction problem for recruitment purposes too.

The data collected ranges from 2010 to 2012, where 45 Walmart stores across the country were included in this analysis. Each store contains several departments, and we are tasked with predicting the department-wide sales for each store. It is important to note that we also have external data available like CPI, Unemployment Rate and Fuel Prices in the region of each store which, hopefully, helps us to make a more detailed analysis.

## Datasets
Walmart Recruiting - Store Sales Forecasting downloaded from https://www.kaggle.com/c/walmart-recruiting-store-sales-forecasting

- train.csv - CSV Data file containing following attributes
  - Store
  - Dept
  - Date
  - Weekly_Sales
  - IsHoliday
 
*115064 Data rows*

- stores.csv - CSV Data File containing following attributes
  - Store
  - Type
  - Size
 
*45 Data rows*

- features.csv - CSV Data file containing following attributes
  - Store
  - Date
  - Temperature
  - Fuel_Price
  - MarkDown1
  - MarkDown2
  - MarkDown3
  - MarkDown4
  - MarkDown5
  - CPI
  - Unemployment
  - IsHoliday
 
*8190 Data rows*


## Machine Learning Models
- Linear Regression Model
- Random Forest Regression Model
- K Neighbors Regression Model
- XGBoost Regression Model
- Custom Deep Learning Neural Network
