# DSND_Project1
Study of the Stack Overflow survey answers 
<br>
## Installation
- Pandas      for the dataframes manipulations
- Numpy       for the statistics and maths
- Sklearn     for the predictions
- Matplotlib  fro the visualizations

## Data
The data used are the answers to the Stack Ovreflow surveys for 2017, 2018 and 2019 found at https://insights.stackoverflow.com/survey. It can be as weel foud on the repo.

## File description
- Stack Overflow study.ipynb : Wrangling and analysing the data extracted from the .csv files
- survey_results_public_2017 : The data downloaded from Kaggle for 2017
- survey_results_public_2018 : The data downloaded from Kaggle for 2018
- survey_results_public_2019 : The data downloaded from Kaggle for 2019

## Project motivation
I investigate some insights about the survey answers to the Stack Overflow surveys and I try to make predictions on some variables about the Stack Overflowers. Then I added one more insight with visualizations about Stack Overflow.

## Licence
Kaggle : Data provider

## Authors 
Quentin Joly : Jupyter Notebook

## Summary
Q1 - Is it possible to predict the expected salary and what are the most influencial coefficients to the salary expectation?
   -> We can predict the Expected Salary mostly with the ImportantBenefits column and a little bit with the Country column as well, but with a low precision (R² = 0.24)
   
Q2 - Is it possible to predict how much hours someone spend on looking for job opportunities ?
   -> The best R² score found is 0.006 which is very low, the data model used might be not the most appropriated to predict the HoursPerWeek column. With this data model, we can't predict this variable.
   
Q3 - Can we predict how many hours someone will work per week?
   -> After various runs of the jupyter notebook, the best R² for the prediction is variating between -0.33 and -0.01. This difference is probably due to the random sample I take at the beginning of the study because of low memory issues.
   
Q4 - How is evolving the popularity of StackOverflow?
   -> Among the people who answered, most of them join the community by created an account but they don't really feel part of the community. The welcome to the site is mostly the same through time. Since 2014 they are fewer each year to discover Stack Overflow but the frequecy of the frequentation of the site is quite high.

## Medium link
https://medium.com/@quentinjoly31/stack-overflow-survey-investigation-3e7b5c7ed159 

#### Last edition
15/03/2020
