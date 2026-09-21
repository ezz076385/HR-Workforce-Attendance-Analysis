# HR Workforce & Attendance Analysis

> Turning employee data into actionable workforce insights for better HR decision-making.

<p align="center">
![image alt] (https://github.com/ezz076385/HR-Workforce-Attendance-Analysis/blob/Master/scr/HR%20Overview.png)
</p>

## Project Overview

Employee data can tell a much bigger story than simple headcount and salary totals.

This project analyzes **689 employee records** to understand workforce structure, compensation, attendance, sick leaves, overtime, and experience patterns.

Rather than building a dashboard around charts alone, the analysis was structured around business questions:

* Where is the workforce concentrated?
* How does compensation differ across departments?
* Which departments have higher overtime?
* What patterns can be seen in sick and unpaid leaves?
* Is experience strongly associated with salary?
* Which areas deserve further HR investigation?

The final result is an **interactive Excel dashboard** that converts employee-level data into a clearer view of workforce patterns.

---

## 1. Business Problem

HR teams often have large amounts of employee data, but raw tables do not always make workforce issues easy to identify.

The purpose of this analysis was to move from:

**Raw Employee Data → Business Questions → Analysis → Insights → Decision Support**

The analysis focuses on four main areas:

**Workforce Structure**
Understanding employee distribution across departments, countries, centers, gender, and experience.

**Compensation**
Comparing salaries across departments and examining whether experience is associated with salary.

**Attendance & Sick Leave**
Identifying attendance patterns and departments that may require further investigation.

**Overtime & Workload**
Understanding how overtime is distributed across employees and departments.

---

## 2. Dataset

The main employee table contains:

* **689 employee records**
* **15 fields**
* Start dates ranging from **2016 to 2020**
* Department, country, and center information
* Compensation and job-rate information
* Sick leave, unpaid leave, and overtime measures

### Main Data Fields

| Area             | Fields                                         |
| ---------------- | ---------------------------------------------- |
| Employee Profile | No, First Name, Last Name, Gender              |
| Employment       | Start Date, Years, Department, Country, Center |
| Compensation     | Monthly Salary, Annual Salary                  |
| Performance      | Job Rate                                       |
| Attendance       | Sick Leaves, Unpaid Leaves                     |
| Workload         | Overtime Hours                                 |

> The public version of the repository should use a sanitized dataset if the original employee names are not intended for public disclosure.

---

## 3. Data Preparation & Analysis Process

The analysis followed a structured workflow rather than moving directly from the raw table to the final dashboard.

### Step 1 — Data Review

The employee table was reviewed to understand:

* Dataset structure
* Field types
* Workforce dimensions
* Numeric measures
* Potential analytical relationships

Basic validation confirmed **689 employee numbers** with no missing values across the main 15 fields.

### Step 2 — Workforce Analysis

The workforce was segmented by:

* Department
* Gender
* Country
* Center
* Years of experience

This created the foundation for understanding how the workforce is distributed.

### Step 3 — Compensation Analysis

Salary metrics were analyzed using:

* Monthly Salary
* Annual Salary
* Department-level comparisons
* Job Rate
* Experience versus salary

### Step 4 — Attendance & Workload Analysis

The analysis focused specifically on:

* Sick Leaves
* Unpaid Leaves
* Overtime Hours

Both total and average measures were used where appropriate to avoid looking at only one side of the data.

### Step 5 — Dashboard Development

The final analysis was transformed into a multi-page Excel dashboard using:

* PivotTables
* PivotCharts
* KPI summaries
* Slicers
* Interactive navigation
* Department-level comparisons

The goal was to make the analysis easier to explore rather than simply presenting a collection of charts.

---

# 4. Workforce Analysis

<p align="center">
  <img src="assets/headcount-by-department.png" alt="Employee Distribution by Department" width="850"/>
</p>

### Employee Distribution

The dataset contains **689 employees**.

The largest departments are:

* **Manufacturing — 140 employees**
* **Quality Control — 89 employees**
* **Account Management — 84 employees**

This helps identify where most of the workforce is concentrated and provides context for later compensation and workload comparisons.

### Gender Distribution

<p align="center">
  <img src="assets/gender-distribution.png" alt="Gender Distribution" width="650"/>
</p>

The workforce consists of:

* **449 Male**
* **240 Female**

The same analysis can be explored across departments to understand workforce composition in more detail.

---

# 5. Compensation Analysis

<p align="center">
  <img src="assets/salary-by-department.png" alt="Average Salary by Department" width="850"/>
</p>

### Salary Overview

The dataset shows:

* **Average Monthly Salary: 2,068.20**
* **Average Annual Salary: 24,818.42**
* **Total Annual Salary: 17,099,892**

Department-level comparisons provide more useful context than relying only on the overall average.

### Experience vs Salary

<p align="center">
  <img src="assets/experience-vs-salary.png" alt="Experience versus Salary" width="800"/>
</p>

The relationship between years of experience and monthly salary is weak in this dataset, with a correlation of approximately **-0.04**.

This suggests that **experience alone does not explain salary variation**, so additional factors would need to be considered before making compensation-related conclusions.

---

# 6. Attendance & Overtime Analysis

This was one of the key analytical areas of the project.

## Sick Leave Analysis

<p align="center">
  <img src="assets/sick-leaves-by-department.png" alt="Sick Leaves by Department" width="850"/>
</p>

The dataset contains:

* **1,109 total Sick Leaves**
* **1.61 average Sick Leaves per employee**
* **319 employees** with at least one recorded Sick Leave
* **370 employees** with zero recorded Sick Leave

The important question is not simply how many Sick Leaves exist, but **where the patterns are concentrated**.

Differences between departments can therefore be used as a starting point for further HR investigation.

> These results are descriptive and do not establish why employees take sick leave.

---

## Overtime Analysis

<p align="center">
  <img src="assets/overtime-distribution.png" alt="Overtime Hours Distribution" width="850"/>
</p>

Across the dataset:

* **9,441 total Overtime Hours**
* **13.70 average Overtime Hours per employee**
* **638 employees** recorded more than zero Overtime Hours

Looking at the distribution is useful because the overall average alone does not show how overtime is spread across the workforce.

Department-level overtime comparisons can help identify areas that may require further workload or resource review.

---

## 7. Key Findings

The analysis produced several important observations:

### Workforce Concentration

Manufacturing represents the largest department in the dataset with **140 employees**, followed by Quality Control and Account Management.

### Compensation Differences

Average salary varies considerably across departments, making department-level comparison more informative than a single overall salary figure.

### Overtime Exposure

**638 of 689 employees** recorded some level of overtime, while total overtime reached **9,441 hours**.

### Sick Leave Pattern

Sick Leave totaled **1,109**, but the distribution is not uniform across employees or departments, creating opportunities for deeper attendance analysis.

### Experience and Salary

The weak relationship between experience and salary suggests that tenure alone is not sufficient to explain salary differences in this dataset.

---

# 8. Business Questions This Dashboard Helps Answer

The dashboard was designed to help HR explore questions such as:

* Where is the workforce concentrated?
* Which departments have the highest headcount?
* How does compensation differ by department?
* Which areas have higher overtime levels?
* Where are Sick Leaves more concentrated?
* How is gender distributed across the workforce?
* Does experience appear to influence salary?
* Which areas should HR investigate further?

---

# 9. Business Value

The purpose of the dashboard is not simply to display employee statistics.

It provides a structured view that can support:

* Workforce planning
* Compensation analysis
* Attendance monitoring
* Workload investigation
* Workforce composition analysis
* Early identification of areas requiring deeper analysis

The dashboard turns employee-level records into a more accessible decision-support view for HR.

---

# 10. Limitations

This analysis has several limitations:

* The dataset is primarily a workforce snapshot rather than a full historical employee movement dataset.
* Start Date can support experience analysis, but it does not provide monthly headcount history.
* Sick Leave and Overtime relationships are observational and should not be interpreted as causal.
* The dataset does not contain termination dates or detailed workload drivers.
* Salary differences cannot be attributed to experience alone.

These limitations define where further analysis could be added.

---

# 11. Tools & Techniques

**Tools**

* Microsoft Excel
* PivotTables
* PivotCharts
* Slicers
* Excel formulas

**Analytical Techniques**

* Data validation
* Aggregation
* Grouping
* Cross-tabulation
* Distribution analysis
* Department-level comparison
* Correlation analysis
* KPI analysis

---

# 12. Dashboard Structure

### Workforce Overview

<p align="center">
  <img src="assets/dashboard-overview.png" alt="Workforce Overview Dashboard" width="900"/>
</p>

### Compensation Analysis

<p align="center">
  <img src="assets/compensation-analysis.png" alt="Compensation Analysis Dashboard" width="900"/>
</p>

### Attendance & Overtime

<p align="center">
  <img src="assets/attendance-analysis.png" alt="Attendance and Overtime Dashboard" width="900"/>
</p>

The dashboard uses interactive navigation and filtering to allow users to move between analytical areas without manually searching through worksheets.

---

# 13. Portfolio Takeaway

This project represents a **business-question-first approach to data analysis**.

The objective was not to build an Excel dashboard simply because Excel was the available tool.

The objective was to answer meaningful workforce questions, identify measurable patterns, and present the results in a format that can support further HR investigation and decision-making.

**Raw Data → Questions → Analysis → Insights → Decision Support**

---

## Author

**Mohamed Ezz**

[GitHub](https://github.com/ezz076385) · [LinkedIn](https://www.linkedin.com/in/mohamedezz076385/)
