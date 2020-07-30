Readme


# Module 2 Final Project: Housing project in King County


## Objectives

Use King County Housing Data collected from May 2014 to May 2015 to find safe 
homes for people from the homeless shelter in an effort to reduce the spread
of covid-19.

## Final Project Summary


## The Dataset

King County House Sales dataset. 

## Data Exploration

1. Find out shape and columns of the data to know what the data contains
2. Check for duplicates and missing values
3. Generate a scatter plots to have an overall picture of the data
4. Generate joint plots to understand the relationship between home price and other
features
5. Plot distribution plots for each feature vs price 
6. Use skew function to understand the skew of attribute distribution
7. Plot violin plots for selected features to understand the summary statistics of mean, median and distribution of the data
8. Generate bar graphs for each attribute to see their relationship with home price
9. List unique values for each attribute

## Data Cleaning
1. Check for null or NaN values
2. Replace NaNs with mean
3. Convert data type from floats to integers
4. Drop outliers for values > z_score with threadhold of 3
5. Create dummy variables

## Build Regression Model to Predict Prices with All the Data
1. Build linear regression model with Statsmodel: the model is not used to
analyze the data.
2. Build linear regression with SKLearn: the model has an R quared value of 87.5%. This satisfies the requirement for R squared.

## Train and validate the model
1. Setup train test split
2. Train and predict the model by:
    fit the model
    calculate predictions on training, testing sets, traing and testing residuals, mean square error.  
3. Cross Validation
4. Evaluate the effect of train-test split size

## King County Temporary Housing Project for Homeless People During Covid-19 Pandamic Project
1. Find homes by zipcode and sale price
2. Find homes by square feet living
3. Limit homes to a numbder of bedrooms
4. Locate homes by conditions

## King County Map shows locations of cheap, medium and high price homes
## King County Map shows locations of the homes of interest

## Summary

Potential homes for the sheltor residents have:
    
    -price below $500000
    
    -Condition ranges 2-5
    
    -Up to 5 bedrooms in the house 
    
    -Home with sq ft living up to 2020 sq. ft.

## Future Work: I would like to analyze the rental data because that will give me an accurate total cost for the housing project. I also would like to explore the option of renting from hotels since many of them are perhaps avaiable during the padamic. This way, the government can also help other business in the area. 