| Column Name          | Data Type | Description                                 |
|----------------------|-----------|---------------------------------------------|
| Unnamed: 0           | int64     | Index column (likely auto-generated)        |
| work_year            | int64     | The year in which the salary was reported   |
| experience_level     | object    | Experience level of the employee            |
| employment_type      | object    | Type of employment (e.g., full-time)        |
| job_title            | object    | Job title of the employee                   |
| salary               | int64     | Employee salary in original currency        |
| salary_currency      | object    | Currency of the reported salary             |
| salary_in_usd        | int64     | Salary standardized to USD                  |
| employee_residence   | object    | Country of residence of the employee        |
| remote_ratio         | int64     | % of remote work (0, 50, 100)               |
| company_location     | object    | Country where the company is located        |
| company_size         | object    | Company size (S: Small, M: Medium, L: Large)|

# **Column Description**

- **Unnamed: 0**: Auto-generated index column.
- **work_year**: The year in which the salary data was collected or reported.
- **experience_level**: Represents the level of expertise of the employee (e.g., EN=Entry-level, MI=Mid-level, SE=Senior, EX=Executive).
- **employment_type**: Type of employment like FT (Full-time), PT (Part-time), CT (Contract), FL (Freelance).
- **job_title**: The designation or job role of the employee (e.g., Data Scientist, ML Engineer).
- **salary**: The annual salary amount in the original currency.
- **salary_currency**: The currency code in which the salary is paid (e.g., USD, EUR, GBP).
- **salary_in_usd**: The salary converted to US dollars for standard comparison.
- **employee_residence**: The country where the employee resides.
- **remote_ratio**: The percentage of remote work allowed for the employee (0 = no remote, 50 = hybrid, 100 = fully remote).
- **company_location**: The country where the employee's company is headquartered.
- **company_size**: The size of the company categorized as S (Small), M (Medium), or L (Large).
