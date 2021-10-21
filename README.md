# Introduction

This readme file will go over the steps taken from start to finish. 

# Ask

What is the predicted price of a dataset with houses?

# Prepare

The data used was directly taken from Kaggle's page for [this challenge](https://www.kaggle.com/c/house-prices-advanced-regression-techniques/submit).

# Process

To adequately analyze the data, one must ensure that the training set is properly portraying the dataset one would want to predict the prices of. To do that, one would remove all cases with variables from the training set that are not contained within the dataset one would want to predict the prices of. The vice versa action should also taken, because there were are variables inside the real dataset which do not exist in the training set. One would also replace all the character values in the dataset with numeric values (e.g GasW = 1, GasE = 2, etc.). This is to ensure that the methods used to analyze are working as intended.

Appropriate choices for a processing tool here would be using R, Matlab, Python, Google Spreadsheets or Microsoft Excel.

In my case, I've used Google Spreadsheets to clean the data.

# Analyze

The code with all the explaining comments is attached to this repository.

This visual showcases to the developer that an appropriate alpha and number of iterations values are chosen for running gradient descent algorithm.

(picture)

# Post-Process

After we have the data, we export it as csv file and upload it to google spreadsheets where we remove the scientific notation and calculate the mean of the results of both the methods used in a new column. This column is our final price prediction.

Picture of first 10 predictions:

(pictures of first 10)

Picture of last 10 predictions:

(picture of last 10)

All the supporting files and scripts are attached to this repository. One could also find the raw and processed data.

