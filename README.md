# Project Name
Prediction of Housing pricess using Regularisation Methogs(Lasso & Ridge)


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia. The data is provided in the CSV file below.

## Objective
- Which variables are significant in predicting the price of a house, and
- How well those variables describe the price of a house.
- Also, determine the optimal value of lambda for ridge and lasso regression.

 

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- The optimum alpha for Ridge is 5, and the optimum alpha for Lasso is 0.0001.

- Below are the important features from Ridge regression
[('OverallQual', 0.113), ('GrLivArea', 0.095), ('Neighborhood_NoRidge', 0.076), ('2ndFlrSF', 0.071), ('GarageArea', 0.058), ('TotalBsmtSF', 0.053), ('FullBath', 0.052), ('BsmtFullBath', 0.046), ('Neighborhood_NridgHt', 0.044), ('Neighborhood_Crawfor', 0.041)]

- Below are the important features from Lasso regression
[('GrLivArea', 0.299), ('OverallQual', 0.146), ('Neighborhood_NoRidge', 0.082), ('YearBuilt_Age', -0.076), ('KitchenAbvGr', -0.065), ('OverallCond', 0.055), ('LotArea', 0.054), ('KitchenQual_TA', -0.051), ('BsmtFullBath', 0.048), ('Neighborhood_NridgHt', 0.047)]

- Ridge regression at Optimal ALPHA: 5.0 
R2 SCORE: 0.8440% MSE: 0.0
Lasso Regression at Optimal ALPHA: 0.0001 
R2 SCORE: 0.8568% MSE: 0.0

Lasso Provides a better R2 score and Mean square error. So I will choose Lasso Regression model for predicting the Housing prices.



<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- numpy
- pandas
- matplotlib
- seaborn
- sklearn


## Acknowledgements


## Contact
Created by [@venkatjonnadula] - feel free to contact me!
