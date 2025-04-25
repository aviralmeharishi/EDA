# 💰 Salary Secrets Unlocked: Analyzing Global Employee Compensation 📊

## 🚀 Project Overview

Dive deep into the world of employee salaries! This project analyzes a comprehensive dataset to uncover patterns, trends, and correlations in compensation across various industries, job roles, and regions. 🌍

**Goal:** To understand the factors influencing salaries (like experience, remote work, company size) and provide valuable insights for:

* Salary Trend Analysis 📈
* Predictive Modeling 🔮
* Data-Driven Decision Making ✅

## 💾 Dataset Description

The analysis is based on the `ds_salaries.csv` dataset, containing information about employee compensation. Key fields include:

| Field                 | Description                                                                |
| :-------------------- | :------------------------------------------------------------------------- |
| `work_year`           | The year of employment.                                                    |
| `experience_level`    | Employee experience level (e.g., Entry, Mid, Senior, Executive).           |
| `employment_type`     | Type of employment (e.g., Full-time, Part-time, Contract).                 |
| `job_title`           | Job title or position.                                                     |
| `salary`              | Salary amount in local currency.                                           |
| `salary_currency`     | Currency of the salary.                                                    |
| `salary_in_usd`       | Equivalent salary amount in USD (Used for standardized analysis).          |
| `employee_residence`  | Employee's residence location.                                             |
| `remote_ratio`        | Percentage of remote work allowed (0%, 50%, 100%).                         |
| `company_location`    | Company's location.                                                        |
| `company_size`        | Company size (Small, Medium, Large).                                       |

## 🔍 Analysis Highlights

This project performs a thorough Exploratory Data Analysis (EDA) and preprocessing:

1.  **Data Loading & Initial Exploration:** Importing necessary libraries (`pandas`, `numpy`, `seaborn`, `matplotlib`) and understanding the dataset's structure (`info`, `describe`, `shape`).
2.  **Univariate Analysis:** Examining individual variable distributions (KDE plots for salaries, count plots for categorical features like experience level, company size, etc.).
3.  **Bivariate Analysis:** Exploring relationships between variables, particularly how different factors correlate with `salary_in_usd` (using regression plots and bar charts).
4.  **Correlation Analysis:** Calculating and visualizing correlations between numerical features.
5.  **Data Cleaning:**
    * Identifying and removing duplicate entries (42 duplicates found and dropped).
    * Checking for null values (none found).
    * Analyzing outliers (identified but kept as they represent potentially valid high salaries).

## 🛠️ Technologies Used

* Python 3
* Pandas
* NumPy
* Seaborn
* Matplotlib
* Jupyter Notebook

## ✨ Key Findings & Inferences

* **Salary Standardization:** `salary_in_usd` provides a better basis for comparison across different currencies.
* **Experience Pays:** Senior-level (SE) employees generally command higher salaries.
* **Employment Type Matters:** Full-time (FT) roles are the most common and often associated with higher pay compared to other types.
* **Company Size Influence:** Larger companies tend to offer higher salaries, though medium-sized companies are most represented in the dataset.
* **Remote Work Impact:** Fully remote (100%) roles show competitive salaries, while hybrid (50%) roles surprisingly showed lower average salaries in this dataset compared to fully in-office (0%).
* **Top Earners:** Job titles like 'Head of Data' and 'Analytics Lead' showed the highest average salaries.
* **Currency Advantage:** Salaries denoted in USD tend to be higher on average.
* **Recent Data:** The year 2022 has the most data points, indicating more recent salary information.

## ▶️ How to Use

1.  Ensure you have Python and the listed libraries installed.
2.  Clone or download the repository containing the `SALARIES.ipynb` notebook and the `ds_salaries.csv` file.
3.  Run the Jupyter Notebook to see the full analysis and visualizations.

---

*This README provides a high-level overview. For detailed code and visualizations, please refer to the `SALARIES.ipynb` notebook.*
