# 👥 HR Workforce Analytics Dashboard

An interactive **HR Workforce Analytics Dashboard** built with **Microsoft Power BI** to analyze employee attrition, workforce demographics, compensation, career growth, satisfaction, and performance.

The dashboard is designed to help HR teams and business leaders understand workforce trends and identify areas that may require attention.

---

## 📊 Dashboard Preview

### Executive Summary
![Executive Dashboard](Assets/Executive.png)

### Attrition Analysis
![Attrition Dashboard](Assets/Attrition.png)

### Workforce Demographics
![Workforce Dashboard](Assets/Workforce.png)

### Compensation & Career Growth
![Compensation Dashboard](Assets/Compensation.png)

### Employee Satisfaction & Performance
![Satisfaction Dashboard](Assets/Satisfaction.png)

---

# 🎯 Project Objective

The objective of this project is to build an interactive HR analytics solution that helps answer important workforce-related business questions.

The dashboard focuses on:

- Workforce size and composition
- Employee attrition
- Department-level workforce trends
- Employee demographics
- Compensation and salary growth
- Career progression
- Employee satisfaction
- Work-life balance
- Performance
- Overtime

---

# 💼 Business Questions

This dashboard answers questions such as:

- How many employees are currently in the organization?
- What is the overall employee attrition rate?
- Which departments have the highest number of employees leaving?
- Which job roles experience the highest attrition?
- What is the gender and age distribution of employees?
- Which departments have the highest average monthly income?
- Which job roles have the highest average income?
- What is the average salary hike?
- Which departments have employees waiting longest for promotion?
- How are employees distributed across stock option levels?
- What is the overall employee job satisfaction?
- How does work-life balance vary across employees?
- How many employees work overtime?
- How are employee performance ratings distributed?

---

# 📑 Dashboard Pages

## 🏠 1. Executive Summary

Provides a high-level overview of the organization's workforce.

### Key Metrics

- Total Employees
- Employees Left
- Attrition Rate
- Average Age
- Average Monthly Income
- Average Years at Company

### Visualizations

- Total Employees by Department
- Total Employees by Gender
- Employees Left by Department
- Total Employees by Age Group
- Average Monthly Income by Department
- Employees Left by Job Role

---

## 📉 2. Attrition Analysis

Focuses on understanding employee turnover and identifying areas with higher attrition.

### Key Metrics

- Employees Left
- Attrition Rate
- Active Employees
- Employees Working Overtime
- Job Roles with Attrition

### Visualizations

- Total Employees and Employees Left by Department
- Employees Left by Overtime
- Employees Left by Job Role
- Employees Left by Age Group
- Employees Left by Marital Status
- Employees Left by Education Field

---

## 👥 3. Workforce Demographics

Provides a detailed view of the composition of the workforce.

### Key Metrics

- Total Employees
- Male Employees
- Female Employees
- Average Age
- Total Departments
- Total Job Roles

### Visualizations

- Total Employees by Department
- Total Employees by Gender
- Total Employees by Education Field
- Total Employees by Age Group
- Average Monthly Income by Department
- Total Employees by Job Role

---

## 💰 4. Compensation & Career Growth

Analyzes employee compensation, salary growth, career progression, and benefits.

### Key Metrics

- Average Monthly Income
- Average Salary Hike
- Highest Paying Salary
- Employees Promoted
- Average Stock Option Level
- Average Years in Current Role

### Visualizations

- Average Monthly Income by Department
- Average Years Since Promotion by Department
- Average Salary Hike by Department
- Average Monthly Income by Education Field
- Employees by Stock Option Level
- Average Monthly Income by Job Role

---

## ⭐ 5. Employee Satisfaction & Performance

Analyzes employee satisfaction, work environment, performance, work-life balance, and overtime.

### Key Metrics

- Average Job Satisfaction
- Average Environment Satisfaction
- Average Work-Life Balance
- Average Performance Rating
- Average Relationship Satisfaction
- Employees Working Overtime

### Visualizations

- Employees by Job Satisfaction
- Employees by Performance Rating
- Employees by Relationship Satisfaction
- Employees by Environment Satisfaction
- Employees by Overtime
- Employees by Work-Life Balance

---

# 📌 Key KPIs

The dashboard uses several important HR metrics.

### Total Employees

```DAX
Total Employees =
COUNT(Employee[EmployeeNumber])
