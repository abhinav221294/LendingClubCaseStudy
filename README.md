# Lending CLub Case Study
> The credit loss is the amount of money lost by the lender when the borrower refuses to pay or runs away with the money owed since borrowers who default cause the largest amount of loss to the lenders. In this case, the customers labelled as 'charged-off' are the 'defaulters.The Company need to find out what are driving factors for loan to getting defaulted.Help company to analyse the pattern in data and provide solution on how can they reduce loan defaulting hence cutting down credit loss. Identification of such applicants using EDA is the aim of this case study.



## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)


## General Information
- Lending case is a marketplace for lending various type of loans like home loans, personal loans, business loans etc that matches borrower who are seeking a loan with investors  looking to lend money and make a return.
- We were trying to analyze what are the all driving factor that is causing a loan to default and how to reduce that which help the company to reduce the financial losses.
- We used the loan data (loan.csv file) to analyze the problem.



## Conclusions
- Loan taken for small business purpose.
- Loan issued for term that has 60 months slight chance but there is very less difference.
- Loan issued for verification_status inrespect the verification_status when amount is greater than 16K.
- -For annual_inc_group inrespect the annual_inc_group. 
- For int_rate_group when interest rate between 9%-21%.
- For annual_inc_group  inrespect the revol_util_group. 
- For annual_inc_group  inrespect the installment_group.
- INT Rate Group having interest having between 13-16% likely to get charged off (defaulted)
- Open_acc_group having 6-10. 
- Pub_rec_group having between 0-20.
- Annual_inc_group having between 31-58K.
- Revol_util_group having 60-80.
- Installment_Group  having 107-199.
- Funded_Amnt_Inv_Group having 5K-10K  but close for 0K-5K.
- Dti_group having 12-18.
- Inq_last_6mths having 0.
- Loan_amnt_group having 0-5K.
- Emp_length having 10.



## Technologies Used
- Numpy - version 1.24.1
- Pandas - version 1.5.2
- Matplotlib - version 3.6.2
- Seaborn - version 0.12.1



## Acknowledgements
Thanks you Upgrad and IIIT bangalore for giving such a beautiful project.


## Contact
Created by [@abhinav221294] - feel free to contact me!
