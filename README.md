# DataScienceCapstoneOne
### Paysim Mobile Money Transfer Fraud Detection Service

Paysim is a mobile money transfer service provider that is currently serving 14 countries all around the world. A mobile money transfer is fast, easy, and secure. A sender sends money from their bank account, credit/debit card, or own money account to another mobile money account. This technology is a multi-faceted way users can receive, store, spend and send money from the account on their mobile device. Unfortunately, due to the ease of the technology, sometimes frauds occur even operating under financial regulations.


### 1. Data

There are problems where a class imbalance in a dataset like our current fraudulent transactions dataset. For example, the vast majority will be in the "Non-Fraud" class, and a tiny minority will be in the "Fraud" class. The Paysim dataset is based on a sample of actual transactions extracted from one month of financial logs from a mobile money service implemented in an African country. This dataset contains 6,362,620 rows by 11 columns with 8,213 labeled as a "Fraud."

> * [8a.nu website](https://www.8a.nu/)







Data Info:

In this case 1 step is 1 hour of time. Total steps 744 (30 days simulation).

type - CASH-IN, CASH-OUT, DEBIT, PAYMENT and TRANSFER.

amount - amount of the transaction in local currency.

nameOrig - customer who started the transaction

oldbalanceOrg - initial balance before the transaction

newbalanceOrig - new balance after the transaction

nameDest - customer who is the recipient of the transaction

oldbalanceDest - initial balance recipient before the transaction. Note that there is not information for customers that start with M (Merchants).

newbalanceDest - new balance recipient after the transaction. Note that there is not information for customers that start with M (Merchants).

isFraud - This is the transactions made by the fraudulent agents inside the simulation. In this specific dataset the fraudulent behavior of the agents aims to profit by taking control or customers accounts and try to empty the funds by transferring to another account and then cashing out of the system.

isFlaggedFraud - The business model aims to control massive transfers from one account to another and flags illegal attempts. An illegal attempt in this dataset is an attempt to transfer more than 200.000 in a single transaction.


Acknowledgement:
https://www.kaggle.com/ealaxi/paysim1
