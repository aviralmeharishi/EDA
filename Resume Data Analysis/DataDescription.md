## 📊 Data Description

This dataset contains synthetic resume information designed for building and testing **resume scoring and job-fit models**. The data simulates candidate profiles including skills, education, past experience, and more.

### 🧱 Columns Overview

| Column Name       | Description                                                                 |
|-------------------|-----------------------------------------------------------------------------|
| `name`            | Fake candidate name generated using Faker                                   |
| `skills`          | List of technical and soft skills mentioned in the resume                   |
| `education`       | Educational qualifications (degree, institute, etc.)                        |
| `experience`      | Work experience details (companies, roles, duration)                        |
| `certifications`  | Any certifications listed in the resume                                     |
| `past_roles`      | Previously held job titles or relevant experience summaries                 |
| `projects_count`  | Number of projects completed by the candidate                               |
| `resume_text`     | Complete unstructured resume text (used for NLP-based processing)           |
| `job_fit_score`   | A synthetic score (0–1) indicating how well the resume fits a given role    |

---

### ⚠️ Notes

- All data is **synthetic** and was generated using the `Faker` library.
- The `resume_text` column is especially useful for **text preprocessing**, keyword extraction, and classification tasks.
- `job_fit_score` can serve as a **target variable** in regression/classification tasks related to resume quality or role match.

---

### 🧪 Use Cases

- Resume parsing and skill extraction  
- NLP-based job-role prediction  
- Job-fit scoring and resume ranking models  
- Streamlit apps for HR analytics demos  
