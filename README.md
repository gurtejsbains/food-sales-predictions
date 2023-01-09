<p align = "center"> 
  <img src = "https://github.com/gurtejsbains/sales-predictions/blob/1f2624e8eb600e0e1c7670cdf89dbeb4e1bbc2f2/Stock%20Image%20Sales%20Prediction.png">
</p>

# Predicting Grocery Sales
## Predicting grocery sales for BigMart grocery chain 

**Author**: Gurtej Bains 
**Data Source**: https://datahack.analyticsvidhya.com/contest/practice-problem-big-mart-sales-iii/ 

### Business Problem:
1. Help the retailer understand the properties of products and outlets that play crucial roles in predicting sales.
2. Sales prediction by building two different models and deciding which one to recommend.

### Data Dictionary:
<p align = "center"> 
  <img src = "https://github.com/gurtejsbains/sales-predictions/blob/1f2624e8eb600e0e1c7670cdf89dbeb4e1bbc2f2/Data%20Dictionary%20for%20Grocery%20Store%20Sales%20Prediction%20Data.png">
</p>

## Overview
The dataset contain data for 10 stores and more than 1,500 products. Stores opened between 1985 and 2009. The data was collected in 2013 and has 12 columns with 8,523 records. 
Some important call outs: 
1. Average outlet sales for Outlet 27 is the highest. 
<p align = "center"> 
  <img src = "https://github.com/gurtejsbains/food-sales-predictions/blob/d6d6e8fa5db851b2734aa983c5358759af8e09bb/outlet%20identifier.png">
</p>  

2. Average outlet sales for Super Market Type 3 is the highest.
<p align = "center"> 
  <img src = "https://github.com/gurtejsbains/food-sales-predictions/blob/73bf90ca980254b00fafb014fb9a3e506539ca37/outlet%20type.png">
</p>  

## Methods
A Multiple Regression Model and two Decision Tree Models were used to predict sales. Tuned Decision Tree Model performed best in predicting sales with r square of the test segment at 59%. 

## Results
The Tuned Decision Tree Model is the best model. It is stable as does not have high bias or high varaince. MAE and RMSE is also good as sales predictions are off by approximatly Rs. 1,000

## Recomendations
Add more data and build a more sophisticated model as R square can be improved 
