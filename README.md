# Project Name: Lending Club CaseStudy 

## Table of Contents
* Background
* Technologies Used
* Conclusions
* Acknowledgements
* Collaborators

### Background:
Lending Club is the largest online loan marketplace, facilitating personal loans, business loans, and financing of medical procedures. When the company receives a loan application, the company has to make a decision for loan approval based on the applicant’s profile. There are two types of risks associated with the bank’s decision:
1. If the applicant is likely to repay the loan, then not approving the loan results in a loss of business to the company
2. If the applicant is not likely to repay the loan, i.e. he/she is likely to default, then approving the loan may lead to a financial loss for the company

Like most other lending companies, lending loans to ‘risky’ applicants is the largest source of financial loss (called credit loss). Credit loss is the amount of money lost by the lender when the borrower refuses to pay or runs away with the money owed

The primary objective of this exercise is to assist Lending Club in minimizing the credit losses and identify the potential factors for defaulting.

### Technologies Used:
* Python - version 3.10.12
* Matplotlib - version 3.7.1
* Numpy - version 1.26.4
* Pandas - version 2.2.2
* Seaborn - version 0.13.2

### Conculsions:
The driving factors that impact defaulting of loan are
* Annual Income
* Purpose
* Interest Rate
* Loan Amount
* Grade
* Home Ownership

#### Other Observations:

There is more probability of defaulting when :

* People taking loan for 'home improvement' or 'small business' and have income of 60k -70k
* People who receive interest at the rate of 20%-25% and have an income of 60k-80k
* People whose home ownership is 'MORTGAGE and have an income of 60K-70K
* People with annual income of 100K-125K and have taken loan amount of 17.5K to 20K
* People who have taken a loan in the range 30k - 35k and are charged interest rate of 15%-17.5%
* People who have taken a loan for small business and the loan amount is between 12K to 14K
* People whose home ownership is 'MORTGAGE and have loan of 14-16k
* People whose grade is F and taken loan amount is between 15k-20k
* People whose employment period is more than 10yrs and taken loan amount is 12k-14k
* People with the loan status is verified and took loan amount above 16k
* People having grade G and took loan with interest rate above 20%

### Acknowledgements:
This project was inspired by UpGrad IITB Programme as a case study for the Machine Learning and Artificial Intelligence course.
Special thanks to the team for providing the resources and support for this case study.

### Collaborators:
 [Pooja Kamath](https://github.com/Pookam90) and  [Haripriya Pamu](https://github.com/HaripriyaPamu)
