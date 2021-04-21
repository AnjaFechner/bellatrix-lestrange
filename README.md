# bellatrix-lestrange

## Day 1
***

***MySQL***
***
- we solve the My SQL tasks
- pass two taks to solve it later

***Python***
***

- ***Step 0***
- we read the file into Python
- Create the column names because the csv has no headers

***Step 1***
- Explore the data (with Python,Tableau,Excel)
- Missing Values: We drop the Missing values : only 24 values yes and no are the same missbalanced in comparison to the whole dataset
- There are no duplicates in the Dataset
- unwanted columns Q1_Balance to Q4_Balance and customer_number
- target variable: offered accepted
- Maybe later: create groups
- datatypes are correct

***Step3***
***EDA***

![bild1](bild_1.JPG)
y-Variable(yes, No)
- one hint: Drop the outliers for NO can redurce the dataset. The dataset für ysy gets notr bigger but the relationship between no and yes gets better. It is a step to imporve the dataset befor starts the model.
- we create 3 different dataset for handling with the outliers and we how our model will works (because we have different housholdsize and differentz income level that influence of course the dataset

![bild_2](bild_2.JPG)
- we will check if the houeholdsize 8 and 9 (only 1 row) stays in the dataset. Because if we normalize/encode the features, the influence of the bothe rows withe the householdsize 8 and 9 have a big influence of the new interval.

- Result of handling the outliers and household_size: The household_size is not a outliers. This amount stays in the datset after reove the outliers. Additionally to that, it is easier to remove the outliers from the columsn q1_balance to q4_balance that to remove the outliers only from the column average_column. So we have to drop the single row for houehold_size 8.


## Day 2
***

***Tableau***
***
![bild_4](bild_4.JPG)
We visualise our data and the result is, the balance has not a big impact of our target variable. But we will se how the model reachts on the balance-variable.

***Python***
****

![bild_3](bild_3.JPG)

The numerical variable at the positions 1 to 4 stays numerical. But we use this features as categrical in our dataset. We will see how big is the impact of the feature as numerical and as categorical.


## Day 3
***

We try to improve our model.
We try 5 different changes to achieve a better accuracy.

The results are divided into different jupyter notebooks.
![bild_5](bild_5.JPG)




