# Online Retail II - Exploratory Data Analysis (Week 1 Task)

## Overview
This project performs Exploratory Data Analysis (EDA) on the Online Retail II dataset 
as part of the ITSimplera Institute Data Analysis Internship (Week 1).

## Objective
Analyze customer purchase behavior for a retail company to support future development 
of a recommendation system, by identifying data quality issues, top products, 
top countries, and revenue trends.

## Dataset
- **Source:** [UCI Online Retail II Dataset](https://archive.ics.uci.edu/ml/datasets/Online+Retail+II)
- Real transaction data from a UK-based online retailer (2009–2011)

## Key Steps
- Data loading and structure inspection
- Missing values & duplicate detection
- Top 10 products by quantity and revenue
- Sales performance by country
- Monthly revenue trend analysis
- Correlation heatmap
- Outlier detection using box plots
- Business insights derived from findings

## Key Findings
- United Kingdom contributes ~84.94% of total revenue
- ~22.77% of records are missing Customer ID
- Clear seasonal spike in revenue toward Nov–Dec
- Revenue correlates more with Quantity than Price

## Files
- `Week1_EDA_OnlineRetailII.ipynb` — Full analysis notebook
- `Week1_EDA_Documentation.docx` — Step-by-step documentation with screenshots

## Tools Used
Python, Pandas, NumPy, Matplotlib, Seaborn, Google Colab
