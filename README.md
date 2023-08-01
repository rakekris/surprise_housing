# Project Name
> Surprise Housing - advanced regression Assignment


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information

A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia. The data is provided in the CSV file below. The company is looking at prospective properties to buy to enter the market. You are required to build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not. The company wants to know:

  a) Which variables are significant in predicting the price of a house, and
  b) How well those variables describe the price of a house. Also, determine the optimal value of lambda for ridge and lasso regression.

For this use case we are using train.csv data  a data description.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

Steps involved in Multiple Linear Regression

Step 1: Read the data from the source
Step 2: Understand The data
Step 3: Clean up the data, drop unwanted columns, check for duplicates etc
Step 4: EDA
Step 5: Perform outlier analysis
Step 6: Impute data whereever necessary
Step 7: Map all categorical variables to Dummy variables
Step 8: Train and test split
Step 9: Scaling
Step 10: Feature Selection
Step 11: Evaluate Test set


## Conclusions
The top features contributing significantly are as below
- OverallQual
- OverallCond
- YearBuilt
- Neighborhood_StoneBr
- Exterior1st_BrkFace
- TotalBsmtSF
- LotArea


More details and analysis in the "_Rakesh_Krishnamurthy.ipynb_" and "_AdvancedRegressionPart2_"


<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- pandas - version 1.4.4
- seaborn - version 0.12.2
- numpy - version 1.23.5
- matplotlib - version 3.7.0
- sklearn - version 0.0.post5

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
Contributors
- Rakesh Krishnamurthy



## Contact
Created by [@rakekris] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
