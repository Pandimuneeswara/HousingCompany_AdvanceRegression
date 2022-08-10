# Advanced Regression - Surprise Housing Company
A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia. The data is provided in the CSV file below.

The company is looking at prospective properties to buy to enter the market. You are required to build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not.

The company wants to know:
    Which variables are significant in predicting the price of a house, and
    How well those variables describe the price of a house.

## Table of Contents
* Data Understanding
* Data Cleaning and Imputing
* Data analysis
* Build the model
* Conclusion

## General Information
- Past few years sales data set used for this analysis
- Few features were unique values and not having much impact those were dropped
- Built the model using lasso and Ridge regression to predict the salesPrice

## Conclusions
- The optimal value of alpha for ridge and lasso model based on the model built are;
    a.	Lasso: 500
    b.	Ridge: 100
- The important predictor variables are;
    MSSubClass, LotArea, OverallQual, OverallCond, TotalBsmtSF, BsmtFullBath, LowQualFinSF, BsmtHalfBath, YearBuilt_2001-2010, HeatingQC, SaleType, SaleCondition, GarageCond, Exterior1st, Neighborhood, Fireplaces, Condition1, RoofStyle,  Exterior2nd_Stone, KitchenQual, Functional_Mod, GarageType_BuiltIn, Heating_Wall, Heating
- Lasso will works better for this analysis

## Technologies Used
- library - pandas
- library - matplotlib
- library - seaborn
- library - sklearn

## Acknowledgements
Thanks to upgrad for letting us work with the real world datasets.

## Contact
Created by [@Pandimuneeswara] - feel free to contact me!
