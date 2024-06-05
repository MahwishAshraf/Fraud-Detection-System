# Fraud-Detection-System
This fraud detection system works on a principle that the model identifies a certain transaction as fraud if the sender attempts to send a huge amount at a given time. Else, the transaction is considered not fraud. The model implements the decision tree algorithm to train the dataset after setting certain hyperparameters.

The dataset is simulated from a software called PaySim with mobile money transactions. [5] The dataset was acquired from Kaggle.com [6]

step - Describes a real-world unit of time. One step = one hour, totaling 744 steps (31 days of simulation)
type - CASH-IN, CASH-OUT, DEBIT, PAYMENT and TRANSFER
amount - Transaction amount in local currency
nameOrig - The customer who initiated the transaction
oldbalanceOrg - Pre-transaction balance of the sender
newbalanceOrig - Post-transaction balance of the sender
nameDest - Transaction recipient
oldbalanceDest - Pre-transaction balance of the recipient
newbalanceDest - Post-transaction balance of the recipient
isFraud - Transactions made by the fraudulent agents within the simulation. The behaviour of the fraudsters in this particular dataset can be described as hijacking the accounts of customers, transferring the funds to another account, and then withdrawing them.
isFlaggedFraud - A single transaction of more than 200.000 is considered illegal in this dataset

![image](https://github.com/MahwishAshraf/Fraud-Detection-System/assets/171836302/2b9c4b78-9117-4e45-a9d1-e116e8479734)
