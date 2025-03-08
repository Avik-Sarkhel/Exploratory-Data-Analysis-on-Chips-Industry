# QUANTIUM Job Simulation - Chips Industry EDA

## Overview
This project is part of the QUANTIUM job simulation on the Forage platform. It involves the exploratory data analysis (EDA) of the chips industry data to understand customer purchasing behavior, segment customers based on lifestage and spending habits, and analyze the effectiveness of store trials using control store selection methods.

## Objectives
### Task 1: Customer Segmentation and Brand Analysis
- Analyze customer purchase behavior in the chips industry.
- Identify top-selling chip brands.
- Segment customers based on lifestage and spending category (Premium, Budget, Mainstream).

### Task 2: Control Store Selection for Store Trials
- Identify suitable control stores for trial stores based on sales performance.
- Use similarity measures like Pearson correlation and magnitude distance to determine store matching.

## Datasets Used
- **Purchase Behaviour Dataset:** Contains customer loyalty card numbers, lifestage, and premium customer classification (72,637 records).
- **Transaction Data:** Includes transaction details, product information, store numbers, and total sales (264,836 records).

## Data Cleaning & Preprocessing
- Standardized company names to resolve inconsistencies.
- Merged datasets on 'Loyalty Card No' to enrich customer insights.
- Removed 1,418 incomplete records (French Fried Potato Chips with missing company names).
- Handled missing values and ensured data integrity.

## Exploratory Data Analysis (EDA)
### Key Insights
1. **Top 5 Chip Brands:** Kettle (16%) leads, followed by Smith’s (12%) and Doritos (11%).
2. **Customer Segmentation:** Older Singles/Couples (21%) are the largest buyers, followed by Retirees (19%).
3. **Spending Behavior:** Mainstream customers (39%) dominate, while premium customers (26%) form the smallest segment.

## Control Store Selection
- **Trial Period:** February 2019 – April 2019
- **Selection Criteria:** Total sales revenue, total customers, and average transactions per customer.
- **Methods Used:** Pearson correlation and magnitude distance formula.
- **Outcome:** Identified best-matching control stores to evaluate trial store performance.

## Tools & Technologies Used
- **Google Colab** (Python-based analysis)
- **Pandas, NumPy** (Data manipulation)
- **Matplotlib, Seaborn** (Data visualization)

## Conclusion
- Provided actionable insights into customer preferences and spending patterns.
- Successfully identified control stores to benchmark trial store performance.
- Findings support data-driven marketing and retail strategies in the chips industry.

## Contact
📧 Email: avik305sarkhel@gmail.com

🔗 QUANTIUM Job Simulation Link: https://www.theforage.com/simulations/quantium/data-analytics-rqkb  

📂 GitHub Repository: https://github.com/Avik-Sarkhel/Quantium-Job-Simulation.git

