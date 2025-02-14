# Walmart Sales Forecasting
## 📌 Project Overview
Walmart is one of the largest retail chains in the U.S., aims to enhance its sales forecasting accuracy. The company experiences fluctuations in demand due to holidays, promotional markdowns, and economic conditions. Accurate predictions can help mitigate stock shortages and optimize inventory management.

This project focuses on developing machine learning models to predict weekly sales for 45 Walmart stores across different regions. Key influencing factors include holiday events, fuel prices, temperature variations, CPI, and unemployment rates.

## 📂 Dataset Information

**Dataset Source:** The dataset is publicly available on [Kaggle](https://www.kaggle.com/competitions/walmart-recruiting-store-sales-forecasting/data)

The dataset contains historical sales records from February 5, 2010, to November 1, 2012. It includes the following sub-datasets:

1. **features.csv**

2. **stores.csv**

3. **train.csv**

4. **features.csv**

**1. features.csv**

This file contains additional data related to the store, department, and regional activity for the given dates. It contains the following fields:

Store – Unique store identifier

Date – Week of recorded sales

Temperature – Average temperature in the region

Fuel_Price – Fuel cost in the respective region

MarkDown1-MarkDown5 - Anonymized data on Walmart's promotional markdowns, available only from November 2011 onward.Data is not available for all stores at all times; missing values are marked as NA.

CPI – Consumer Price Index at the time

Unemployment – Unemployment rate in the region

IsHoliday – Indicates whether the week includes a major holiday (1 for holiday, 0 for non-holiday)

**2. stores.csv**

This file contains anonymized information about the 45 **Stores**, indicating the **Type** and **Size** of store.

**3. train.csv**

This is the historical training data, which covers to 2010-02-05 to 2012-11-01. Within this file you will find the following fields:

Store - Unique store identifier/number

Dept - Unique department identifier/number

Date - Week of recorded sales

Weekly_Sales -  Sales for the given department in the given store

IsHoliday - Indicates whether the week includes a major holiday (1 for holiday, 0 for non-holiday)

**4. test.csv**

This file is identical to train.csv, except we have withheld the weekly sales. You must predict the sales for each triplet of store, department, and date in this file.


## 🎉 Major Holiday Events Considered:

Super Bowl: February 12, 2010 | February 11, 2011 | February 10, 2012 | February 8, 2013

Labor Day: September 10, 2010 | September 9, 2011 | September 7, 2012 | September 6, 2013

Thanksgiving: November 26, 2010 | November 25, 2011 | November 23, 2012 | November 29, 2013

Christmas: December 31, 2010 | December 30, 2011 | December 28, 2012 | December 27, 2013



## 🎯 Project Objectives

The primary goal is to build and evaluate regression models to predict weekly sales based on various influencing factors. This involves:

✔ Understanding the dataset and performing necessary data cleaning.

✔ Conducting Exploratory Data Analysis (EDA) to identify patterns and trends.

✔ Implementing feature engineering to enhance model performance.

✔ Developing and comparing regression models (both single and multiple feature-based).

✔ Evaluating models using metrics like R² score, RMSE, and MAE to determine the most effective approach.

