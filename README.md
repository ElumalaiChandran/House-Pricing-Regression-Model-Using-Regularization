House Pricing Regression Model Using Regularization
Problem Statement :

Surprise Housing

A US-based housing company has decided to enter the Australian market.
It uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price.
Requirement :

The company is looking at prospective properties to buy to enter the market.
We are required to build a regression model using regularization in order to predict the actual value of the prospective properties
and decide whether to invest in them or not.
Objective:
The company wants to know:

Which variables are significant in predicting the price of a house.
How well those variables describe the price of a house.
House Price Prediction - Solution
The solution is divided into the following sections:

Data understanding and exploration.
Data cleaning.
Data preparation.
Model building and evaluation.
Data understanding and exploration
Data Understanding and exploring the data is very important steps in any of the Predictive models.
Exploring the data's and get to the details like
-Row Count
-Column Count
-Check for Outliers any

Check for missing/null values
-Duplicates
-Perform EDA and get to know correlation of the variables to the independent variables
-Thus, while building the model, we'll have to pay attention to multicollinearity (especially linear models, such as linear and logistic regression, suffer more from multicollinear).
Data cleaning
Missing Values Imputation:
Real Missing Values - Deal with imputation Techniques like Mean/Median/Mode etc.,
Meaningful Missing Values - You cant drop or deal will with any imputation techniques, because missing values has some meaning in it. Here Domain knowledge required to understand these kind of Missing Values.
Data preparation
Check For Skewness of the data
Convert all Categorical columns into numerical based on the requirements
Scaling the variables.
Model building and evaluation
Data Split for Train & Test
-Apply linear Regression and get R2Score
-Apply Lasso Regression and find the optimal Alpha Values and Predict the top variables
-Apply Ridge Regression and find the optimal Alpha Values and Predict the top variables
Predict Test scores and Evaluation
-From the Model Summary Report we can Say that Lasso Regression is ideal choice for this model, because both Test and Train are equal and we got optimal Alpha is 0.001
-Listed below is the Top 10 Variable that significant variables to predict the House Pricing
-Therefore, The Target variables varies based on the Top 10 features coefficient .
