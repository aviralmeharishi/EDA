# 🛒 Sales Analysis for Big Mart Outlets  

## 📌 Project Overview  
The data scientists at **BigMart** have collected 2013 sales data for **1559 products** across **10 stores** in different cities. The goal of this project is to build a **predictive model** to estimate sales for each product at a particular outlet.  

By analyzing this model, **BigMart** aims to understand the key properties of **products and outlets** that drive higher sales.  

---

## 📂 Dataset Information  
We have two datasets:  
- **Train Dataset (8523 records)** - Contains both input features and the target variable (**Sales**).  
- **Test Dataset (5681 records)** - Contains only input features; we need to predict sales for this dataset.  

---

## 📑 Data Dictionary  
The dataset consists of the following columns:  

| Feature Name              | Description |
|---------------------------|-------------|
| **Item_Identifier**       | Unique product ID |
| **Item_Weight**           | Weight of the product |
| **Item_Fat_Content**      | Whether the product is low-fat or regular |
| **Item_Visibility**       | The percentage of total display area allocated to the product in the store |
| **Item_Type**             | Category of the product |
| **Item_MRP**              | Maximum retail price (MRP) of the product |
| **Outlet_Identifier**     | Unique store ID |
| **Outlet_Establishment_Year** | The year in which the store was established |
| **Outlet_Size**           | The size of the store (Small/Medium/Large) |
| **Outlet_Location_Type**  | The type of area the store is located in (Tier 1, 2, 3) |
| **Outlet_Type**           | The type of store (Supermarket/Grocery Store, etc.) |
| **Item_Outlet_Sales**     | **(Target Variable)** Sales of the product in the store |

---

## 🛠 Steps Completed  

### 🔍 1. Exploratory Data Analysis (EDA)  
- **Data Summary** - Checked for missing values, outliers, and basic statistics.  
- **Data Visualization** - Used **histograms, box plots, and scatter plots** to analyze distributions and relationships.  
- **Target Variable Distribution** - Analyzed the spread of sales values.  

### 🏗 2. Data Preprocessing  
- **Missing Value Treatment** - Imputed missing values for `Item_Weight` and `Outlet_Size`.  
- **Feature Engineering** - Created new features and modified existing ones for better predictive power.  
- **Encoding Categorical Variables** - Applied **Label Encoding & One-Hot Encoding** for categorical data.  

### 📊 3. Statistical Tests  
- Conducted **t-tests and ANOVA** to check the significance of categorical features.  
- Performed **correlation analysis** to understand relationships between numerical features.  

---

## 🚀 Next Steps  
🔹 **Feature Selection & Engineering** – Identifying the most relevant features.  
🔹 **Model Selection** – Trying different regression models for prediction.  
🔹 **Hyperparameter Tuning** – Optimizing model performance.  
🔹 **Evaluation Metrics** – Using **R², RMSE, MAPE**, and more to assess the model.  

---

## 📌 Technologies Used  
- 🐍 Python (Pandas, NumPy, Scikit-Learn)  
- 📊 Matplotlib & Seaborn (for Visualization)  
- 🏗 Streamlit (for Deployment)  

---

## 📬 Contact  
👤 **Avi**  
📧 [aviralmeharishi@gmail.com]



---

### 🚀 Stay Tuned for More Updates!  



![image](https://github.com/user-attachments/assets/f6c325d0-ba35-496d-858c-07293156f37f)
![image](https://github.com/user-attachments/assets/8340369a-a699-4d32-9c5a-2a8b78c73c1d)
