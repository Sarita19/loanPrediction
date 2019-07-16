
# loanPrediction
 
The Client, a financial institution, is looking for a better approach to identify credit defaulters.
The main idea here is to predict which customers are likely to default on their loan payments after receiving their loan approval? 

The predictive model built here is built in Python

For the Data reading, I got my data from 3 datasets. These datasets were bigger than 25MB hence was not possible for me to upload the same.

Below is a description of the 3 datasets:-
-Borrower Information: Information on the clients’ customers
-Loan Classification Information: Information on the loan itself
-Loan Payment Information: Information on the payments on the loans.


I have attached the Data Dictionary “Feature Explanations.xlsx”. This document explains the features of all the datasets present into separate files


To give a brief of what I have done:-

1. I have merged the datasets
2. I have looked for null values more than 80% in a particular column and removed them.
3. I have removed the variables which are highly co-related to each other
4. Before moving into building prediction models, 
    - I have used one-hot encoding for categorical variables
    - I have used Box-cox transformation for numerical variables and normalised them
5. I have built prediction models using 3 algorithms:-
   - Logistic Regression
   - Decision Tree Classifier
   - Naive Bayes Classifier
    

