# 📊 QUANTIUM Job Simulation – Chips Industry EDA

This project is part of the **QUANTIUM Job Simulation** on the Forage platform. It involves detailed **exploratory data analysis (EDA)** on chips industry data to:

- Understand customer purchase behavior  
- Segment customers based on **lifestage** and **spending habits**  
- Analyze the effectiveness of store trials by selecting appropriate control stores using similarity measures

---

## 🧠 Project Overview

The main goal of this simulation is to extract actionable insights from transactional data and customer profiles. This project is split into **two core tasks** focused on marketing analytics and retail experimentation.

---

## 📁 Files Included

| File Name                           | Description                                                      |
|------------------------------------|------------------------------------------------------------------|
| `Quantum Data analysis ppt.pdf`    | Presentation summarizing analysis and key takeaways             |
| `Quantium_Da_Task_1_and_2.ipynb`   | Jupyter Notebook with full Python-based EDA for both tasks      |
| `README.md`                        | This project overview file                                       |

---

## 🎯 Objectives

### ✅ Task 1: Customer Segmentation & Brand Insights
- Analyze customer purchase behavior in the chips industry  
- Identify top-selling chip brands  
- Segment customers by **lifestage** and **spending category** (Premium, Budget, Mainstream)

### ✅ Task 2: Control Store Selection for Store Trials
- Select control stores for trial evaluation based on store similarity  
- Use **Pearson correlation** and **magnitude distance** to measure performance match  
- Evaluate sales impact during the **trial period (Feb 2019 – Apr 2019)**

---

## 💾 Datasets Used

- **Purchase Behaviour Dataset**: 72,637 records including Loyalty Card No, Lifestage, and Premium Category  
- **Transaction Data**: 264,836 records with store-level transactions, products, and total sales

---

## 🧹 Data Cleaning & Preprocessing

- Standardized company names via mapping (e.g., Kettle, Smith’s, Doritos)  
- Merged datasets using `Loyalty Card No`  
- Removed 1,418 rows with missing product/company info  
- Checked for missing/null values and ensured consistency in formats

---

## 📈 Exploratory Data Analysis (EDA)

Detailed visualizations and groupings were used to understand:

- Purchase volume by brand  
- Segmentation by age/lifestage  
- Premium vs. budget purchase behavior  
- Trial store trends across the pre- and post-trial periods

---

## 💡 Key Insights

- **Top 5 Chip Brands**:  
  - Kettle (16%), Smith’s (12%), Doritos (11%), Pringles (9%), Twisties (8%)

- **Customer Segments**:  
  - Largest buyer group: **Older Singles/Couples** (21%)  
  - Next: **Retirees** (19%)

- **Spending Category**:  
  - **Mainstream**: 39%  
  - **Budget**: 35%  
  - **Premium**: 26%

---

## 🏪 Control Store Selection

- **Trial Period**: February 2019 – April 2019  
- **Metrics Used**: Total sales, number of customers, average transactions per customer  
- **Similarity Methods**:
  - 📈 **Pearson Correlation** – to match trend patterns  
  - 🧮 **Magnitude Distance** – to match scale of metrics  
- **Outcome**: Successfully identified control stores for Store 77, 86, and 88

---

## 🛠️ Tools & Technologies Used

- 🐍 **Python (Google Colab)**  
- 📊 **Pandas, NumPy** – for data handling and transformation  
- 📈 **Matplotlib, Seaborn** – for visualizations  
- 🧠 **Forage QUANTIUM Simulation** – learning platform

---

## ✅ Conclusion

- Discovered key drivers of customer behavior across brand, age, and spending category  
- Demonstrated analytical thinking through control store selection logic  
- Helped simulate a real-world retail data science task using clean, reproducible code

---

## 📧 Contact

- **Email**: [avik305sarkhel@gmail.com](mailto:avik305sarkhel@gmail.com)  
- **LinkedIn**: [https://www.linkedin.com/in/avik-sarkhel](https://www.linkedin.com/in/avik-sarkhel)

---

## 🚀 Feel Free to Explore or Fork

This project is a great foundation for learning:

- Retail data analytics  
- Customer segmentation  
- A/B testing methodology  
- Python + EDA best practices

> ⭐ If this project helped or inspired you, leave a star and feel free to connect!
