## Problem Statement
A retail company `ABC Private Limited` wants to understand the customer purchase behaviour against various products of different categories. They have shared purchase summary of various customers for selected high volume products from last month.
The data set also contains customer demographics, product details and Total purchase amount from last month.

## Data Evaluation
Firstly, check out the labels where missing value is present. If there are more than 50% columns have a missing value than we remove that row from our dataset.

### Missing Number Matrix
![matrix.png](/image/missingno_matrix.png)

Since we have a lots of missing value in the `Product_Category_2` and `Product_Category_3` so we remove these value from the dataset.
