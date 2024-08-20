# Lending Club Case Study
> You work for a consumer finance company which specialises in lending various types of loans to urban customers. When the company receives a loan application, the company has to make a decision for loan approval based on the applicant’s profile. Two types of risks are associated with the bank’s decision:

If the applicant is likely to repay the loan, then not approving the loan results in a loss of business to the company

If the applicant is not likely to repay the loan, i.e. he/she is likely to default, then approving the loan may lead to a financial loss for the company

The data given below contains information about past loan applicants and whether they ‘defaulted’ or not. The aim is to identify patterns which indicate if a person is likely to default, which may be used for taking actions such as denying the loan, reducing the amount of loan, lending (to risky applicants) at a higher interest rate, etc.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
This company is the largest online loan marketplace, facilitating personal loans, business loans, and financing of medical procedures. Borrowers can easily access lower interest rate loans through a fast online interface. 

Like most other lending companies, lending loans to ‘risky’ applicants is the largest source of financial loss (called credit loss). Credit loss is the amount of money lost by the lender when the borrower refuses to pay or runs away with the money owed. In other words, borrowers who default cause the largest amount of loss to the lenders. In this case, the customers labelled as 'charged-off' are the 'defaulters'.  

If one is able to identify these risky loan applicants, then such loans can be reduced thereby cutting down the amount of credit loss. Identification of such applicants using EDA is the aim of this case study.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
• Income range between 0-20000 has high chances of charged off.

• Interest rate more than 16% has good chances of charged off as compared to other category interest rates.

• Those who are not owning the home is having high chances of loan defaulter.

• Those applicants having loan for small business is having high chances for loan defaults.

• High DTI value having high risk of defaults.

• Higher the Bankruptcies record higher the chance of loan defaults.

• DE States is holding highest number of loan defaults.

• The Loan applicants with loan Grade G is having highest Loan Defaults.

• Applicant having home ownership as MORTGAE and Average Annual income 60K or loan amount more than 14K has higher chance of defaulting.

• small_business loan where avegrage loan_amount is more than 14K has higher default.

• Verified status having loan amount greater than 16K has higher chance of defaulting. This also indicates issue in verification process.

• G grade has higher defaults when interest rate is above 20%. F grade has highest defaults when average loan amount is between 15-20K.

• Employment length >10+ years has higher chances of defaults with an average loan amount 14500.

• December month has higher defaults having average loan amount 13K.

• vacation loans in AK, HI, OR is risky. House loans in NH, WV is risky. small business loans in DE, NM, WV, WY is risky.

• small business loans for lowest and medium income groups (4K-65K) has higher chance of defaulting.

• Medium debt-to-income group in the lowest income range has higher chances of defaulting.

• home ownership OTHER has high default when loan purpose is moving or car.

• Applicants with prb_rec/pub_rec_bankruptcies or open_acc/total_acc has higher chances of defaulting.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
* Python - version 3.11.4
* Matplotlib - version 3.7.1
* Numpy - version 1.24.3
* Pandas - version 1.5.3
* Seaborn - version 0.12.2

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
Give credit here.
- This project was inspired by Akashdeep Makkar 
- UpGrad sessions on Exploratory Data Analysis (EDA) on the learning platform.



## Contact
Created by [@Adityaajain] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
