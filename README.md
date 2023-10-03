# Credit Risk Classification

**Overview:** The purpose of this analysis is to evaluate the accuracy of a model that predicts whether or not a potential borrower is a healthy or a high risk. 
  
**Results:** 
  - *Accuracy Score:* 94.5% 
  - *Precision Score:* 94%
  - *Recall Score:* 94%
  
**Summary:** I suggest employing this model for assessing borrowers' creditworthiness due to its impressive track record of achieving over 95% accuracy in predicting loan repayment outcomes. This high level of accuracy can seamlessly integrate into a business risk profile, guaranteeing a steady capital stream for lenders, ultimately enabling them to sustain their operations and generate profits.

**INSTRUCTIONS:**

Open the starter code notebook and use it to complete the following steps:

  - Read the lending_data.csv data from the Resources folder into a Pandas DataFrame.
  
  - Create the labels set (y) from the “loan_status” column, and then create the features (X) DataFrame from the remaining columns.
  
  ***NOTE:*** A value of 0 in the “loan_status” column means that the loan is healthy. A value of 1 means that the loan has a high risk of defaulting. 
  
  - Split the data into training and testing datasets by using train_test_split.
  
  - Create a Logistic Regression Model with the Original Data
  
Use your knowledge of logistic regression to complete the following steps:
  
  - Fit a logistic regression model by using the training data (X_train and y_train).
  
  - Save the predictions for the testing data labels by using the testing feature data (X_test) and the fitted model.
  
Evaluate the model’s performance by doing the following:

  - Generate a confusion matrix.
  
  - Print the classification report.
  
  - Answer the following question: How well does the logistic regression model predict both the 0 (healthy loan) and 1 (high-risk loan) labels?
