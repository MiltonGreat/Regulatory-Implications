# IRB Credit Risk Modeling System

A Basel III-Compliant Framework for Probability of Default (PD) and Regulatory Capital Calculation

### Project Overview

This project implements an Internal Ratings-Based (IRB) credit risk system that:

- Predicts Probability of Default (PD) using machine learning
- Calculates Risk-Weighted Assets (RWA) per Basel III regulations
- Simulates stress scenarios (recession, financial crises)
- Generates risk grades and capital adequacy reports

Designed for banks and financial institutions to automate regulatory capital requirements under Basel III standards.

### Dataset

The dataset contains financial and demographic information related to credit applicants. The key features used in this model include:

- Credit History – Previous loan repayment behavior.
- Purpose – The reason for applying for credit.
- Savings – Amount of savings available.
- Amount – Loan amount requested.
- Duration – Loan repayment period.

The target variable is Credit Risk (Good/Bad Credit), where 1 represents bad credit and 0 represents good credit.

### Methodology

The project follows a structured approach to building a credit scorecard:

1. Data Preprocessing – Handling missing values, feature encoding, and binning.
2. Train PD Model & Calculate Capital.
3. Run Stress Tests.
4. Generate Reports.

### Insights & Limitations

#### Strengths:
- Regulatory Compliance: Follows Basel III capital calculation standards.
- Explainability: WoE bins and risk grades make model decisions transparent.

#### Limitations:
- Stress test results may need debugging (capital decreases under stress).
- Assumes fixed LGD (45%) – could be modeled dynamically.

### Conclusion

While the framework provides a robust foundation for internal ratings-based approaches, its true value will emerge through iterative refinement using real-world portfolio data. The project demonstrates how machine learning and regulatory finance can converge to create smarter risk management systems.

### Source

![German Credit Data from Kaggle](https://www.kaggle.com/datasets/varunchawla30/german-credit-data)
