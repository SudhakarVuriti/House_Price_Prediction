# House_Price_Prediction
# Project Name
> House-Price-Prediction
- Github link :(https://github.com/SudhakarVuriti/House_Price_Prediction.git)

## Table of Contents
*  Assignment part1
*  Business Goal
*  Data Defination
*  Data Understanding and Exploration
*  Handling null & missing values
*  EDA & Visualization(Outliers treatment)
*  Splitting the data into train and test sets
*  Scaling of numeric varaibles
*  Model Building and Evaluation
*  Ridge and Lasso Regression
*  Company requirements

## General Information
A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia. The data is provided in the CSV file below.

The company is looking at prospective properties to buy to enter the market. You are required to build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not.

The company wants to know:

1) Which variables are significant in predicting the price of a house, and

2) How well those variables describe the price of a house.

Also, determine the optimal value of lambda for ridge and lasso regression.

## Business Goal
You are required to model the price of houses with the available independent variables. This model will then be used by the management to understand how exactly the prices vary with the variables. They can accordingly manipulate the strategy of the firm and concentrate on areas that will yield high returns. Further, the model will be a good way for management to understand the pricing dynamics of a new market.

## Conclusions
*  Some of the variables are significant in predicting the price.
*  With using Ridge Regression and Lasso Regression variables describe the price of a house.

## Technologies Used
import numpy as np
import pandas as pd
import seaborn as sns
import matplotlib.pyplot as plt
%matplotlib inline
from sklearn import linear_model, metrics
from sklearn.linear_model import LinearRegression
from sklearn.linear_model import Ridge
from sklearn.linear_model import Lasso
from sklearn.model_selection import GridSearchCV
from sklearn.metrics import mean_squared_error, r2_score
import os
import warnings
warnings.filterwarnings('ignore')
pd.set_option('display.max_rows', 500)
pd.set_option('display.max_columns', 500)
pd.set_option('display.width', 1000)



## Contact
Created by Sudhakar Vuriti    (me.sudh.85@gmail.com)
