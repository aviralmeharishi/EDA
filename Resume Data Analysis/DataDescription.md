## 📄 Dataset Description

This dataset contains raw resume data collected for exploratory analysis and potential use in resume scoring and job-fit modeling.

### 🔢 Shape of Data
- **Total Rows**: 3500+ (approx)
- **Total Columns**: 5

### 🧱 Column-wise Description

| Column Name       | Description                                                                 |
|-------------------|-----------------------------------------------------------------------------|
| `ID`              | Unique identifier for each resume                                           |
| `Name`            | Candidate's full name                                                       |
| `Resume`          | Raw resume text containing skills, experience, education, and projects      |
| `Category`        | Job domain or role the resume is associated with (e.g., Data Science, HR)   |
| `Resume_text`     | Resume in text format (rich formatting version of the plain text resume)    |

> 📝 Note: The `Resume` column is used for NLP analysis, skill extraction, and text-based scoring.

---

### ⚠️ Observations

- The dataset contains **unstructured text** which requires preprocessing (lowercasing, punctuation removal, stopword filtering).
- Some resumes are lengthy and detailed, while others are short and may lack clarity.
- `Category` is useful as a target variable for classification tasks.

---

### 🎯 Use Cases Enabled by This Dataset

- Resume parsing and keyword extraction  
- Job role classification using NLP  
- Resume scoring based on skill-job match  
- Clustering resumes by profile similarity  

