# Demand Forecasting with LightGBM

## Table of contents
* [Introduction](#Introduction)
* [Business Problem](#Business_Problem)
* [Task Details](#Task_Details)
* [Attribute Information](#Attribute_Information)

<a id="Introduction"></a>
## Introduction
Demand forecasting is the process of predicting what the demand for certain products will be in the future. This helps manufacturers to decide what they should produce and guides retailers toward what they should stock.

![image](https://user-images.githubusercontent.com/83332641/171662826-1524f688-2360-4aac-a747-dfab436f70e1.png)


## Business Problem

Create a 3-month demand forecasting model for the relevant retailer using the time series and machine learning techniques.
The data set includes 5 years of data for 10 different stores and 50 different products of a chain of stores between 2013–01–01 and 2017–12–31.

<a id="Task_Details"></a>
## Task Details

* 1 IMPORTING LIBRARIES AND DATA
* 2 EXPLORATORY DATA ANALYSIS
* 3 FEATURE ENGINEERING & DATA PRE-PROCESSING
  * 3.1 Date Features
  * 3.2 Random Noise
  * 3.3 Lag/Shifted Features
  * 3.4 Rolling Mean Features
  * 3.5 Exponentially Weighted Mean Features
  * 3.6 One-Hot Encoding
  * 3.7 Converting sales to log(1+sales)
* 4 MODEL
  * 4.1 Time-Based Validation Sets
  * 4.2 LightGBM Model
  * 4.3 Feature Importance
  * 4.4 Final Model

<a id="Attribute_Information"></a>
## Attribute Information:

**date :** Date of sales data.    
**store :** Unique Store ID for each store.  
**item :** Unique Item ID for each item.  
**sales :** The number of items sold from a particular store on a given date.
