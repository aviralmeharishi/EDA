# 🛒 MohKart Customer Segmentation - EDA Report

Welcome to the **Exploratory Data Analysis (EDA)** of **MohKart's customer data**, where we deep-dive into key customer attributes, purchasing patterns, and behavioral clusters to drive marketing and retention strategies.

---

## 📌 Project Objective

To explore and analyze customer transaction data from **MohKart**, with the goal of identifying valuable customer segments, risk zones, and loyalty patterns.

---

## 📊 Key Features

- Summary statistics across all columns with a custom `column_explorer()` function.
- Null value distribution & handling strategy.
- Data type-wise profiling (numerical & categorical).
- Min, Max, Mean, Median, and Std Dev insights for numerical columns.
- Frequency analysis for categorical variables.
- Sample value exploration for quick data intuition.

---

## 🧠 `column_explorer()` Function

This custom-built function inspects each column and returns a comprehensive report with:

- Data Type
- Missing Value Count and %
- Unique Value Count
- Sample Values
- For Numeric Columns:
  - Min, Max, Mean, Median, Std Dev
- For Categorical Columns:
  - Most Frequent Value & Its Frequency

---

## 🔍 Sample Output

| Column       | Data Type | Missing % | Unique Values | Min | Max | Mean | Top Freq |
|--------------|-----------|------------|----------------|-----|-----|------|-----------|
| Customer_Age | int64     | 0.0%       | 35             | 18  | 70  | 37.6 | -         |
| Gender       | object    | 0.0%       | 2              | -   | -   | -    | Male      |
| City         | object    | 2.3%       | 15             | -   | -   | -    | Bangalore |

---

## 📁 Files Included

- `MohKart Customer Segmentation.ipynb`: Jupyter notebook with full EDA workflow
- `column_explorer()` definition inside the notebook
- Ready-to-export summary DataFrame

---

## 🚀 How to Use

1. Clone the repo
2. Open the notebook in Jupyter or VSCode
3. Run all cells
4. Use `column_explorer(df)` to generate the full feature overview

---

## 🤝 Let's Connect

Built with ❤️ for clean data storytelling and impactful segmentation.


