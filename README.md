## Liability-Account-Monitoring-for-Money-Mules
## Problem Statement

Bank A enables customers to open savings accounts entirely online, enhancing customer convenience and experience. However, this online process has been exploited by fraudsters (referred to as mules) who open accounts solely to deceive others. These mules use social engineering to convince unsuspecting individuals to transfer money to their Bank A accounts.

To combat this misuse, Bank A aims to develop an automated transaction monitoring framework using Machine Learning algorithms. The objective is to proactively detect and prevent fraudulent activities in customers' savings accounts.The objective of the project is to use machine learning algorithms to predict the probability that a given account is a mule based on various account-level attributes, demographic information, transaction history, and other relevant factors. 

**Overview of the Approach:**
1.	Understanding Data and EDA (Exploratory Data Analysis) 
2.	Preprocessing
3.	Feature selection
4.	Dimensionality Reduction 
5.	Model Selection and Training
6.	Prediction on the Validation Data

##**DATA DESCRIPTION**

The development data contains 1,00,000 savings account details with 178 feature columns consisting of-
Primary key – The index of the accounts
Target – 0 or 1 accounts identified as mules have target=1.
Account level attributes like account opening date
Demographic attributes of the customer (e.g. income, occupation, city tier etc.) 
Transaction history of customer ( includes credits / debits of specific types over a period of time ) 
Other attributes like product holding with the Bank, app / web logins etc. 
Some variable names have been provided. For other variables, demographic attributes start with “demog_”, transaction attributes start with “txn_” and the rest start with “others_”.
The validation data consists of 50,000 savings account details with the same set of input variables but without “Target”.
The feature columns contained 147 columns with float values, 18 columns with int values, 12 with categorical or object entries and a datetime column.

