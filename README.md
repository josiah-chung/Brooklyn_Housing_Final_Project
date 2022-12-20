# Brooklyn_Housing_Final_Project

## Do Not Duplicate

In this final project for my Statistical Analysis course at the University of Chicago, I was tasked with developing a model from five CSV files reporting real estate sales in Brooklyn from 2016 to 2020. The goal of this project was to develop a linear regression model for this data that could best predict sale price. The model had to meet the following requirements:
    <= 40 degrees of freedom, 
    >= 13,000 rows used in the model, 
    >= 0.6 adjusted R-squared value, 
    < $450,000 RMSE

The first portion of the code shows the process of extracting and cleaning the data before working on a model. Some steps of the data cleaning included:
    Making the column names the same for all 5 CSV's, 
    Dealing with null/missing values, 
    Changing character types of data, 
    Removing white space from some cells


The end of the code shows the final linear regression model that I settled on and the remaining steps taken to get to that point. I found that restricting the range of the prices used in the model to $5,000-$6,000,000 helped reduce my RMSE and remove unhelpful outliers. I decided on four predictor variables (as well as some transformations) that I believed would give me as high of an R-squared value as possible.
