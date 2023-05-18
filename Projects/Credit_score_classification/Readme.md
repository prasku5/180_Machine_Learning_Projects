Original Author: https://www.linkedin.com/company/thecleverprogrammer/?original_referer=https%3A%2F%2Fthecleverprogrammer.com%2F

Banks and credit card companies calculate your credit score to determine your creditworthiness. It helps banks and credit card companies immediately to issue loans to customers with good creditworthiness. Today banks and credit card companies use Machine Learning algorithms to classify all the customers in their database based on their credit history. So, if you want to learn how to use Machine Learning for credit score classification, this article is for you. In this article, I will take you through the task of credit score classification with Machine Learning using Python.

Credit Score Classification

There are three credit scores that banks and credit card companies use to label their customers:

Good

Standard

Poor


A person with a good credit score will get loans from any bank and financial institution. For the task of Credit Score Classification, we need a labelled dataset with credit scores.

I found an ideal dataset for this task labelled according to the credit history of credit card customers. You can download the dataset here - https://statso.io/credit-score-classification-case-study/

Credit Score Classification: Case Study

The credit score of a person determines the creditworthiness of the person. It helps financial companies determine if you can repay the loan or credit you are applying for.

Here is a dataset based on the credit score classification submitted by Rohan Paris on Kaggle. Below are all the features in the dataset:

ID: Unique ID of the record

Customer_ID: Unique ID of the customer

Month: Month of the year

Name: The name of the person

Age: The age of the person

SSN: Social Security Number of the person

Occupation: The occupation of the person

Annual_Income: The Annual Income of the person

Monthly_Inhand_Salary: Monthly in-hand salary of the person

Num_Bank_Accounts: The number of bank accounts of the person

Num_Credit_Card: Number of credit cards the person is having

Interest_Rate: The interest rate on the credit card of the person

Num_of_Loan: The number of loans taken by the person from the bank

Type_of_Loan: The types of loans taken by the person from the bank

Delay_from_due_date: The average number of days delayed by the person from the date of payment

Num_of_Delayed_Payment: Number of payments delayed by the person

Changed_Credit_Card: The percentage change in the credit card limit of the person

Num_Credit_Inquiries: The number of credit card inquiries by the person

Credit_Mix: Classification of Credit Mix of the customer

Outstanding_Debt: The outstanding balance of the person

Credit_Utilization_Ratio: The credit utilization ratio of the credit card of the customer

Credit_History_Age: The age of the credit history of the person

Payment_of_Min_Amount: Yes if the person paid the minimum amount to be paid only, otherwise no.

Total_EMI_per_month: The total EMI per month of the person

Amount_invested_monthly: The monthly amount invested by the person

Payment_Behaviour: The payment behaviour of the person

Monthly_Balance: The monthly balance left in the account of the person

Credit_Score: The credit score of the person


The Credit_Score column is the target variable in this problem. You are required to find relationships based on how banks classify credit scores and train a model to classify the credit score of a person.