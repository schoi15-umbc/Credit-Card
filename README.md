# Credit-Card

## **Table of Content**

[Overview](https://github.com/schoi15-umbc/Credit-Card#overview)-
[Goals](https://github.com/schoi15-umbc/Credit-Card#goals) -
[Motivation and Background](https://github.com/schoi15-umbc/Credit-Card#motivation-and-background) -
[Data](https://github.com/schoi15-umbc/Credit-Card#data) -
[Project Info](https://github.com/schoi15-umbc/Credit-Card#project-info) 


## **Overview**

K bank in DC is trying to create a new credit card for their bank. The new credit card is geared to sell to new and existing customers, but the bank wants to make more benefits for existing customers. In order to find out the best benefit program for their new credit card, the bank has hired me to categorize the customers by clustering them. K bank provided me with a dataset that contains data on how the customer uses their bank account. By using Kmeans method, I will attempt to figure out how to cluster the customers along with finding the average of each features for better understanding of the groups.
  
<pre>
Executive Code  :  <a href=https://github.com/schoi15-umbc/Credit-Card/blob/main/Credit%20Card%20_Report.ipynb>Executive Notebook </a> </a>
</pre>

## **Goals**
1. Data Preparation     : Cleaning data, and creating visualizations for deeper understanding of the dataset. 
2. Clustering           : Using K means and PCA to cluster the given data
3. Business Problem     : Finding best suggestion for promotion paln according to the differnt usage behavior of customers. 

## **Motivation and Background**

## **Data**
The dataset is obtained from [Kaggle (Credit Card dataset)](https://www.kaggle.com/arjunbhasin2013/ccdata). It includes 8950 observations, each representing an individual. 
There are 18 Columns: 

1. CUSTID : Identification of Credit Card holder (Categorical)
2. BALANCE : Balance amount left in their account to make purchases 
3. BALANCEFREQUENCY : How frequently the Balance is updated, score between 0 and 1 (1 = frequently updated, 0 = not frequently updated)
4. PURCHASES : Amount of purchases made from account
5. ONEOFFPURCHASES : Maximum purchase amount done in one-go
6. INSTALLMENTSPURCHASES : Amount of purchase done in installment
7. CASHADVANCE : Cash in advance given by the user
8. PURCHASESFREQUENCY : How frequently the Purchases are being made, score between 0 and 1 (1 = frequently purchased, 0 = not frequently purchased)
9. ONEOFFPURCHASESFREQUENCY : How frequently Purchases are happening in one-go (1 = frequently purchased, 0 = not frequently purchased)
10. PURCHASESINSTALLMENTSFREQUENCY : How frequently purchases in installments are being done (1 = frequently done, 0 = not frequently done)
11. CASHADVANCEFREQUENCY : How frequently the cash in advance being paid
12. CASHADVANCETRX : Number of Transactions made with "Cash in Advanced"
13. PURCHASESTRX : Numbe of purchase transactions made
14. CREDITLIMIT : Limit of Credit Card for user
15. PAYMENTS : Amount of Payment done by user
16. MINIMUM_PAYMENTS : Minimum amount of payments made by user
17. PRCFULLPAYMENT : Percent of full payment paid by user
18. TENURE : Tenure of credit card service for user


## **Project Info**

<pre>
Software Requirements
Language/Tool: Python (Anaconda)
Libraries: pandas, seaborn, numpy, matplotlib, sklearn, scipy
</pre>

<pre>
Related Studies

</pre>

<pre>
Contributors : <a href=https://github.com/schoi15-umbc>Sooyeon Choi</a>
</pre>

<pre>
Duration     : November 2020
Last Update  : November 15 2020
</pre>
