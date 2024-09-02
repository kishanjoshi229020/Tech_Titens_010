![image](https://github.com/user-attachments/assets/6a425d0b-9994-4e6b-83ed-c10ac75fef71)

The bank wants to improve their services. For instance, the bank managers have only vague idea, who is a good client (whom to offer some additional services) and who is a bad client (whom to watch carefully to minimize the bank loses). Fortunately, the bank stores data about their clients, the accounts (transactions within several months), the loans already granted, the credit cards issued The bank managers hope to improve their understanding of customers and seek specific actions to improve services. A mere application of a discovery tool will not be convincing for them.

<div align="center">
<h1>DashBoard</h1>
</div>
<img src="https://github.com/user-attachments/assets/0b6c6e3d-0d68-4f2d-9d8f-9f111acd3355" alt="Sample Image" style="max-width: 100%;">

Client Classification and Economic Disparity Analysis for Financial Risk Management
Description
This project analyzes bank client data—including transactions, loans, and credit cards—to classify clients who may be at risk of default. Additionally, the project examines economic disparities across districts and identifies patterns of loan risk to derive insights that can enhance loan approval processes.

Key Features:
Client classification based on financial behavior.
Analysis of economic disparities by district to tailor loan products.
Identification of loan risk patterns.
Recommendations for improving loan approval processes based on findings.
Project Structure
1. Data Understanding
Data Sources: Bank client data, transactions, loans, credit cards, and district information.
Goal: Understand relationships between datasets, examine attribute names, content, and ranges.
2. Data Preparation
Renaming Attributes: Ensure column names are meaningful and consistent across datasets.
Extracting Key Information:
Extract client age and sex from birth numbers.
Handling Missing Data:
Replace missing values in District D69 with the average values from other districts.
Sanctions Information: Identify accounts with a history of sanctions by analyzing transaction data.
3. Analysis
a. Client Classification
Objective: Identify clients at risk of default based on account balance.
Methodology: Determine how many times the balance in their account fell below industry standards and flag clients accordingly.
b. Economic Disparities
Objective: Analyze salary and balance disparities across different districts.
Methodology:
Compare average salaries and account balances across districts.
Highlight regions with higher and lower average salaries, such as:
High-salary districts: 'Hl.m. Praha', 'Mlada Boleslav', 'Plzen - mesto', etc.
Balanced districts: Chomutov, Zlin, Pardubice, etc.
Tailor loan products based on the economic profile of each district.
c. Risk Patterns
Objective: Identify risk patterns in loan performance.
Key Risk Indicators:
Loan amount.
Loan duration.
Insight: Larger and longer-term loans pose higher risks, requiring stricter credit checks and potentially more collateral.
Code Sections
1. Data Understanding
Loading and Cleaning Datasets:
Load client, transaction, loan, credit card, and district data.
Clean datasets to ensure proper relationships between them.
2. Data Preparation
Renaming Columns:
Ensure columns have meaningful names.
Extracting Information:
Extract age and gender information from birth numbers.
Handling Missing Data:
Replace missing values in districts with averages.
3. Client Classification
Classifying Clients:
Identify clients who are at risk of default based on their account balances and how often the balance falls below the threshold.
4. Economic Disparities
Analyzing District-Level Disparities:
Compare average salaries and balance trends across districts to highlight economic differences and adapt loan offerings accordingly.
5. Risk Patterns
Loan Performance Analysis:
Analyze the risk of loans based on the amount and duration to identify high-risk loans and improve the bank's risk management strategies.

