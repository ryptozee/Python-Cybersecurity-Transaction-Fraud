# Transaction Frauds
> This is inspired by JP Morgan Cybersecurity Study Case via [Forage](https://www.theforage.com/simulations/jpmorgan/cybersecurity-0acj). The dataset named 'transaction.csv can be found in [Kaggle](https://www.kaggle.com/ealaxi/paysim1/version/2).

## Scenario 
You are a cybersecurity analyst at the one of the largest financial companies in the world. Your job is to analyze a large dataset of fraud in Financial Payment Services. 
The dataset has five types of transactions:
* CASH-IN is any deposit.
* CASH-OUT is any withdrawal.
* DEBIT is a specific type of withdrawal in which the money is sent to the user’s bank account.
* PAYMENT is the purchase of goods or services.
* TRANSFER involves moving money from one user’s account to another user’s account.

## Process
1. Read the dataset (`transactions.csv`) as a Pandas dataframe. Note that the first row of the CSV contains the column names.
2. Return the column names as a list from the dataframe.
3. Return the first k rows from the dataframe.
4. Return a random sample of k rows from the dataframe.
5. Return the Origin account balance delta v. Destination account balance delta scatter plot for Cash Out transactions (Source Delta & Delta Destination).
6. Return Fraud transactions that are flagged as frauds and how many of them are real frauds. 

## Implementation
* Transaction types bar chart:
  
![image](https://github.com/user-attachments/assets/1f3e99f4-1e25-490c-947a-600ced775f23)


* Transaction types frequencies:

![image](https://github.com/user-attachments/assets/bfcf637d-2ed0-4b5b-ba8d-da4991f356aa)

* Delta Source:

![image](https://github.com/user-attachments/assets/2777abcd-e055-4fbc-8a0f-95d2013717df)

* Fraud Detection:

![image](https://github.com/user-attachments/assets/1b75452e-f7c6-40ab-a259-9899732f2416)

## Future Works: 
* I would like to use free open source Facebook, Twitter, etc. scrappers, to gather the data and put them into csv extension file.
* More analysis can be conducted for this type of report. 
