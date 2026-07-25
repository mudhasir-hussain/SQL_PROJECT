# SQL Data Analyst Job Market Analysis

> **Learning Project:** Completed while following Luke Barousse's SQL course. This repository documents my implementation, notes, and understanding of the SQL concepts covered.

## Overview

This project explores the 2023 Data Analyst job market using PostgreSQL. I analysed job-posting data to identify high-paying roles, in-demand technical skills, and the skills that offer the strongest balance between salary potential and employer demand.

The project was completed as part of my SQL learning journey while following Luke Barousse's SQL course. While the project idea and dataset come from the course, I wrote and executed each SQL query myself.

## Objectives

This analysis answers the following questions:

- Which Data Analyst jobs offer the highest salaries?
- Which skills are required for high-paying Data Analyst jobs?
- Which skills are most frequently requested by employers?
- Which technical skills are associated with the highest salaries?
- Which skills provide the best combination of salary potential and market demand?

## Dataset

The dataset contains job postings for data-related roles, including:

- Job titles
- Salary information
- Company details
- Job locations
- Required technical skills



## Technologies Used

- SQL
- PostgreSQL
- Visual Studio Code
- Git
- GitHub

## SQL Concepts Practised

- `SELECT` statements
- Filtering with `WHERE`
- `ORDER BY` and `LIMIT`
- Aggregate functions such as `COUNT` and `AVG`
- `GROUP BY` and `HAVING`
- `INNER JOIN` and `LEFT JOIN`
- Common Table Expressions (CTEs)
- Data analysis using SQL

## Analysis

### 1. Top-Paying Data Analyst Jobs

[View SQL query](project_sql/top_paying_jobs.sql)

I identified the highest-paying remote Data Analyst positions by filtering for jobs with available salary information.

**Skills demonstrated:**

- Filtering data
- `LEFT JOIN`
- Sorting results
- Limiting output

**Key findings:**

- Salaries ranged from approximately **$184,000 to $650,000**.
- Remote roles offered significant earning potential.
- High-paying opportunities existed across multiple industries.

![Top Paying Data Analyst Jobs](SQL_PROJECT/assets/top_paying_jobs.png)

### 2. Skills Required for Top-Paying Jobs

[View SQL query](project_sql/top_paying_job_skills.sql)

This analysis examines the technical skills required for the highest-paying Data Analyst positions.

**Skills demonstrated:**

- Common Table Expressions (CTEs)
- Multiple `INNER JOIN`s
- Relational database querying

**Key findings:**

- SQL appeared most frequently.
- Python and Tableau were also commonly requested.
- Employers expected a combination of database, programming, and visualisation skills.

![Skills Required for Top Paying Jobs](SQL_PROJECT/assets/top_paying_job_skills.png)

### 3. Most In-Demand Skills

[View SQL query](project_sql/top_demanded_skills.sql)

This analysis identifies the technologies that appear most frequently across Data Analyst job postings.

| Skill | Demand |
|---|---:|
| SQL | 7,291 |
| Excel | 4,611 |
| Python | 4,330 |
| Tableau | 3,745 |
| Power BI | 2,609 |

**Key findings:**

- SQL remains the most valuable core skill.
- Excel continues to be widely used.
- Python and business-intelligence tools are highly desirable.

![Most In-Demand Skills](assets/top_demanded_skills.png)

### 4. Highest-Paying Skills

[View SQL query](project_sql/top_paying_skills.sql)

I calculated the average salary associated with each technical skill.

**Key findings:**

- Cloud technologies and big-data tools command higher salaries.
- Engineering-focused technologies often pay more than traditional reporting tools.
- Advanced technical skills can significantly increase salary potential.

![Highest Paying Skills](assets/top_paying_skills.png)

### 5. Best Skills to Learn

[View SQL query](project_sql/optimal_skills.sql)

This analysis combines salary and demand data to identify the skills with the strongest overall career value.

**Key findings:**

Skills such as SQL, Python, Snowflake, AWS, Azure, and Tableau offer an excellent balance between employer demand and salary potential.

![Best Skills to Learn](assets/optimal_skills.png)

## What I Learned

This project gave me practical experience using SQL with a realistic dataset. I became more comfortable with:

- Writing complex SQL queries
- Joining multiple tables
- Using Common Table Expressions (CTEs)
- Aggregating and summarising data
- Answering business questions using SQL
- Interpreting analytical results
- Organising a complete SQL project with Git and GitHub

## Project Structure

```text
SQL_PROJECT/
│
├── README.md
├── assets/
│   ├── top_paying_jobs.png
│   ├── top_paying_job_skills.png
│   ├── top_demanded_skills.png
│   ├── top_paying_skills.png
│   └── optimal_skills.png 
│
└── project_sql/
    ├── top_paying_jobs.sql
    ├── top_paying_job_skills.sql
    ├── top_demanded_skills.sql
    ├── top_paying_skills.sql
    └── optimal_skills.sql
```

## Credits

This project was completed while following the SQL course by [Luke Barousse](https://lukebarousse.com/sql).

This repository represents my own implementation and learning experience.

## Future Improvements

- Build interactive dashboards using Power BI or Tableau
- Perform the same analysis for Data Scientist and Data Engineer roles
- Create visualisations directly in Python
- Compare job-market trends across different countries
- Automate the analysis using SQL scripts
