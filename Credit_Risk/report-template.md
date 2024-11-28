# Module 12 Report Template

## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

## Explain the purpose of the analysis.

    The Purpose of this analysis was to fit a Logistic Regression model using our training data. We then want to perform our model's performance by generating a confusion matrix and printing our classification report. Once we reviewed our classification report, we were then able to determine the precision of Healthy & High-Risk Loans. 


## Explain what financial information the data was on, and what you needed to predict.

The financial data came from a banks lending informaiton to their borrowers. We needed to prdict the loan status. 


## Provide basic information about the variables you were trying to predict (e.g., `value_counts`).

Using the the value_counts() method in Pandas. I was able to count the number of unique values in the specified column, which helped me understand the distribution of my target variable (loan_status).


## Describe the stages of the machine learning process you went through as part of this analysis.

I first defined the problem we were trying to solve. I then Gathered the necessary data from the CSV file provided. Once this data was retrieved,I Cleaned and preprocessed the data to make it suitable for my analysis. 

Exploratory Data Analysis (EDA) was performed to Analyze the data to uncover important patterns. Once I did this, I was able to Identify and select the most relevant features for my model.

The machine learning algorithm I decided to use was the Logistic Regression Model. Once my model was chosen, I Split the dataset into training and testing sets. I Trained the model using the training set and tuned hyperparameters to improve the models performance.

I then Assessed my model's performance using the testing set. Utilizing metrics such as accuracy and precision.


## Briefly touch on any methods you used (e.g., `LogisticRegression`, or any other algorithms).

I used the Logistic Regression Model. 

## Results

Using bulleted lists, describe the accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1:
    * Description of Model 1 Accuracy, Precision, and Recall scores.

Machine Learning Model 1 - Logistic Regression:

Accuracy score: 0.99     

Precision:
Class 0: 1.00
Class 1: 0.84

Recall:
Class 0: 0.99
Class 1: 0.94


## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. For example:



## Which one seems to perform best? How do you know it performs best?

The Logistic Regression model performs better at predicting healthy loans, over risky loans. Healthy loans had a precision of 100%. Risky Loans hada Precision of 84%.

## Does performance depend on the problem we are trying to solve? (For example, is it more important to predict the `1`'s, or predict the `0`'s? )

Yes, this performance depends on the problem we are trying to solve. In this case it is more important to predict Healthy Loans rather than High-Risk Loans. 
