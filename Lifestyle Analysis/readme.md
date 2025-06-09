# 🍎 Obesity Risk Prediction: An Exploratory Data Analysis

## 📊 Unveiling the Factors Behind Obesity Risk!

This repository contains an in-depth **Exploratory Data Analysis (EDA)** of a dataset aimed at understanding and predicting obesity risk. Through data preprocessing, visualization, and statistical analysis, we explore the relationships between lifestyle habits and health conditions, leading to **actionable insights**.

---

## 📁 Installation

Clone the repository:

```bash
git clone <your-repo-link>
cd <your-repo-name>
```

Open the Jupyter Notebook:

```bash
jupyter notebook "Obesity Risk Prediction.ipynb"
```

---

## 📝 Project Structure

```bash
📂 obesity-risk-prediction/
├── Obesity Risk Prediction.ipynb     # Main Jupyter Notebook
├── README.md                         # Project overview
└── data/                             # (Optional) Folder for dataset files
```

---

## 👣 EDA Steps Followed

### 📥 Data Loading & Initial Inspection

- Loaded dataset into a pandas DataFrame  
- Used `df.head()`, `df.info()`, and `df.describe()`  
- Checked dataset shape with `df.shape`

### 🧹 Handling Missing Values

- Identified missing values using `df.isnull().sum()`  
- Applied imputation or dropped data where needed

### 🧼 Data Cleaning & Preprocessing

- Renamed columns (for readability)  
- Removed duplicates  
- Fixed inconsistent spellings in categorical data

### 🔍 Feature Understanding & Data Types

- Separated categorical and numerical features  
- Explored unique values in categorical columns

### 📈 Ordinal Encoding of Categorical Features

Used `sklearn.preprocessing.OrdinalEncoder` with defined order for:

- `snacking_freq`: Never < Sometimes < Frequently  
- `time_spend_on_tech`: Low Usage < Moderate Usage < High Usage  
- `MTRANS`: Walking < Public_Transport < Car  
- `health_condition`: Underweight < Healthy < Overweight < Obese < Severely Obese

### 📊 Exploratory Data Analysis (EDA)

#### 🔹 Univariate Analysis
- Histograms and KDE plots for numerical features  
- Count plots for categorical variables

#### 🔹 Bivariate Analysis
- Box plots (numerical vs categorical)  
- Scatter plots (numerical vs numerical)  
- Bar plots (categorical vs numerical)

#### 🔹 Correlation Analysis
- Correlation matrix with `df.corr()`  
- Heatmap via `seaborn.heatmap()`

### 🛠️ Feature Engineering (If Applicable)

- Derived features like BMI (if height/weight were available)  
- Created interaction features from habits

---

## 🌟 Top 10 Inferences from the EDA

1. **Smoking's Lesser Role?** 🚬➡️📉  
   Smoking (`SMOKE`) showed limited differentiation between health conditions — not a dominant factor.

2. **Water is Wealth!** 💧💪  
   Higher `water_consumption` is strongly associated with being 'Healthy'.

3. **Calories Count, But How?** 🍔🤔  
   `calorie_monitoring` does not clearly distinguish healthy and overweight groups.

4. **Activity Levels Matter!** 🏃‍♀️🏆  
   Increased `physical_activity` shows a clear link to better health outcomes.

5. **Tech Time & Tummy Size** 💻🛋️  
   High `time_spend_on_tech` usage appears more often in the 'Overweight' category.

6. **Alcohol's Subtle Influence** 🍻⚖️  
   The relationship of `alcohol_consump` with health status is subtle and may need deeper analysis.

7. **MTRANS & Mobility Patterns** 🚌🚶‍♀️  
   Transportation mode choices may reflect active vs. sedentary lifestyles affecting weight.

8. **Snacking Frequencies Tell a Tale** 🍿🔄  
   Even moderate `snacking_freq` shows variation across health conditions — it matters!

9. **Interconnected Lifestyle Factors** 🕸️🔗  
   Obesity isn’t caused by a single behavior — it's a blend of inactivity, screen time, and diet.

10. **Targeted Interventions Potential!** 🎯💡  
    Programs focusing on reducing screen time and increasing physical activity could be effective in tackling obesity.

---

## 🤝 Contributions

Feel free to **fork** this repository, **explore the dataset**, and contribute your own insights, notebooks, or enhancements!

> Let’s fight obesity — one dataset at a time 💪
