# ITEM-DEMAND-FORECASTING

## Problem Statement
Demand forecasts are fundamental to plan and deliver products and services.
Accurate forecasting of demand can help the manufacturers to maintain appropriate 
stock which results in reduction in loss due to product not being sold and also reduces 
the opportunity cost (i.e. higher demand but less availability => opportunity lost).
Despite such relevance, manufacturers have difficulty choosing which 
forecast model is the best for their use case. In this project, 
historical sales data corresponding to multiple(25) items sold in 10 stores are provided 
and participants are expected to come up with a best model to predict the future demand for 
products which results in maximum profit for the manufacturer. 
Predict the demand for the next 3 months at the item level (i.e. all the stores combined).


## Data
The historical sales data is available as :
Train data as-->**item**
Test data as--> **sales_demans_data.csv**

The item,store and sales details are provided at the daily level
for a 4 year span

## Here's what is covered
1.IMPORTING LIBRARIES AND DATA.  
2.EXPLORATORY DATA ANALYSIS.  
3.FEATURE ENGINEERING AND DATA PRE-PROCESSING  
- Date Features  
- Random Noise  
- Lag/Shifted Features  
- Rolling Mean Features  
- Exponentially Weighted Mean Features  
- One hot encoding  
- Converting Sales to log(1+sales)  

4.MODEL
- Time Based Validation sets
- LightGBM Model
- Feature Importance
- Ligth Model  

5.SUBMISSION
