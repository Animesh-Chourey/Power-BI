# Credit Card Data Analysis Using Power BI

This project is my attempt to learn and create an analysis on credit card dataset using Power BI. The main focus will be on importing, transforming, and visualising the dataset on credit card defaults. 


### Steps-

* The dataset is available on UCI Machine Learning Repository.
* Fixing the column names:
    * In this dataset, converted the row 2 as the column name, as it gives much clearer understanding of the data instead of pre-existing names.
    * Rename the second last column to DEFAULT, and the last column to STATES.
    * Commited the changes to the data by pressing on close and apply.
* Transforming the dataset:
    * Convert the values in the sex coloumn with 1 to Male and 2 as Female respectively. Going to replace values option and firstly replacing the values as mentioned before. (Here ensure the datatype is changed to 'text' from 'whole number' to replacce the numbers).
    * Similarly converted the categorical data from Education column respectively by adding a new column with conditional column option.
    * Same steps taken as the previous one for the Marriage column.