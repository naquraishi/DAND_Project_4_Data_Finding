# Data Set:Loan Data from Prosper

## Overview of the Data Set:
**This data set contains 113,937 loans with 81 variables on each loan, including loan amount, borrower rate (or interest rate), current loan status, borrower income, and many others.**

## Key Data Analysis Steps:

##### 1. Dataset had duplicate 1698 entries, which had to be dropped for the analysis.
##### 2. pandas groupby is used to group the data to genertate bivariate plots
##### 3. Bar, Distplot, Hist, Violin, Box, Pie plots generated using seaborn and matplotlib. 

## Main Findings:

### Findings Loan Status, Loan Original Amount Box Plot
##### 1. Maximum value loan looks to be in current loan category
##### 2. There are more loans below 10000 in current loan category
##### 3. In dues categories there are maximum number of loans due in >120 days category

### BroserRate LenderYield Scatter Plot
##### 1. The plot is created to see correlation between quantitative variables BorrowerRate and LenderYield
##### 2. As expected, the variatbles show a strong correlation.


### Occupation Borrowers count Bar chart
##### 1. The plot is created to see which are the top borrowing professions
##### 2. Computer Programmers, Analyst and Teachers are among top 10 borrowers


### Borrowers count state vise Bar plot
##### 1. The plot is created to see which states have more number of borrowers
##### 2. CA seems to have very high number of borrowers in comparison to other states


### House owners vs Non house owners borrowered amount Pie chart
##### 1. The plot is created to see houseoweners or non house owners have borrowed more amount
##### 2. Seems, non home oweners have borrowed more than home owners.




