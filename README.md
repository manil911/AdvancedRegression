# Advanced Regression Case Study
#Objective:
A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia. The data is provided in the CSV file below.

 

The company is looking at prospective properties to buy to enter the market. You are required to build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not.

 
***The company wants to know:***

- Which variables are significant in predicting the price of a house, and

- How well those variables describe the price of a house.


## Table of Contents
The solution is divided into the following sections: 
- Data understanding and exploration
- Data cleaning
- Data preparation
- Model building and evaluation



## General Information
- A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price


<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- For Ridge: Coeff values are increasing as alpha will increase.r2_score of train data is also 
dropped
- For Lasso: As alpha value increased more feautrues removed from model. But r2score is also 
dropped by 1% in both test and train data 
- Top Features: Neighborhood_NoRidge, Neighborhood_NridgHt, 1stFlrSF, 2ndFlrSF,
OverallQual

- We will choose Lasso as its giving feature selection option.It has removed unwanted 
features from model without affecting the model accuracy. Which makes are model 
generalized and simple and accurate.
- Conclusion 4 from the analysis




## Technologies Used

- Python - version 3.0

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->




## Contact
Created by [@https://github.com/manil911] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->