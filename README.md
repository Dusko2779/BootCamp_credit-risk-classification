# Module_20_Credit-Risk-Classification

### Instructions
The instructions for this Challenge are divided into the following subsections:

Split the Data into Training and Testing Sets

Create a Logistic Regression Model with the Original Data

Write a Credit Risk Analysis Report

### Split the Data into Training and Testing Sets
Open the starter code notebook and use it to complete the following steps:

Read the lending_data.csv data from the Resources folder into a Pandas DataFrame.

Create the labels set (y) from the “loan_status” column, and then create the features (X) DataFrame from the remaining columns.

![image](https://github.com/Dusko2779/BootCamp_credit-risk-classification/assets/134830906/a8258469-42b6-4e6c-8ac3-30204702115b)


Split the data into training and testing datasets by using train_test_split.

![image](https://github.com/Dusko2779/BootCamp_credit-risk-classification/assets/134830906/6fbaf3d5-fa63-4125-8043-f7c305b15d51)


### Create a Logistic Regression Model with the Original Data
Use your knowledge of logistic regression to complete the following steps:

Fit a logistic regression model by using the training data (X_train and y_train).

Save the predictions for the testing data labels by using the testing feature data (X_test) and the fitted model.

![image](https://github.com/Dusko2779/BootCamp_credit-risk-classification/assets/134830906/95a70284-a237-470e-add8-6ca6ab9bbca9)


Evaluate the model’s performance by doing the following:

![image](https://github.com/Dusko2779/BootCamp_credit-risk-classification/assets/134830906/40c62543-300d-48ab-a5c0-06dcb0392009)


Generate a confusion matrix.

Print the classification report.

### Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge.

The objective of this analysis is to develop and assess the effectiveness of a data model designed to forecast the creditworthiness of prospective borrowers using peer-to-peer lending. 

Balanced Accuracy Score of 95%: This score reflects the model's ability to simultaneously consider sensitivity (recall) and specificity in its predictions. In this case, the model achieved a high level of balance by correctly identifying both true positives (sensitivity) and true negatives (specificity), resulting in an overall balanced accuracy of 95%.

Precision Score of 92%: This indicates that 92% of the instances the model classified as positive were indeed correct. In other words, when the model made a positive prediction, it was accurate 92% of the time in identifying true positives.

Recall Score of 95%: The model's recall score of 95% signifies its precision in capturing true positive values out of all the actual positive instances. This means that the model successfully identified 95% of all the positive cases in the dataset, demonstrating its effectiveness in minimising false negatives.

I would highly reccomend for the adoption of this model for assessing borrower creditworthiness. The model's remarkable accuracy of over 95% in predicting the loan repayment outcomes positions it as a robust tool for decision-making in the lending industry. This level of accuracy can be leveraged to create a sound business risk profile, which is instrumental in managing and optimising capital flow for lenders, ultimately ensuring the sustainability of their operations and the potential for profitability.
