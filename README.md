# Banking Transaction Analysis 🏦

## Overview
Analysis of banking transactions using PySpark 
to detect suspicious high-value activity.

## Tools & Technologies
- Python 3.x
- PySpark (Apache Spark)
- Pandas
- Jupyter Notebook

## Dataset
- 1000 synthetic banking transactions
- 50 unique accounts
- Date Range: January 2024 – December 2024

## Tasks Performed
1. Load Transaction Dataset
2. Detect High-Value Transactions (Threshold: 40,000)
3. Group by Account
4. Calculate Total Balance

## Results
- Suspicious Transactions: 194
- Completed Suspicious Transactions: 67
- Suspicious Accounts: 27
- Highest Balance Account: ACC0017 (878,654.32)

## Output Files
- suspicious_transactions.csv
- account_summary.csv

## How to Run
1. Install dependencies: pip install -r requirements.txt

3. Launch Jupyter Notebook:
jupyter notebook

4. Open banking_transaction_analysis.ipynb

5. Run all cells
