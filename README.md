# Lending Club Case Study

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)
* [Contributors](#contributors)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
### Background
- This company is the largest online loan marketplace, facilitating personal loans, business loans, and financing of medical procedures. Borrowers can easily access lower interest rate loans through a fast online interface.
- Like most other lending companies, lending loans to ‘risky’ applicants is the largest source of financial loss (called credit loss). Credit loss is the amount of money lost by the lender when the borrower refuses to pay or runs away with the money owed. In other words, borrowers who default cause the largest amount of loss to the lenders. In this case, the customers labelled as 'charged-off' are the 'defaulters'.

### Problem Statement
- It specializes in lending various types of loans to urban customers. When the company receives a loan application, the company has to make a decision for loan approval based on the applicant’s profile.

### Objective
- The goal is to identify these risky loan applicants, then such loans can be reduced thereby cutting down the amount of credit loss.
- The objective is to use EDA to understand the driving factors (or driver variables) behind loan default, i.e. the variables which are strong indicators of default. The company can utilize this knowledge for its portfolio and risk assessment.

### Data
- The data set is a csv file with the loan data for the Lending Club.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
According to our observations, below are the most impactful driving factors (or driver variables) behind loan default.
- Higher the loan amount (above 16K) will lead to higher default.
- Higher the installment amount (above 327) will lead to higher default.
- Higher the interest rate above 13% will lead to higher default.
- Lower annual income (below 37K) will lead to higher default.
- Higher debt to income ratio (above 15%) will lead to higher default.
- Loan issue month is in Dec, May, Sep.
- Higher the revolving utilization rate above 58%, bigger the chance of the loan getting defaulted.
- Higher the revolving balance above 10k, bigger the chance of the loan getting defaulted.
- Repayment term (5 years).
- Loan Grades from D, E, F and G when compared to others.
- Loan sub grades G3 and F5 when compared to others.
- Missing employment record will lead to default.
- Loan purpose like small business, renewable energy, educational.
- Derogatory public records with (1 or 2) have the chance of defaulting the loan.
- Higher the number of public bankruptcy records, bigger the chance of defaulting the loan.
- Higher installments for any income group have more number of defaults.
- Across all the income groups, the loan amount is higher for people who defaulted.
- Medium debt-to-income group in the lowest income range is the most risky when it comes to loan repayment.
- Interest rate for charged off loans is pretty high than that of fully paid loans in all the loan amount groups.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Technologies Used
- numpy - version 1.26.4
- pandas - version 2.1.4
- matplotlib - version 3.8.0
- seaborn - version 0.12.2

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
This project was inspired by UpGrad IITB Programme as a case study for the Machine Learning and Artificial Intelligence course.

## Contributors
- Vijay Sekhar Lattala
- Srikanth Kaspe


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
