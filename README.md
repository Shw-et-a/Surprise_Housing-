# Surprise_Housing
> A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price.


## Table of Contents
* [General Info](#general-information)
* [Business Goal](#Business-Goal)
* [Conclusions](#conclusions)
* [Contact](#Contact)




## General Information
Surprise housing dataset using lasso and ridge regression

A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia. 

The company is looking at prospective properties to buy to enter the market. You are required to build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not.

The company wants to know:
* Which variables are significant in predicting the price of a house
* How well those variables describe the price of a house.

Also, determine the optimal value of lambda for ridge and lasso regression.


## Business-Goal
You are required to model the price of houses with the available independent variables. This model will then be used by the management to understand how exactly the prices vary with the variables. They can accordingly manipulate the strategy of the firm and concentrate on areas that will yield high returns. Further, the model will be a good way for management to understand the pricing dynamics of a new market.


## Conclusions
➡ Ridge : train - 90.9, Test - 87.4

➡ Lasso : train - 89.8, Test - 86.4

We have a decent score for both the regressions.
Significant Variables in Ridge are :
⚫ 'SaleCondition_Partial', 0.143

⚫'SaleCondition_Others', 0.105

⚫'SaleCondition_Normal', 0.099

⚫'GarageFinish_Unf', 0.094

⚫'GarageFinish_RFn', 0.092

Significant Variables in Lasso are :
⚫ 'SaleCondition_Partial', 0.198

⚫'SaleCondition_Others',0.12

⚫'SaleCondition_Normal',0.098

⚫'GarageFinish_Unf', 0.084

⚫'GarageFinish_RFn', 0.079

Optimum values¶
➡ Optimum Value of lamda for Ridge :10

➡Optimum Value of lamda for Lasso : 0.001

These variables are directly proportional to each other.
Feature selection allows us to choose lasso regression in this case.

## Contact
Created by [@Shw-et-a] - feel free to contact me!

