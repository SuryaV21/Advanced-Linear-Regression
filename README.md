# Linear Regression Project 

## Table of Contents
* [Problem Statement](#problem-statement)
* [Technologies Used](#technologies-used)
* [Data Cleaning](#data-cleaning)
* [Analysis Flow](#analysis-flow)
* [Model Creation and Analysis](#Model_Creation_and_Analysis)
* [Conclusions](#conclusions)

<!-- You can include any other section that is pertinent to your problem -->

## Problem Statement
-You are required to model the price of houses with the available independent variables. This model will then be used by the management to understand how exactly the prices vary with the variables. They can accordingly manipulate the strategy of the firm and concentrate on areas that will yield high returns. Further, the model will be a good way for management to understand the pricing dynamics of a new market.

## Technologies Used
- Pandas
- numpy
- Seaborn
- Matplotlib
- Sklearn
- stats
- warnings



## Data Cleaning
- Dataset contains 1460 rows and 160 columns without any null values
- we have column with more than 40 percent and upto 99.5 percent. Dropping columns which are having more htan 40%
- 'YearBuilt','YearRemodAdd','GarageYrBlt','YrSold' are unwanted columns so dropping them
- creating the dummy variables for the respective categorical variables

## Analysis Flow
- Univariate analysis was performed on categorical and numerical variables respectively
- Bivariate analysis was performed on numerical and categorical data respectively
- By looking at the pair plot Temp and atemp variable are highly correlated and directly proportional
- We applied standard scalar  standardization technique to standardize the data

## Model Creation and Analysis
- Divide the data into train and test using train_test_split function. Train will have 70% data and test will have 30% data
- Using SKLearn linear regression model we develop the model to verify the variable 
- we are using Lasso and Ridge regression and develop the models


## Conclusions
## Lasso:
- Training model accuracy is 89.8% 
- Test data model accuracy is 92.4%
- Important Variables:
    - SaleCondition_Partial
    - SaleCondition_Others
    - SaleCondition_Normal
    - GarageFinish_Unf
    - GarageFinish_RFn 
## Ridge:
- Training model accuracy is 90.1% 
- Test data model accuracy is 92.1%
- Important Variables:
    - SaleCondition_Partial
    - SaleCondition_Others
    - SaleCondition_Normal
    - GarageFinish_Unf
    - GarageFinish_RFn 



## Contact
Created by [@https://github.com/SuryaV21]
 - feel free to contact me!
