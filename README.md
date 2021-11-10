# Lending Club Case Study
<b>Problem Statement</b>
> A consumer finance company which specialises in lending various types of loans to urban customers. When the company receives a loan application, the company has to make a decision for loan approval based on the applicant’s profile. Two types of risks are associated with the bank’s decision:
> - If the applicant is likely to repay the loan, then not approving the loan results in a loss of business to the company
> - If the applicant is not likely to repay the loan, i.e. he/she is likely to default, then approving the loan may lead to a financial loss for the company

<b>Understandings</b>

As a financial organisation it is always risky to lend loans, actually it largest source of fiscal loss (called credit loss). The credit loss is the quantum of money lost by the lender when the borrower refuses to pay or runs down with the amount owed. In short, borrowers who don't pay cause the largest quantum of loss to the lenders. In this case, the customer labelled as' charged-off' are the 'defaulters'.

Still, also similar loans can be reduced thereby cutting down the amount of credit loss, If one is suitable to identify these risky loan aspirants. We identification such loan aspirants using EDA (Exploratory Data Analysis) is the end of this case study. 

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
As a employee of finance company which is specialises in lending various types of loans to urban customers. When the company receives a loan application, the company has to make a decision for loan approval based on the applicant’s profile. 

The project try to analize the Loan data and try to reduce fiscal loss for the company. The project is undertaken to solve this problem describe above with Exploratory Data Analysis

There are two types of decisions that company want to take:
- **Loan accepted**: If the company approves the loan, there are 3 possible scenarios described below:
  - Fully paid: Applicant has fully paid the loan (the principal and the interest rate)
  - Current: Applicant is in the process of paying the instalments, i.e. the tenure of the loan is not yet completed. These candidates are not labelled as 'defaulted'.
  - Charged-off: Applicant has not paid the instalments in due time for a long period of time, i.e. he/she has defaulted on the loan
- **Loan rejected**: The company had rejected the loan (because the candidate does not meet their requirements etc.). Since the loan was rejected, there is no transactional history of those applicants with the company and so this data is not available with the company.

In other words, the company wants to understand the driving factors (or driver variables) behind loan defaulter, i.e. the variables which are strong pointers of defaulter. The company can use this knowledge for its portfolio and risk/threat assessment. 

Dataset has been provided by for Exploratory Data Analysis. It contains the complete loan data for all loans issued through the time period 2007 t0 2011.
<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Technologies Used
- Python - 3.8.8
- NumPy - 1.21.4
- Pandas - 1.3.4
- Seaborn - 0.11.2
- matplotlib - 3.4.3

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- Grading system is working as expected, the Low-grade loans have high tendency to default.
- People with records of bankruptcies should be denied loan.
- Higher interest rate loan has more defaulter. Always need to check the background of applicant thoroughly whenever interest rate is high.
- Small businesses are particularly risky, therefore should be cautiously sanctioned.
- Individuals who have more open credit lines are less likely default, therefore number of open credit lines is a good indicator of financial safety.
- When the purpose is debt consolidation, more scrutiny of applicant as has high tendency to default.
- People with records of bankruptcies should be denied loan. individuals may be better strategy than approving their loan with higher interest.
- The applicant belonging to CA state, need more scrutiny must be done, as tendency to default is high


<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
- References: 
  - upGrad: [What is Exploratory Data Analysis in Python? Learn From Scratch](https://www.upgrad.com/blog/exploratory-data-analysis-in-python/)
  - kaggle: [Comprehensive data exploration with Python](https://www.kaggle.com/pmarcelino/comprehensive-data-exploration-with-python)


## Contact
Created by Suprabhat Paul - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
