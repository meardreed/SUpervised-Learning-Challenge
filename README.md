# Supervised-Learning-Challenge

An overview of the analysis: 

We are using various logistic regression to train and evaluate a model based on loan risk. We are analyzing a dataset of historical lending activity from a peer-to-peer lending services company to build a model that can identify the creditworthiness of borrowers where 0 is a healthy loan and 1 is a risky loan. We split the data into 75% training data and 25% testing data with a random state of 1.

The results:

Using The logistic regression model, the precision for predicting healthy loans is at 100%, and 85% for risky loans. The model is better at predicting healthy loans than risky ones.
Recall is at 99% for healthy loans and 91% for risky ones. Again the model shows performing best to predict false positives than false negatives. 
For F1 scores, healthy loans have an ideal score of 100%, followed by high risk loans at a score of 88%.

The logistic regression model, fit with oversampled data retained the level of precision, recall and f1-score of the original model for the healthy loans, 100%, 99% and 100% respectively.
We are noticing overall improvement on the results for the risky loans. However, the precision level lost 1 point at 84%. The recall is at 99% and f1-score at 91% which increased from previous fit.

A summary: Summarize the results from the machine learning model. Include your justification for recommending the model for use by the company. If you don’t recommend the model, justify your reasoning.
