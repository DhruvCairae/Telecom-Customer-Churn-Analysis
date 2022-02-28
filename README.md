# Telecom-Customer-Churn-Analysis
The data selected for this project is a data set from kaggle called “Telco Customer Churn”. It is originally an IBM sample data set. 
The data is concerned with whether customers are retained, this variable is a dummy variable called churn. 
Churn takes a value of 1 if the customer churned (left) or 0 if the customer is retained. The data set contains 19 more predictor varibles and a 
identification column. The predictor varibles fall into three broad categories: services each customer has, customer account information, and customer demographics.
Developing a model to predict whether a customer leaves the company or not. First we split the data into training and testing sets. 
Then we fit XGBoost to the training set and use K-fold cross validation to validate our predicted results.
