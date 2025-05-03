# 💼 Data Science Salaries Dashboard

This project presents an interactive dashboard built in Tableau, using the `ds_salaries.csv` dataset, to analyze global salary trends in the data science and tech industry.

## 📊 Dashboard Overview

The dashboard provides insights into:

- 💰 **Average Salary** by experience level, employment type, job title, and country
- 🏢 **Company Distribution** by size and location
- 🧑‍💻 **Employee Demographics** including top countries of residence and experience levels
- 🌍 **Geographic Salary Variance** across top contributing countries

## 🔍 Key Insights

- Full-time senior roles offer the highest compensation.
- Medium-sized companies dominate the tech hiring landscape.
- The U.S. and select European countries provide the top-paying roles.
- Most roles are full-time; part-time and freelance are rare.

## 📁 Dataset

The dataset used: [`ds_salaries.csv`](./ds_salaries.csv)

| Column Name         | Description                                      |
|---------------------|--------------------------------------------------|
| work_year           | Year of the salary record                        |
| experience_level    | Entry, Mid, Senior, Executive levels             |
| employment_type     | Full-time, Part-time, Contract, Freelance        |
| job_title           | Job title of the role                            |
| salary              | Annual salary (raw)                              |
| salary_currency     | Currency code                                    |
| salary_in_usd       | Standardized salary in USD                       |
| employee_residence  | Country of the employee                          |
| remote_ratio        | % of remote work allowed                         |
| company_location    | Company’s location                               |
| company_size        | Size of the company (S, M, L)                    |

