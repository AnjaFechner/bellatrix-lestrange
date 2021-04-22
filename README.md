# Bank Analysis - Why customers accept and decline the credit card offer.
## Mit Bootcamp Project
*Simon Goodall, Jalal Karimov and Anja Fechner*

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
- [OnePager](#OnePager)

## Introduction
***

A highstreet bank has called in a wizard team of data analysts to help them analyse their credit marketing campaign. 
They want to understand which types of customers respond positively to the campaign and what kind of marketing is most successful.
We received the data set of 18000 records from the previous campaign. This included information about account details over a year, 
demographic and customer segments as well as information about what type of campaign each customer received.


## The Data 
***
![tools](https://github.com/AnjaFechner/bellatrix-lestrange/blob/main/pictures/tools.jpg)

Our set consists of 18000 dates about customers, who accept or reject a credit card offer from the bank. 
We used Python to read the csv file, to explore the dataset and to visualize the data. Next to this tool, we used Tableau and MySQL, too.


## Visualisation
***

The graphs for exploring and evaluate the data set is published behind this [link](https://public.tableau.com/profile/anja.fechner#!/)
The Tableau [file](https://github.com/AnjaFechner/bellatrix-lestrange/tree/main/tableau) is saved in the Repo, too.


## Statistical Analysis 
***

We explore the data set that is marked by huge imbalance between the customer who accepted and declined the credit card offer.
The data set consists of 15 features to analyze what determining factors in peoples' likelihood of saying 'Yes' or 'No'.
The features (our x-variables) are the following plottet. Our target variable is the credit card offer ('Yes'/'No').
We try to predict our target variable with the Logistic Regression and the KNN as Machine Learning Models.
But the huge imbalance in the data set prevents the best solution. 

![imbalance](https://github.com/AnjaFechner/bellatrix-lestrange/blob/main/pictures/imbalance.JPG)

At first, we dropped the columns Q1 Balance to Q4 Balance, because in the data set there is also the column Average Balance. And we decide  We found out that the average balance is not an important factor for predicting the target variable. 
The other features show an impact of the decision from the customer to say "Yes" to the credit card offer, but the data set is not big enough and because of the huge imbalance it was not to find the best feature combinations.
But we try our best and used SMOTE. 

The results of our improving steps are the following:
![table_of_results](https://github.com/AnjaFechner/bellatrix-lestrange/blob/main/pictures/table_of_results.JPG)

The confusion matrix for the best model:
![Confusion%20matrix](https://github.com/AnjaFechner/bellatrix-lestrange/blob/main/pictures/Confusion%20matrix.JPG)

Some interesting features of the data set:
![interesting_features](https://github.com/AnjaFechner/bellatrix-lestrange/blob/main/pictures/interesting_features.JPG)

Our jupyter notebook files:

*Version: With the column "average_balance":*

- [Version 0](https://github.com/AnjaFechner/bellatrix-lestrange/blob/main/jupyter_notebook/with_avg_balance__version_0.ipynb)
- [Version 1](https://github.com/AnjaFechner/bellatrix-lestrange/blob/main/jupyter_notebook/with_avg_balance__version_1.ipynb)
- [Version 2](https://github.com/AnjaFechner/bellatrix-lestrange/blob/main/jupyter_notebook/with_avg_balance__version_2.ipynb)
- [Version 3](https://github.com/AnjaFechner/bellatrix-lestrange/blob/main/jupyter_notebook/with_avg_balance__version_3.ipynb)
- [Version 4](https://github.com/AnjaFechner/bellatrix-lestrange/blob/main/jupyter_notebook/with_avg_balance__version_4.ipynb)


*Version: Without the column "average_balance":*

- [Version 0](https://github.com/AnjaFechner/bellatrix-lestrange/blob/main/jupyter_notebook/without-balance-version_0.ipynb)
- [Version 1](https://github.com/AnjaFechner/bellatrix-lestrange/blob/main/jupyter_notebook/without-balance-version_1.ipynb)
- [Version 2](https://github.com/AnjaFechner/bellatrix-lestrange/blob/main/jupyter_notebook/without-balance-version_2.ipynb)


## Review
***

- Went well:
We had a good overview and handling of the data in the early stages (removing the average balance very early) and changing the data type from numbers to categories.

- Would do differently:
Probably not use machine learning to answer this type of business case. The data is too unbalanced and the data set too small. 
Another approach will be to try the Decision-Tree-Model.


## My SQL
***

Our MySQL file is located in this [folder](https://github.com/AnjaFechner/bellatrix-lestrange/tree/main/mysql).

## OnePager
***

Our OnePager is located in this [folder](https://github.com/AnjaFechner/bellatrix-lestrange/tree/main/onepager).

