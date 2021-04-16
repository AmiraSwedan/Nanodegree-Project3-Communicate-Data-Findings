# Nanodegree-Project3-Communicate-Data-Findings

## Dataset
This data set contains 113,937 loans with 81 variables on each
loan, including loan amount, borrower rate (or interest rate),
current loan status, borrower income, and many others.
This [data dictionary](https://docs.google.com/spreadsheets/d/1gDyi_L4UvIrLTEC6Wri5nbaMmkGmLQBk-Yx3z0XDEtI/edit#gid=0) explains the variables in the data set.


## Required Packages 
In this notebook I used the following packages: 
1. pandas 
2. Seaborn 
3. matplotlib 
4. numpy 

## Key questions:
using the propser loans dataset, I tried to answer the following questions:
1. What is the loan status of the majority of borrowers?
2. What is the income range of the majority of borrowers at the time the listings created? 
3. What is the debt to income ratio of the majority of listings?
4. What is the interest rate of the majority of listings ?
5. What is the debt to income ratio and interest rate of borrowers according to the loan status ?

## Key findings:
1.  the loan amount is associated with the number of investors who fund the loan, the more investors the higher amount provided, in addition, the more investors contributed the lower interest rate the borrower will sustain.
2. the majority of borrower have to submit documents that verfies their income, which should not be less than $75,000 in average.
3. the debt to income ratio and interest rate for borrowers with loan status (Defaulted) or (Charged off) was higher than others completed their loans 
