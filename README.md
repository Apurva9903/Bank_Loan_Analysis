🏦 Bank Loan Analytics Project: End-to-End Financial Insights
📌 Project Overview

This project delivers an end-to-end analytical solution for evaluating a bank’s loan portfolio using SQL-driven analytics and Power BI visualization.
The objective is to monitor lending performance, assess portfolio health, and uncover borrower behavior trends that support data-driven credit and risk decisions.

The dashboard enables stakeholders to quickly identify:

Overall lending performance

Good vs. Bad loan distribution

Risk concentration across borrower segments

Seasonal and geographic lending trends

🛠️ Technical Stack

Data Analysis & Transformation: SQL (PostgreSQL / SQL Server)

Data Visualization: Power BI

Data Source: Bank_Loan_Data.csv (stored in the Data/ directory)

📊 Key Performance Indicators (KPIs)

The dashboard tracks five core financial KPIs critical to loan portfolio monitoring:

KPI	Value
Total Loan Applications	37.1K (MTD Growth: +7.5%)
Total Funded Amount	$425.5M (MTD Growth: +13.2%)
Total Amount Received	$461.7M
Average Interest Rate	12.1%
Average Debt-to-Income (DTI)	13.4%
🖥️ Dashboard Views
1️⃣ Summary View – Portfolio Health

Provides a high-level snapshot of loan performance:

Good Loans: 86%

Bad Loans: 14%

Identifies Charged-Off loans and total financial loss

Enables rapid risk assessment for senior management

📷 Preview:


2️⃣ Overview View – Trends & Demographics

Focuses on macro-level trends and borrower insights:

Monthly Trends:
Loan disbursements show steady growth with a clear Q4 peak

Geographic Distribution:
Interactive state-level map highlights high-volume regions

Loan Purpose Analysis:
Debt Consolidation is the leading reason for loan applications

3️⃣ Details View – Granular Loan Data

Allows analysts to drill down to individual loan records, including:

Loan sub-grades

Employment length

Installment amount

Interest rate and DTI

Loan status

This view supports audits, investigations, and targeted risk analysis.

🔍 Key Insights & Findings
📉 Risk Assessment

86% of loans are performing well, indicating a strong portfolio

The 14% Bad Loan rate highlights opportunities to improve underwriting

Certain loan sub-grades show higher default risk and require tighter controls

👤 Borrower Profile

Borrowers with 10+ years of employment form the largest and most stable segment

These customers contribute significantly to predictable revenue

📆 Seasonality

Loan applications increase steadily throughout the year

Q4 shows the highest demand, suggesting the need for enhanced liquidity planning

🏠 Housing Impact

Most applicants fall under Rent or Mortgage categories

Very few borrowers fully own homes

Housing status correlates strongly with the average DTI of 13.4%

📂 Repository Structure
Bank_Loan_Analysis/
│
├── Data/
│   └── Bank_Loan_Data.csv
│
├── SQL/
│   └── KPI_Calculations.sql
│
├── PowerBI/
│   └── Bank_Loan_Dashboard.pbix
│
├── Summary_Dashboard.png
│
└── README.md


🚀 Business Value

This project demonstrates how data analytics can drive smarter lending decisions by:

Improving credit risk visibility

Identifying high-risk borrower segments

Supporting seasonal liquidity planning

Enhancing portfolio profitability and stability

📌 Future Enhancements

Predictive modeling for loan default risk

Customer segmentation using clustering techniques

Automated data refresh using SQL pipelines

Integration with real-time banking systems

🔗 Dashboard Example:
![image alt](https://github.com/Apurva9903/Bank_Loan_Analysis/blob/5b6b45269000f6404ea601884bdae9e27fe3e47f/Summary_Dashboard.png)
