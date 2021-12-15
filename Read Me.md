
# Risk Analytics in Banking


# Introduction

We will use this case study to gain an understanding of how we can apply EDA to a real-world business scenario, as well as some basic understanding of how risk analytics fits into banking.

The data  contains the information about the loan application at the time of applying for the loan. It contains two types of scenarios:

- The client with payment difficulties: he/she had late payment more than X days on at least one of the first Y instalments of the loan in our sample,

- All other cases: All other cases when the payment is paid on time.

When a client applies for a loan, there are four types of decisions that could be taken by the client/company):

Approved:
The Company has approved loan Application

Cancelled:
The client cancelled the application sometime during approval. Either the client changed her/his mind about the loan or in some cases due to a higher risk of the client he received worse pricing which he did not want.

Refused:
The company had rejected the loan (because the client does not meet their requirements etc.).

Unused offer:
Loan has been cancelled by the client but on different stages of the process.


# Problem

When a Bank receives a loan application, it must decide on the loan's approval based on the applicant's profile. The bank is faced with two types of risks:

If the applicant is likely to repay the loan, then not approving it results in the bank losing business.

If the applicant is not likely to repay the loan, then  approving it results the loan may lead to a financial loss.



# Dataset

The selected dataset of the applicant’s profile' attributes is in this URL.
[URL](https://www.kaggle.com/gauravduttakiit/loan-defaulter)

# Question?

- Is the applicant eligible for the loan? 


# Data 

1. 'application_data.csv'
It contains all the information of the client at the time of application. The data is about whether a client has payment difficulties.

2. 'previous_application.csv'
It contains information about the client’s previous loan data. It contains the data whether the previous application had been Approved, Cancelled, Refused or Unused offer.

3. 'columns_description.csv'
It is data dictionary which describes the meaning of the variables.

# Machine learning  Algorithm
- Random Forest Algorithm

# contact me 
Ali Mahmoud Mostafa - a.mostafa609@gmail.com


