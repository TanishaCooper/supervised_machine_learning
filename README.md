# Supervised Machine Learning: Predicting Credit Risk

![Google Images](./Images/clustering.jpg)

## Description
Build a machine learning model that attempts to predict whether a loan will be approved or not using Logistic Regression model and Random Forest Classifier.

## Background
Lending services companies allow individual investors to partially fund personal loans as well as buy and sell notes backing the loans on a secondary market. 

The goal is to use this data to create machine learning modules to classify the risk level of given loans. Specifically, we will be comparing the Logistic Regression model and Random Forest Classifer.

## Process

1. Use [Lending Data](./Resources/lending_data.csv)
2. Import data using Pandas
3. Create and compare two models on the data: 
    - <strong>Logistic Regression vs Random Forest Classifier</strong>
4. Make a prediction and provide justification as to which model I think will perform better 

## Prediction
1. Prediction
    - <strong><em>Random Forest Classifier</em></strong>
2. Justification
    - Due to known category of "credit risk vs not credit risk", random forest classifier would be better to predict whether a loan will be approved or not. Individual Random Forest Classifier decision trees with random selection can capture more complicated feature patterns and deliver the best accuracy. Logistic Regression model would better predict numerical range/data ushc as weather forecasting, market forecasting, estimating life expectancy, advertising popularity prediction, etc..

## Outcome Prediction
1. Which model performed better? 
    - Random Forest Classifier

2. How does that compare to your prediction? 
    - I chose Random Forest Classifer, as well. "A random forest is a meta estimator that fits a number of decision tree classifiers on various sub-samples of the dataset and uses averaging to improve the predictive accuracy and control over-fitting (scikit-learn, 2007-2022)." Random forest classifier models is good due to high performance and less need for interpretation. The decision tree within the Random Forest Classifier split the data into smaller data groups based on features such as debt-to-income ratio, loan amount, etc..

