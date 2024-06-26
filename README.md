
# Lending Club Case Study

> The objective of this case study is to analyze a dataset of loan applicants to identify patterns and factors that influence loan default. By understanding these patterns, the finance company can make more informed lending decisions, minimize credit losses, and enhance overall profitability.


## Table of Contents

* [General Info](#general-information)

* [Technologies Used](#technologies-used)

* [Conclusions](#conclusions)

* [Acknowledgements](#acknowledgements)
  

## General Information

This project involves conducting an exploratory data analysis (EDA) on a dataset provided by a consumer finance company. The goal is to identify patterns and factors that indicate whether a loan applicant is likely to default. The insights derived from this analysis will help the company in making informed decisions to minimize credit loss.

- Background

    In the finance industry, lending decisions are critical as they directly impact the company's financial health. Approving loans to applicants who are likely to default can lead to significant financial losses. On the other hand, rejecting loans to applicants who are likely to repay can result in missed business opportunities. Therefore, an attempt is made to understand the factors that influence loan defaults.

- Business Probem

    The primary business problem addressed by this project is the identification of risky loan applicants who are likely to default. By identifying these applicants, the company can take preventive measures such as denying the loan, reducing the loan amount, or offering loans at higher interest rates to mitigate potential losses. 

- Dataset

    The dataset used in this project contains information about past loan applicants from 2007 to 2011. It includes various attributes related to the applicants' personal, financial, and loan details, as well as the status of the loan (fully paid, current, or charged-off). 

    The dataset includes key variables such as:
    - Applicant's demographic details (age, employment, etc.)
    - Financial information (annual income, debt-to-income ratio, etc.)
    - Loan details (amount, interest rate, purpose, etc.)
    - Loan status (fully paid, current, charged-off)


## Conclusions

- Debt consolidation and credit card repayment loans exhibit high default rates. Borrowers using loans for these purposes are likely under financial stress.

- Renters and mortgaged homeowners show higher default rates compared to homeowners without mortgages, indicating a correlation between financial obligations and default risk.

- Loans with longer terms (60 months) have higher default rates compared to shorter-term loans (36 months), suggesting that longer repayment periods increase the risk of financial instability.

- Loans graded "A" have low default rates, while those graded "F" and "G" have significantly higher default rates, indicating a strong relationship between borrower creditworthiness and default risk.

- Borrowers with higher annual incomes ($80K and above) show lower default rates, highlighting income as a significant predictor of repayment ability.

- Higher interest rates are associated with increased default rates, reflecting the higher risk profiles of borrowers with such loans.

- Higher DTI ratios are linked to higher default rates, highlighting the importance of managing debt relative to income.

- Longer employment histories correlate with higher loan amounts and lower default rates, suggesting job stability as a key factor in loan repayment.
  

## Technologies Used

- Python - 3.10.12
- Pandas - 2.0.3
- Matplotlib - 3.7.1
- Seaborn - 0.13.1
- Jupyter Notebook - 7.34.0


## Acknowledgements

- Anil Kumar Narayanan
- Sharwan Kumar


## Contact

Created by [@anilnarayanan]