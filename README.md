# Fraud-Detection-using-Unsupervised-Machine-learning

## Anomaly detection! Use unsupervised machine learning to identify credit card transactions that appear suspicious!

## Goal:
To detect fraudulent transactions from the given credit card transactions. 
Few questions to answer :
1. Your boss wants to identify those users that in your dataset never went above the monthly credit card limit (calendar month). The goal of this is to automatically increase their limit. Can you send him the list of Ids?
2. On the other hand, she wants you to implement an algorithm that as soon as a user goes above her monthly limit, it triggers an alert so that the user can be notiﬁed about that.We assume here that at the beginning of the new month, user total money spent gets reset to zero (i.e. she pays the card fully at the end of each month). Build a function that for each day, returns a list of users who went above their credit card monthly limit on that day.
3. Build a model that can help detect these transactions!

## Data :
**Transactions Table** :

Credit_card : denotes the account number of the credit card

Date : date when the transaction was made

Transaction_dollar_amount : the amount that was transacted from the account

Lat: latitude of the place where the transaction was made

long : longitude of the place where the transaction was made

**cc_info Table**:

credit_card:denotes the account number of the credit card

city: city

state: state

zipcode: zipcode of the place

credit_card_limit : montly limit on the credit card
