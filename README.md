# employee_salary_predications
# 💼 HR Job Salary Prediction Analytics Project
Welcome to the HR Job Salary Prediction Analytics Project repository! 🚀
This project explores a global job salary dataset to uncover actionable HR insights — covering salary trends, workforce distribution, remote work patterns, and compensation analysis. Designed as a portfolio project, it highlights practical skills in data analytics, SQL-based reporting, and interactive dashboarding.

---

## 📖 Project Overview
This project analyzes a dataset of global job salary records containing fields across multiple industries, locations, and job titles with the following fields:

| Column | Description |
|---|---|
| `job_title` | Title of the job role |
| `experience_years` | Number of years of experience |
| `education_level` | Highest education qualification (High School, Diploma, Bachelor, Master, PhD) |
| `skills_count` | Number of skills the employee possesses |
| `industry` | Industry sector of employment |
| `company_size` | Size of the company (Startup, Small, Medium, Large, Enterprise) |
| `location` | Country of employment |
| `remote_work` | Work arrangement (Remote, Onsite, Hybrid) |
| `certifications` | Number of professional certifications held |
| `salary` | Annual salary in USD |

**Job Titles covered:** AI Engineer, Data Analyst, Frontend Developer, Business Analyst, Product Manager, Backend Developer, Machine Learning Engineer, DevOps Engineer, Software Engineer, Cybersecurity Analyst

**Education Levels covered:** High School, Diploma, Bachelor, Master, PhD

**Experience Level Groups:**

| Education Level | Experience Range | Level Tag |
|----------------|-----------------|-----------|
| High School | 0 – 2 years | Entry Level |
| Diploma | 0 – 2 years | Entry Level |
| Bachelor | 3 – 5 years | Junior Level |
| Master | 6 – 10 years | Mid Level |
| PhD | 11 years & above | Senior / Expert Level |

---

## ❓ Business Questions
The analysis is driven by 5 key HR business questions:

1. How does education level and years of experience jointly impact salary across different job titles?
2. Which combination of industry, company size, and location offers the highest paying opportunities?
3. Do remote or hybrid workers earn more than onsite employees, and does this vary by job title?
4. Does having more skills and certifications significantly increase an employee's salary regardless of experience?
5. Which job titles are most in demand across industries, and are they being compensated competitively?

---

## 📊 Analytics & Insights
The analysis delivers insights across the following areas:

- **Salary Trends** — Average, minimum, and maximum salary by job title and industry
- **Education & Experience Impact** — How qualifications and years of service drive compensation
- **Remote Work Analysis** — Salary comparison across Remote, Onsite, and Hybrid arrangements
- **Skills & Certifications** — Whether more skills and certifications lead to higher pay
- **Workforce Distribution** — Most in-demand roles and how they are compensated across industries
- **Location Intelligence** — Which countries and regions offer the best paying opportunities
- **Company Size Comparison** — Salary benchmarks across Startup, SME, Large, and Enterprise companies

---

## 🎯 Skills Demonstrated
- SQL Development & Query Optimization
- Data Cleaning & Transformation
- Exploratory Data Analysis (EDA)
- Data Analytics & Reporting
- Business Intelligence Insights
- Power BI Dashboard Design

---

## 🛠️ Tech Stack
- SQL Server (SSMS)
- Power BI

---

## ⚙️ Data Preparation Steps
The following changes were made to the raw dataset before analysis:

- **Remote Work Column Renamed** — Values updated from `Yes/No` to `Remote/Onsite` to avoid SQL keyword conflicts and improve clarity
- **Experience Level Grouping** — Experience years grouped based on education level into Entry, Junior, Mid, Senior, and Expert levels
- **Education Level Ordering** — Education levels assigned numeric prefixes for correct sorting (1-Basic to 5-Doctorate)
- **Table Created in SQL Server** — DDL written manually and data imported into `HR_SalaryDB` database
- **Salary Formatted** — Stored as `DECIMAL(10,2)` for accurate financial calculations

---

## 📂 Repository Structure
```bash
employee_salary_predications/
│
├── datasets/
│   └── job_salary_prediction_dataset.csv    # Raw salary data
│
├── scripts/                                 # SQL queries and transformation scripts
├── docs/                                    # Power BI dashboards and summaries
├── README.md
└── LICENSE
```

---

## ⚙️ Setup & Installation

### Clone Repository
```bash
git clone https://github.com/manhazyare/employee_salary_predications.git
```

### Navigate to Project
```bash
cd employee_salary_predications
```

### Database Setup
```sql
CREATE DATABASE HR_SalaryDB;
USE HR_SalaryDB;
```

---

## 🛡️ License
This project is licensed under the **MIT License**.
You are free to use, modify, and distribute this project with proper attribution.

---

## 🌟 About Me
Hi there! I am passionate about Data Analytics and turning raw data into meaningful business insights. This repository is part of my portfolio showcasing practical experience in HR data analysis, SQL reporting, and Power BI dashboarding.

---

## 🔗 GitHub Repository
https://github.com/manhazyare/employee_salary_predications
