# Online Retail Sales Analysis

Analysis of online retail transactions (Dec 2010 to Dec 2011) to find top products, countries, customers, monthly trends and customer behaviour.

## Tools Used
- Python (Pandas, NumPy, Matplotlib, Seaborn)
- Jupyter Notebook

## Dataset
Online Retail transactions dataset (541,910 rows). Source: UCI Machine Learning Repository, Online Retail dataset.

The dataset is not included in this repository because of its size. To run the notebook, download it and update the file path in the `pd.read_csv(...)` line.

## Data Cleaning
- Removed duplicate rows
- Removed cancelled invoices and returns
- Removed rows with zero price
- Removed non-product rows (postage, manual entries, bank charges)
- Removed 2 very large orders that were cancelled later

## Key Findings
- After cleaning, the data has **522,362 transaction lines** with total revenue of about **10.02M**.
- The **United Kingdom** generates about **85%** of revenue (8.50M).
- Sales grow strongly in the last quarter: **September 1.03M, October 1.10M, November 1.45M** (peak). **February** is the weakest full month (0.51M).
- **Regency Cakestand 3 Tier** is the top product by revenue (174K). **World War 2 Gliders** has the highest quantity sold (54,951).
- About **65%** of customers with an ID are repeat customers.
- **Thursday** is the best sales day and **Sunday** the lowest. No transactions are recorded on Saturdays.

## Files
- `Online_Retail_Sales_Analysis.ipynb`: Full analysis with charts

## Author
Goutham R | [LinkedIn](https://linkedin.com/in/goutham06)
