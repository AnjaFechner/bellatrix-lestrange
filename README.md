# Bank Analysis - Why customers say "Yes"or "No"to the offered credit card.
## Worked out by
*Simon, Jalal and Anja*

### *April 2021*
***
![creditcards](https://github.com/AnjaFechner/bellatrix-lestrange/blob/main/pictures/creditcards.jpg)

Project exploring the Data of 18000 customers, the analysis and visualisation of them.


## Content
***

- [Introduction](#introduction)
- [The Data](#the-data)
- [Visualisation](#visualisation)
- [Statistical Analysis](#statistical-analysis)
- [Review](#review)
- [My SQL](#my-sql)

## Introduction
***

A highstreet bank has called in a wizard team of data analysts to help them analyse their credit marketing campaign. 
They want to understand which types of customers respond positively to the campaign and what kind of marketing is most successful.
We received the data set of 18000 records from the prevois campaign. This included information about account details over a year, 
demographic and customer segments as well as inforamtion about what type of campaign each customer received.


## The Data 
***
![tools](https://github.com/AnjaFechner/bellatrix-lestrange/blob/main/pictures/tools.jpg)

Our set consits of 18000 dates about customers, who accept or reject a credit card offer from the bank. 
We used Python to read the csv-file, to explore the dataset und to visualize the data. Next to this tool, we used Tableau and MySQL, too.


## Visualisation
***

The graphs for explore and evaluate the data set is published behind this [link](https://public.tableau.com/profile/anja.fechner#!/)
The Tableau [file](https://github.com/AnjaFechner/bellatrix-lestrange/tree/main/tableau) is saved in the Reppo, too.


## Statistical Analysis 
***

We explore the data set that is marked by hughe imbalance between the customer who said 'Yes' and 'No'.
The data set consist of 15 features to analyse what determining factors in peples' liklihood of saying 'Yes' or 'No'.
The features (our x-variables) are following plottet. Our target variable is the credit card offer ('Yes'/'No') .
We try to predict our target variable with the Logistic Regression and the KNN Model as a Machine Learning Algoritmen.
But the hughe imbalance in the dataset prevent the best solution. 

![imbalance](https://github.com/AnjaFechner/bellatrix-lestrange/blob/main/pictures/imbalance.JPG)

We found out that the average balance is not an important factor for predicting the target variable. 
The other features shows an impact of the decision from the customer to say "Yes" to the credit card offer, but the data set is not big enough to find the best combinations.
We try to imrpove the Sampling with Smote. This works for the KNN-model. Please see for this the jupyter notebook file with

The confusion matrix for the best model:
![Confusion%20matrix](https://github.com/AnjaFechner/bellatrix-lestrange/blob/main/pictures/Confusion%20matrix.JPG)

The results of our improving steps are the following:
![table_of_results](https://github.com/AnjaFechner/bellatrix-lestrange/blob/main/pictures/table_of_results.JPG)

Some interesting features of the datat set:



## Review
***


## My SQL
***

Our MySQL file is located in this [folder](https://github.com/AnjaFechner/bellatrix-lestrange/tree/main/mysql)

