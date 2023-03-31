# Credit-EDA
The loan providing companies find it hard to give loans to the people due to their insufficient or non-existent credit history. We will have to use EDA to analyze the patterns present in the data. This will ensure that  applicants capable of repaying the loan are not rejected.
When the company receives a loan application, the company has to decide for loan approval based on the applicant’s profile. Two types of risks are associated with the bank’s decision:
*If the applicant is likely to repay the loan, then not approving the loan results in a loss of business to the company
*If the applicant is not likely to repay the loan, i.e. he/she is likely to default, then approving the loan may lead to a financial loss for the company.

Our data  contains the information about loan application at the time of applying for the loan. It contains two types of scenarios:
* The client with payment difficulties: he/she had late payment more than X days on at least one of the first Y instalments of the loan in our sample,
* All other cases: All other cases when the payment is paid on time.

When a client applies for a loan, there are four types of decisions that could be taken by the client/company):
Approved: The Company has approved loan Application
Cancelled: The client cancelled the application sometime during approval. Either the client changed her/his mind about the loan or in some cases due to a higher risk of the client he received worse pricing which he did not want.
Refused: The company had rejected the loan (because the client does not meet their requirements etc.).
Unused offer: Loan has been cancelled by the client but on different stages of the process.

In this case study, we will perfrom EDA on the given two datasets i.e. : application_data  and previous_application . In order to understand how consumer attributes and loan attributees influence the tendency of default.
Business Objectives
 This case study aims to identify patterns which indicate if a client has difficulty paying their installments which may be used for taking actions such as denying the loan, reducing the amount of loan, lending (to risky applicants) at a higher interest rate, etc. This will ensure that  consumers capable of repaying the loan are not rejected. 
Identification of such applicants using EDA is the aim of this case study.
In other words, the company wants to understand the driving factors (or driver variables) behind loan default, i.e. the variables which are strong indicators of default. The company can utilize this knowledge for its portfolio and risk assessment.
![image](https://user-images.githubusercontent.com/87516451/229178568-2e9a7e02-8fd6-4e39-abae-575f45988a99.png)
