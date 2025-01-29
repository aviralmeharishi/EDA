# Student Academic and Placement Dataset

This repository contains a dataset that includes information about students' academic performance, their training experiences, and placement status. The dataset is used to explore various factors that might impact students' success in placements, such as CGPA, internships, and soft skills.

## Dataset Overview

The dataset includes the following features:

| Feature                    | Description                                                                                      | Emoticon    |
|----------------------------|--------------------------------------------------------------------------------------------------|-------------|
| **CGPA**                   | Overall grades achieved by the student.                                                          | 🎓         |
| **Internships**            | Number of internships the student has participated in.                                           | 💼         |
| **Projects**               | Number of projects the student has completed.                                                    | 📚         |
| **Workshops/Certifications**| Online courses and certifications opted by students to enhance their skills.                     | 🎓📜        |
| **AptitudeTestScore**      | Score obtained in aptitude tests, which assess quantitative and logical thinking in recruitment. | 🧠         |
| **SoftSkillRating**        | Rating for communication skills, essential for placements and professional growth.              | 💬         |
| **ExtraCurricularActivities**| Reflects the student's engagement in activities outside of academics.                           | ⚽🎭        |

## Current Progress

### 1. **Exploratory Data Analysis (EDA)**

At this stage, the project has focused on conducting exploratory data analysis (EDA) to better understand the dataset and its characteristics. The following steps have been taken as part of the EDA:

- **Data Cleaning and Preprocessing**: 
   - Checked for missing values and handled them appropriately (imputation or removal).
   - Examined the data types and converted them as needed to ensure they align with their intended use.

- **Visualizations**:
   - **Histograms and Box Plots**: Used to visualize the distribution and detect any outliers in the data.
   - **Correlation Matrix**: Created to understand how different numerical features are related to each other.
   - **Pair Plots**: Examined relationships between pairs of features like "Projects" vs. "Internships" to spot any patterns.

- **Scaling and Encoding**: 
   - **Scaling**: Since many machine learning algorithms work best when features have similar scales, we applied scaling techniques like **StandardScaler** to scale numerical features like CGPA, Aptitude Test Score, and others to have a mean of 0 and a standard deviation of 1.
   - **Encoding**: For categorical features (e.g., "Internships" and "ExtraCurricularActivities"), we applied encoding techniques like **Label Encoding** to convert them into numerical format so that they can be used in machine learning models. This ensures that categorical data can be processed by algorithms that require numerical inputs.

The main goal of the EDA was to get a sense of the data's structure and any initial patterns or anomalies. Based on this analysis, we can make informed decisions about the next steps, including feature engineering and model building.

## Installation

To work with the dataset and analysis, you'll need to have the following Python libraries installed:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

Gist Of Analysis

Correlation In Data
![Screenshot 2025-01-30 003721](https://github.com/user-attachments/assets/59994d14-c33d-4cf8-ace9-71a92b1bd282)

Univariate Analysis
![Screenshot 2025-01-29 231951](https://github.com/user-attachments/assets/09a5f12d-06fb-46d1-867f-3b57b5b8166e)

Multivariate Analysis
![Screenshot 2025-01-30 003146](https://github.com/user-attachments/assets/f32ff83b-019b-42f2-b84d-b202b2236b33)


