# Telecom-churn-prediction-Project
## Objective:
The objective is to predict to a high accuracy, in advance the customers who may attrite from the existing service provider in near future.

Analyze using standard SEMMA (Sample, Explore, Modify, Model and Assess) approach and choose the best model based on the lowest  Dollar ($) cost of misclassification.

Recommend product strategies to business team based on  analysis of product offerings that will help in retaining the customer based on available data.

## Dataset:
Data consists of 7043 fictional customers who belong to various demographics (single; with dependents; senior citizen) and subscribe to different products offerings (internet service; phone line; streaming TV; streaming movies; online security) from a telecom company located in one of the US states.

Independent variables: 17 Categorical and 3 Continuous

Dependent Target variable: “Churn”

Churn Rate (Baseline) is 26.5%
## Model Summary:
Multiple models within each type are built and Optimal model is  selected for comparison

1.) Logistic Regression: 12 significant variables are selected by forward exhaustive method.

2.) Decision Tree: Optimal tree had 18 splits.

3.) Bootstrap forest: Optimal model had 10 variables and 15 trees.

4.) Boosted Tree:  Optimal model had 10 variables and 15 layers.

5.) Neural Networks: 12 input variables identified by Regression models with 2 activation layers of TanH(3).

6.) KNN model: 12 input variables with K values from 1 to 30; the optimal model had K as 27.

7.) Naive Bayes: 16 input variables (14 categorical & 2 nominal). From prediction profiler, 

             a.)Increase in “Tenure”, reduction in “Churn” 
             
             b.)Increase in “Monthly charges”, increase in “Churn”
             
8.) Ensemble of “Neural Network” & “Naive Bayes” has highest “Sensitivity”.
## Conclusion:
1.) Significant variables impacting “Churn”:  Type & Tenure of Contract

2.) Churn is observed to be high for customers:

   a.) Without dependents
   
   b.) With high cost Phone Services
   
   c.) Having single line service (no combo services)
   
3.) Recommendation to Business Team for retaining Customer

   a.) Targeted Customer Promotion
   
   b.) Promote Long Term contract
   
   c.) Market more products as Combo (multi) service offering


Thank You

