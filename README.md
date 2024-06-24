# Lending Club Case Study
Problem Statement:
Like most other lending companies, lending loans to ‘risky’ applicants is the largest source of financial loss (called credit loss). Credit loss is the amount of money lost by the lender when the borrower refuses to pay or runs away with the money owed. In other words, borrowers who default cause the largest amount of loss to the lenders. In this case, the customers labelled as 'charged-off' are the 'defaulters'.

*Understand the driving factors (or driver variables) behind loan default
*Identify risky loan applicants using EDA


## Table of Contents

## [General Info](#general-information)
Analyse Lending company data and identify charged off customer behaviour

## [Technologies Used](#technologies-used)
-Python
-Libraries:
--Numpy	
--Panads
--Matplotlib
--Seaborn

## Conclusions
Univariate Analysis
Loan Status
		Total count and percentage of loan customer by their loan status (Fully Paid/Charged Off/Current). 
		Fully Paid: 13982(84%) Most of the customers are in fully paid category
		Charged : 2152(13%)
		Current : 540 (3%)
Grade
		Total count and percentage of loan customer by Grade (A/B/C/D/E/F/G)
		Highest customer in Grade B 5144 (31%)
		Lowest customer in Grade G 118 (1%)

Employment Length

		Employees who have employment length 10 and more are largest customer 3959 (24%)
		second highest are customers who have 1 years experience
Home Ownership
		Rent and Mortgage type customer are the largest customer base. Customers who have own house are only 7%.
Verification 
Status
		42% non verified customers are the highest loan takers. High percentage of non verified customer shows company is not having strict policy or measures to verify customer 		details like address, income sources, credit history. This increases risk of loan defaulters
Purpose
		Highest no. of customers are taking loan for debt consolidation. This has direct relation with home ownership, as many customers who have house mortgage may be using this 		loan for debt consolidation
Address
		Plotted most loan taking states in descending order which will eventually help to target customers to increase business.
Loan Term
		72% peoples taken loan for 36 month tenure and remaining 28% taken loan for 60 month tenure.


Bivariate

Loan status and Employment length
		After plotting box plot using Loan status and employment length we found no correlation between employment length and loan status.
Loan status and Annual income
		After plotting box plot we found interquartile range of charged off customers are below compare to fully paid customer. We can infer customers who have low annual income 		have chances of defaulters
Loan status and interest rate
		We plotted box plot using Loan status and interest rate and we found 25th to 75the percentile of charged off customers are on high interest rate. Customers who have high 		interest rate have high changes of defaulters
Loan status and dti
		We plotted box plot using Loan status and dti(debt to income ratio) and we found 25th to 75the percentile of charged off customers are on high dti. Customers who have high 		dti ratio have high changes of defaulters
Loan status and installment
		After plotting box plot using Loan status and installment we found 75th percentile of charged off customer is high which means high installment amount customer have  			chances of defaulters
Loan status and loan amount
		After plotting box plot using Loan status and Loan Amount we found 75th percentile of charged off customer is high which means high loan amount customer have  chances of 		defaulters
Loan status and IncInstallmentRatio(Income & Installment Ratio)
		After plotting box plot using Loan status and Income installment ratio we found 25th and 75th percentile of charged off customer is high which means high loan amount 			customer have  chances of defaulters

Loans status and inq_last_6mths
		After plotting box plot using Loan status and last 6 months inquiry attribute we can analyse 
		if customer enquiries are more than one in last 6 months then there is high chances of charged off
Loan status and revol_util
		We plotted box plot using Loan status and revol_util and identified customer who are having more utilization rate compared to borrowed amount have high chances of charged 		off
Loan status and total_acc 
		Box plot of Loan status and total account shows plot is more or less same for both changed off and fully paid customers.
		From the graph we can conclude there is no direct impact of total account on charged off customers
Loan status and Grade
		Using Box plot of Loan status and grade we identified B, C & D grades are  having high chances of defaulters
Loan status and state address
		Box plot for both charged off and fully paid customers is same for loan status vs state address which indicates no direct relationship.
Loan status and home ownership
 		We have created derive column based on home ownership ("RENT":1,"OWN":2,"MORTGAGE":3,"OTHER":4)
		From the graph we can conclude there is no significant direct impact of loan status and home ownership
Loan status and term
		People who are taking loan for 60 months of tenure are likely to default.



<!-- You can include any other section that is pertinent to your problem -->

## General Information
 A consumer finance company which specialises in lending various types of loans to urban customers. When the company receives a loan application, the company has to make a decision for loan approval based on the applicant’s profile. Two types of risks are associated with the bank’s decision:
If the applicant is likely to repay the loan, then not approving the loan results in a loss of business to the company
If the applicant is not likely to repay the loan, i.e. he/she is likely to default, then approving the loan may lead to a financial loss for the company

Business problem that your project is trying to solve?
Like most other lending companies, lending loans to ‘risky’ applicants is the largest source of financial loss (called credit loss). Credit loss is the amount of money lost by the lender when the borrower refuses to pay or runs away with the money owed. In other words, borrowers who default cause the largest amount of loss to the lenders. In this case, the customers labelled as 'charged-off' are the 'defaulters'. 

- What is the dataset that is being used?
Loan Data Set CSV File


## Conclusions
1. Highest customer in Grade B 5144 (31%)
2. Employees who have employment length 10 and more are largest customer 3959 (24%)
3. Rent and Mortgage type customer are the largest customer base. Customers who have own house are only 7%.
4. 42% non verified customers are the highest loan takers. This increases risk of loan defaulters
5. Highest no. of customers are taking loan for debt consolidation.
6. 72% peoples taken loan for 36 month tenure and remaining 28% taken loan for 60 month tenure.
7. Customers who have low annual income have chances of defaulters
8. Customers who have high interest rate have high changes of defaulters
9. Customers who have high dti ratio have high changes of defaulters
10.Customers who have high installment amount have  chances of defaulters
11.Cusomers who have high loan amount have  chances of defaulters
12. Customer enquiries are more than one in last 6 months then there is high chances of charged off
13. People who are taking loan for 60 months of tenure are likely to default. 

## Libraries version
Pandas: 2.2.2
NumPy:1.26.4
Seaborn:0.12.2
Matplotlib:3.8.0
Anaconda Navigator: 2.6.0

## Acknowledgements
Give credit here.
- This project was inspired by UpGrad Team
- References if any: None
- This project was based on EDA module


## Contact
Created by [@akhilgarg81] - feel free to contact me!
