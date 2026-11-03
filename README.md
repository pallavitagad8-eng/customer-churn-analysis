# Customer Churn Analysis

Analysis of customer churn to calculate churn rate, Customer Lifetime Value (CLV) and MRR loss, and to identify key behavioural drivers of churn.

## Files
- `Customer_Churn_Analytics_Report.pdf`: full analytics report with charts, key findings and business recommendations
- `customer_churn_cleaned.csv`: cleaned dataset (600 customers)

## Key Findings
- Baseline churn rate: 41.2% (247 of 600 customers)
- Estimated CLV: about INR 65,583 per customer
- MRR loss from churn: INR 1,87,320 (41.1% of total MRR)
- Month-to-month contracts churn at 59.8%, versus about 20% for One Year and Two Year contracts
- First-year customers churn the most (53.8%)
- Late payments and support tickets are the strongest churn signals
- UPI and Wallet users churn more than Card and Net Banking users

## Data Cleaning
Removed 5 duplicate rows, fixed 7 incorrect monthly charges, estimated 10 missing total charges and labelled 13 missing regions as "Unknown".

## Tools
Python, pandas, matplotlib, seaborn
