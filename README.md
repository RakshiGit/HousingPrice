# HousingPrice

## Table of Contents
* [General Info]
A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia.

The company is looking at prospective properties to buy to enter the market. You are required to build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not.


The company wants to know:

1) Which variables are significant in predicting the price of a house, and

2) How well those variables describe the price of a house.

* [Technologies Used]
Python, Jupyter

<!-- You can include any other section that is pertinent to your problem -->

## General Information
A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia.

The company is looking at prospective properties to buy to enter the market. You are required to build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not.


The company wants to know:

1) Which variables are significant in predicting the price of a house, and

2) How well those variables describe the price of a house.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
1) We see high positive corelation between following independent variables: Garagearea-GarageCars, GarageYrbuilt-YearBuilt, TotrmsabvGrd-GrLivArea, TotalBsmtSF-1stFlrSF
2) Sale price is positively corelated with GrLivArea, GarageArea, GarageCars, TotalBSMTSF etc.
3) Sale price is mild negatively corelated with KitchenAbvGr, EnclosedPorch
4) KitchenQuality, Partial salecondition, New Saletype, Builtin garage have positive corelation with Sale price.
5) Building type doesn't seem to have much effect on Sale price
6) Ridge regression has shown R2 score of 90% in Train data and 85% in test data. 
7) Lasso rrgression is showing R2 score of 903% in train but 83% in test data.
8) Looking at the R2 square of train and test data, Ridge regression turns out to be the best model as the difference between the R2 scores of test and train set is small.
9) Looking at the column Ridge in table above,Sale prices depends upon Above grade (ground) living area, First and 2nd Floor square feet, Garage Area, Full bath, Total rooms etcs.
10) Also houses with OverallQual of 8 or above and close to Northridge and Northridge Heights affect the sale price.



## Acknowledgements
-- This project has been performed as part of Upgrad learning program

## Contact
Created by [@RakshiGit] - feel free to contact me!
