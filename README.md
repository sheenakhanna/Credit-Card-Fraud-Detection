# Credit-Card-Fraud-Detection

Dataset used : https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud
This dataset presents transactions that occurred in two days, where we have 492 frauds out of 2.84L transactions. The fraud transactions account for 0.172% of all transactions.
Due to confidentiality issues, the original features and more background information about the data was not provided. Features V1, V2, … V28 are the principal components  the only features which were not transformed are 'Time' and 'Amount'. 
Feature 'Time' contains the seconds elapsed between each transaction and the first transaction in the dataset. 
The feature 'Amount' is the transaction Amount.
Feature 'Class' is the response variable and it takes value 1 in case of fraud and 0 if transaction is legit.

Started out with analysing the data the values and as the dataset is highly unbalanced worked on making it a better dataset by undersampling. Since this is a binary  classification problem  with 2 classes as fraud or legit, I applied 4 supervised machine learning algorithms and got the best accuracy of 94.5% on test data using Logistic Regression model
