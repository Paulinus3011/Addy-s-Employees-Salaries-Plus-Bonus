# Addy-s-Employees-Salaries-Plus-Bonus

## Employees Salaries Plus Bonus – Dashboard

This Power BI dashboard provides a comprehensive view of employees’ total compensation, including base salaries and bonuses. It highlights overall company payroll, departmental distribution, and regional breakdowns, helping stakeholders understand workforce cost allocation.

## Overview

🔢 Key Metrics

Number of Employees: 869

Total Bonus Paid: $6.2M

Total Salary (Excluding Bonus): $61.96M

Total Salary + Bonus: $68.15M

📌 Insight: Bonuses contribute approximately 10% of overall compensation.

🏢 Salary Breakdown by Department

Highest Paid Departments:

Product Management: $6.6M

Business Development: $6.4M

Human Resources: $6.1M

Mid-range Departments:

Support: $5.8M, Legal: $5.7M, Sales: $5.6M, Engineering: $5.6M

Lower-end Departments:

Training: $5.5M, Accounting: $5.5M, Marketing: $5.1M, R&D: $4.7M

📌 Insight: Product Management, Business Development, and HR account for the largest salary shares, while R&D receives the least.

🌍 Salary Breakdown by Region

Texas: $26.3M (largest share)

Florida: $23.8M

Mississippi: $11.1M

Los Angeles: $4.9M

California: $2.0M combined (1.3M + 0.7M)

📌 Insight: Texas and Florida dominate salary distribution, representing nearly 80% of total payroll.

## Data Dictionary

Field	Description	Data Type	Example Values
Employee_ID	Unique identifier for each employee	Integer	101, 205, 322
Employee_Name	Name of the employee	Text	John Doe, Jane Smith
Gender	Gender of the employee	Categorical	Male, Female
Department	Functional area where the employee works	Categorical	HR, Sales, Engineering
Location	Region or state of employment	Categorical	Texas, Florida, California
Salary	Annual base salary	Numeric (USD)	80,000; 120,000
Bonus	Annual bonus amount	Numeric (USD)	5,000; 15,000
Total_Comp	Combined salary + bonus (calculated in Power BI)	Numeric (USD)	95,000; 135,000

## Data Source

Data was sourced from an employee payroll/HR system (Excel extract or SQL export).

Dataset includes 869 employee records.

## Insights

High Concentration in Regions: Texas and Florida absorb the majority of payroll expenditure.

Departmental Leaders: Product Management and Business Development collectively account for over 19% of payroll.

Bonus Contribution: Bonuses make up roughly $6.2M, showing significant investment in employee incentives.

Balanced Departmental Spend: Most departments range between $5M–$6.5M, with minimal outliers.

## Usage Scenarios

Finance Teams: Assess departmental payroll allocation.

Executives: Monitor regional salary investments.

HR Analysts: Evaluate bonus distribution relative to salaries.

## Future Enhancements

Add trend analysis over time (yearly salary growth).

Incorporate average salary per employee per department.

Introduce bonus-to-salary ratio analysis.

Fix potential duplicate region naming (California).
Calculations (e.g., Total Salary + Bonus) were performed in Power BI.

