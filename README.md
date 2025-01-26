# SQL Project: Data Science Job Analysis

## Overview
This project uses SQL to analyze various aspects of data science job salaries and trends. The analysis addresses multiple real-world business scenarios by querying a database of job salary data. Each query is tailored to provide actionable insights into job markets, salary trends, and organizational needs.

---

## Objectives
1. Identify countries offering fully remote manager roles with salaries exceeding $90,000 USD.
2. Determine the top 5 countries with the greatest number of large companies hiring freshers.
3. Calculate the percentage of employees enjoying fully remote roles with salaries above $100,000 USD.
4. Identify locations where entry-level average salaries exceed the market average for specific job titles.
5. Find the country offering the maximum average salary for each job title.
6. Pinpoint locations with sustained salary growth over the past three years.
7. Analyze remote work trends by experience level for 2021 vs. 2024.
8. Calculate the average salary increase percentage by experience level and job title between 2023 and 2024.
9. Implement role-based access control to ensure data confidentiality based on experience levels.
10. Guide employees on domain transitions based on input preferences to maximize salaries.

---

## SQL Queries Addressed

### Query 1: High-Salary Remote Manager Roles
- **Purpose**: Identify countries offering fully remote manager roles with salaries exceeding $90,000 USD.
- **Query**: Utilized `DISTINCT`, `WHERE`, and filtering conditions to pinpoint relevant countries.

### Query 2: Freshers in Large Companies
- **Purpose**: Identify the top 5 countries with the highest count of large companies hiring freshers.
- **Query**: Used `GROUP BY`, `COUNT`, and `ORDER BY` to rank countries.

### Query 3: High-Paying Remote Jobs
- **Purpose**: Calculate the percentage of fully remote roles with salaries above $100,000 USD.
- **Query**: Employed variables and calculations to determine percentages.

### Query 4: Lucrative Entry-Level Locations
- **Purpose**: Identify locations where entry-level average salaries exceed market averages.
- **Query**: Performed `INNER JOIN` and aggregations to compare averages.

### Query 5: Highest Average Salaries by Country
- **Purpose**: Find the country paying the maximum average salary for each job title.
- **Query**: Utilized `DENSE_RANK` for ranking average salaries.

### Query 6: Sustained Salary Growth Locations
- **Purpose**: Identify locations with consistent salary growth over three years.
- **Query**: Combined `WITH` clauses and conditional logic to track salary trends.

### Query 7: Remote Work Adoption Trends
- **Purpose**: Compare remote work percentages by experience level between 2021 and 2024.
- **Query**: Used nested subqueries and calculations to highlight trends.

### Query 8: Salary Increases by Experience and Title
- **Purpose**: Calculate salary increase percentages for each experience level and job title.
- **Query**: Leveraged `CASE`, `GROUP BY`, and arithmetic calculations.

### Query 9: Role-Based Access Control
- **Purpose**: Implement data access restrictions based on experience levels.
- **Query**: Created user roles and granted permissions using `CREATE VIEW` and `GRANT`.

### Query 10: Domain Transition Guidance
- **Purpose**: Recommend job domains for employees based on provided preferences.
- **Query**: Developed a stored procedure with parameters to calculate average salaries for specific conditions.

---

## Tools and Environment
- **Database**: MySQL
- **Dataset**: Includes fields such as `job_title`, `company_location`, `salary_in_usd`, `experience_level`, `remote_ratio`, `company_size`, and more.
- **Approach**: Queries are modular and reusable for various analytical purposes.

---

## How to Run
1. Import the dataset into your SQL environment.
2. Execute each query as outlined in the project file.
3. Use the provided stored procedures for dynamic analysis.

---

## Key Insights
1. **Top Locations for High-Salary Remote Roles**:
   - Specific countries were identified for remote manager roles with attractive salaries.
2. **Freshers’ Opportunities**:
   - Countries with large company hiring trends for freshers were highlighted.
3. **Remote Work Trends**:
   - Significant adoption of remote work for high-paying jobs was observed.
4. **Salary Growth**:
   - Locations with consistent salary increases were pinpointed.
5. **Domain Recommendations**:
   - Employees were guided toward lucrative domains based on salary data.

---

## Future Enhancements
1. Integrate visualization tools like Power BI or Tableau to display trends graphically.
2. Automate the execution of stored procedures for real-time analysis.
3. Expand the dataset to include more years and industries for broader analysis.

---

## Contact
For queries or collaborations, please reach out to [Achyuthkumar] at Email[achyuthkumarak4756@gmail.com].

