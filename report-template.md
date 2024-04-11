# Module 12 Report Template

## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

* Explain the purpose of the analysis.
    -The purpose of the analysis was to use various techniques to train and evaluate a model based on loan risk. I used a dataset of historical lending activity from a peer-to-peer lending services company to build a model that can identify the creditworthiness of borrowers.
        
* Explain what financial information the data was on, and what you needed to predict.
    -The financial information was in a csv file, and the loan status was need to predict
    
* Provide basic information about the variables you were trying to predict (e.g., `value_counts`).
    -I created the labels set(y) from the "loan status" column, and then I created the features (X) DataFrame from the remaining columns.

* Describe the stages of the machine learning process you went through as part of this analysis.
    -First I split the data into training and testing sets and then I created a logistic regression model with the original data
    
* Briefly touch on any methods you used (e.g., `LogisticRegression`, or any other algorithms).
    -I used a logistic regression model as my main method


## Results

Using bulleted lists, describe the accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1:
    * Description of Model 1 Accuracy, Precision, and Recall scores.
        -Accuracy: f1-score 0.99, support 19384
        -0 (healthy loan): precision 0.99, recall 1.00, f1-score 1.00, support 18719
        -1 (high-risk loan): precision 0.91, recall 0.85, f1-score 0.88, support 665

## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. For example:

* Which one seems to perform best? How do you know it performs best?
    - I used the logistic regression model only
    
* Does performance depend on the problem we are trying to solve? (For example, is it more important to predict the `1`'s, or predict the `0`'s? )
    -I believe it is very important to predict the '1's. Identifying the creditworthiness of borrowers is valuable information

If you do not recommend any of the models, please justify your reasoning.
