# HadoopHiveHue
Hadoop , Hive, Hue setup pseudo distributed  environment  using docker compose
# Hive: Employee and Department Data Analysis

##  Project Overview
This project analyzes employee and department data using Hive queries.  
It involves loading data into Hive tables, performing partitioning, and executing various queries  
to extract insights such as employee distribution, salary analysis, and department statistics.

---

##  Datasets Used
- **employees.csv**: Contains employee details (`emp_id`, `name`, `age`, `job_role`, `salary`, `project`, `join_date`, `department`).
- **departments.csv**: Contains department information (`dept_id`, `department_name`, `location`).

---

##  Steps Followed
1. **Set up Hive environment using Docker.**
2. **Created Hive tables:**
   - `employees` (partitioned by `department`)
   - `departments`
3. **Loaded data into Hive tables.**
4. **Executed queries to analyze employee and department data.**

---

##  Queries Executed and Output Files
| Query # | Description | Output File |
|---------|------------|-------------|
| 1️ | Retrieve employees who joined after 2015 | `query1_output.txt` |
| 2️ | Find the average salary of employees per department | `query2_output.txt` |
| 3️ | Identify employees working on the 'Alpha' project | `query3_output.txt` |
| 4️ | Count the number of employees in each job role | `query4_output.txt` |
| 5️ | Retrieve employees earning above their department’s average salary | `query5_output.txt` |
| 6️ | Find the department with the highest number of employees | `query6_output.txt` |
| 7️ | Exclude employees with NULL values | `query7_output.txt` |
| 8️ | Join employees with department locations | `query8_output.txt` |
| 9️ | Rank employees within each department based on salary | `query9_output.txt` |
|  | Find the top 3 highest-paid employees in each department | `query10_output.txt` |

---

## How to Run This Project
1. Clone the repository:
   ```bash
   git clone https://github.com/Cloud-Computing-Spring-2025/hive-employee-data-analysis-bhanukocherla.git

