Loan Default Risk Analysis – EDA

Project Overview

This project performs Exploratory Data Analysis (EDA) on loan application data to identify patterns influencing default risk. The goal is to support data driven 
lending decisions, ensuring eligible clients are not rejected while minimizing financial losses.

Business Problem

Financial institutions face two main risks:

Rejecting creditworthy applicants → loss of business

Approving risky applicants → potential financial loss

The analysis aims to uncover key driver variables that indicate payment difficulties, helping improve credit risk assessment and operational decisions.

Dataset

application_data.csv – Applicant demographic, financial, and employment information

previous_application.csv – Historical loan application records

columns_description.csv – Data dictionary

Target variable: whether a client had payment difficulties.

Tools & Techniques

Python (Pandas, NumPy, Matplotlib, Seaborn)

Data cleaning & missing value handling

Univariate & bivariate analysis

Correlation analysis & visualization

Key Insights

Lower income and higher loan to income ratio → higher default risk

Previous loan refusals correlate with payment difficulties

Certain employment categories show elevated default probability

Business Impact

Support riskmbased lending and pricing strategies

Improve credit approval criteria for high risk applicants

Incorporate historical loan behavior into operational and portfolio decisions
