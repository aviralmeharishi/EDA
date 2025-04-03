# Chocolate Sales Analysis

## Overview
This project analyzes chocolate sales across different countries, providing insights into sales performance by salesperson, product type, and shipment volumes. The dataset contains records of sales transactions, including revenue, units shipped, and locations.

## Dataset Description
The dataset consists of **1,094 records** with the following columns:

| Column Name      | Data Type | Description |
|-----------------|-----------|-------------|
| `Sales Person`  | String    | Name of the salesperson responsible for the sale. |
| `Country`       | String    | Country where the sale took place. |
| `Product`       | String    | Type of chocolate product sold. |
| `Date`          | String    | Date of the sale (format: DD-MMM-YY). |
| `Amount`        | String    | Revenue generated from the sale (contains `$` symbol). |
| `Boxes Shipped` | Integer   | Number of boxes shipped. |

## Data Cleaning Steps
- Convert `Date` column to a proper datetime format.
- Convert `Amount` column to a numeric format after removing the `$` symbol.
- Handle any missing or inconsistent data if found.

## Analysis Goals
- Identify top-performing salespersons and products.
- Analyze sales trends over time.
- Compare sales performance across different countries.
- Assess the correlation between revenue and boxes shipped.

## Tools & Technologies Used
- **Python (pandas, matplotlib, seaborn)** for data analysis and visualization.
- **Power BI / Tableau** for interactive dashboarding.

## Future Enhancements
- Implement machine learning models for sales forecasting.
- Develop an automated reporting system using Streamlit.

## How to Use
1. Load the dataset into a Python environment (e.g., Pandas DataFrame).
2. Perform necessary preprocessing and analysis.
3. Visualize insights using Power BI or other visualization tools.

---

### Author
**Aviral Meharishi**  
GitHub: [aviralmeharishi](https://github.com/aviralmeharishi)  
Email: aviralmeharishi@gmail.com

