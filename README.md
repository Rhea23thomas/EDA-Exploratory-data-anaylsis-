# EDA ON LOAN DATASET (Identifying the defaulter)
> The main aim of this project is to identify patterns which indicate if a person is likely to default and not likely to pay back the loan, which may be used for taking actions such as denying the loan, reducing the amount of loan, lending (to risky applicants) at a higher interest rate, etc.


## Table of Contents
* [Problem Statement](#problem-statement)
* [Problem Solving Methodology](#problem-solving-methodology)
* [Conclusions](#conclusions)
* [Technologies Used](#technologies-used)


## Problem Statement
When the company receives a loan application, the company has to make a decision for loan approval based on the applicant’s profile. Two types of risks are associated with the bank’s decision:

If the applicant is likely to repay the loan, then not approving the loan results in a loss of business to the company

If the applicant is not likely to repay the loan, i.e. he/she is likely to default, then approving the loan may lead to a financial loss for the company

So, company wants to understand the driving factors (or driver variables) behind loan default, i.e. the variables which are strong indicators of default.  The company can utilize this knowledge for its portfolio and risk assessment. 


## Problem Solving Methodology
* Data Sourcing & Understanding -
> Source the dataset which contains the complete loan data for all loans issued through the time period 2007 t0 2011. 
> Making use of the data dictionary and understanding the columns and their domain specific uses.
* Data Cleaning -
> Remove null valued columns having missing percentage grater than 30%, customer behaviour variables, single valued columns, columns having all unique values, rows with loan status as current and those with null values
* Data Manipulation -
> Change the data type of columns to make them fit for analysis, remove outliers, derive new metrics and perform binning
* Univariate Analysis -
> Analyse all the continuous and categorical variables and plot their distribution to gain insights
* Bivariate Analysis -
> Analyse continuous variables with themselves and then with all the categorical variables and plot the visualizations to gain deeper insights
* Bivariate Analysis with Probability of Charged Off -
> Use a custom function and analyse all the categorical variables and the bins of continuous variables with the probability of charged off to find how the probability of charged off changes with these columns
* Recommendations -
> Recommend the company (Lending Club) what all are the driver variables which can be considered as key indicators to identify defaulters while approving the loan 


## Conclusions
- The driver variables which can be used to as key indicators to identify defaulters are :-

1. Term
2. Interest Rate
3. Grade/Sub-grade
4. Annual Income
5. Purpose
6. Loan Amount
7. Home Ownership
8. Employment Length
9. Verification Status
10. Location
11. Issue Month


## Technologies Used
- Numpy      - version 1.21.6
- Pandas     - version 1.3.5
- Seaborn    - version 0.11.2
- Matplotlib - version 3.2.2
# EDA-Exploratory-data-anaylsis-
