# DataScienceCapstoneOne
### Paysim Mobile Money Transfer Fraud Detection Service

Paysim is a mobile money transfer service provider that is currently serving 14 countries all around the world. A mobile money transfer is fast, easy, and secure. A sender sends money from their bank account, credit/debit card, or own money account to another mobile money account. This technology is a multi-faceted way users can receive, store, spend and send money from the account on their mobile device. Unfortunately, due to the ease of the technology, sometimes frauds occur even operating under financial regulations.


### 1. Data

There are problems where a class imbalance in a dataset like our current fraudulent transactions dataset. For example, the vast majority will be in the "Non-Fraud" class, and a tiny minority will be in the "Fraud" class. The Paysim dataset is based on a sample of actual transactions extracted from one month of financial logs from a mobile money service implemented in an African country. This dataset contains 6,362,620 rows by 11 columns with 8,213 labeled as a "Fraud."

> * [Kaggle](https://www.kaggle.com/ealaxi/paysim1)
> * [Data Import](https://github.com/Erik1120/DataScienceCapstoneOne/blob/main/Notebook/data_wrangling.ipynb)

### 2. Method

Logistic and Classification are two types of algorithms for binary classification problems. Also, within Classification, there are bagging or boosting techniques.

1. **Bagging:** is to reduce the variance of the decision tree classifier by averaging predictions from all the tress. Also, it reduces the over-fitting of the model and handles higher dimensionality data very well. 
2. **Boosting:**  is used to create a collection of predictors by learners who are learned sequentially by analyzing data for errors. The purpose of this process is to improve the accuracy from prior tress by increasing the weight of wrongly classified items so that they can more likely be classified correctly on the next iteration. 

### 3. Data Cleaning

> * [Data Cleaning Notebook](https://github.com/Erik1120/DataScienceCapstoneOne/blob/main/Notebook/data_wrangling_EDA.ipynb)

1. Fortunately, Paysim data was very clean and did not require any imputing of Data, including removing rows from the dataset. The biggest changes were to rename feature names for clarity, and two additional fields were added using existing fields to derive two new features. ("diffBalanceOrig" & "diffBalanceDest")

### 4. EDA

> * [EDA Notebook](https://github.com/Erik1120/DataScienceCapstoneOne/blob/main/Notebook/data_engineering.ipynb)


