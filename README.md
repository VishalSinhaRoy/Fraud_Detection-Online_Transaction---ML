# Fraud_Detection-Online_Transaction - ML

![image](https://github.com/VishalSinhaRoy/Fraud_Detection-Online_Transaction-ML/assets/162811130/28ea842a-f9d8-4353-9c73-766c5f7a3d48)

**Objective:**

The most widely used form of payment in the world today is online. But as the number of online payments rises, so does the incidence of payment fraud. This notebook aims to train machine learning models to distinguish between legitimate and fraudulent payments. The dataset was gathered from Kaggle, which offers past fraud data that can be utilized to identify fraudulent online payment activities.

**Dataset Variables:**

The dataset consists of 10 variables:

step: represents a unit of time where 1 step equals 1 hour

type: type of online transaction

amount: the amount of the transaction

nameOrig: customer starting the transaction

oldbalanceOrg: balance before the transaction

newbalanceOrig: balance after the transaction

nameDest: recipient of the transaction

oldbalanceDest: initial balance of recipient before the transaction

newbalanceDest: the new balance of recipient after the transaction

isFraud: fraud transaction

**Content:**

PaySim simulates mobile money transactions based on a sample of real transactions extracted from one month of financial logs from a mobile money service implemented in an African country. The original logs were provided by a multinational company, who is the provider of the mobile financial service which is currently running in more than 14 countries all around the world.

This synthetic dataset is scaled down 1/4 of the original dataset and it is created just for Kaggle.

**Conclusion:**

The Xg-Boost model has emerged as the top performer in identifying fraudulent payments, achieving the highest score among all models tested. It boasts an impressive AUC score of 0.998, which indicates exceptional capability in distinguishing between fraudulent and non-fraudulent transactions.
