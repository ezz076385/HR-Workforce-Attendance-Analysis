# HR Workforce & Attendance Analysis

> **Turning employee data into workforce insights that support better HR decisions.**

## Project Overview

This portfolio project analyzes workforce structure, compensation, performance, attendance, and overtime patterns across **689 employee records**.

The project is designed around business questions rather than software features: understanding where the workforce is concentrated, how compensation differs across departments, where overtime is concentrated, and whether attendance patterns deserve further investigation.

## Business Questions

The analysis focuses on questions such as:

- How is the workforce distributed across departments, countries, centers, and gender?
- How does compensation vary across departments?
- Which departments show higher overtime levels?
- What patterns appear in sick and unpaid leave?
- Is years of experience strongly associated with salary?
- Which workforce areas may require deeper HR investigation?

## Dataset

The main employee table contains **689 records and 15 fields**.

### Core fields

| Category | Fields |
|---|---|
| Employee profile | No, First Name, Last Name, Gender |
| Employment | Start Date, Years, Department, Country, Center |
| Compensation | Monthly Salary, Annual Salary |
| Performance | Job Rate |
| Attendance | Sick Leaves, Unpaid Leaves |
| Workload | Overtime Hours |

**Start Date range:** January 2016 – December 2020.

> **Privacy note:** The original workbook contains employee names. For a public GitHub repository, do not upload the raw workbook unless you have confirmed that the data is synthetic, public, or otherwise safe to disclose. A sanitized/public version should be used when necessary.

## Methodology

This is a **descriptive and diagnostic workforce analysis** rather than a predictive model.

### Analytical approach

1. Validate the employee table structure and completeness.
2. Review workforce distributions and segmentation.
3. Compare compensation across departments.
4. Analyze job-rate distribution.
5. Analyze overtime and attendance patterns.
6. Examine the relationship between experience and salary.
7. Convert findings into a multi-page interactive Excel dashboard.

### Techniques used

- Aggregation and KPI analysis
- Grouping and segmentation
- Cross-tabulation
- Distribution analysis
- Department-level comparison
- Descriptive correlation analysis
- PivotTables and interactive filtering

### Data validation

Basic quality checks were performed on the main employee table:

- **689 unique employee numbers**
- Employee numbers run from **1 to 689**
- **No missing values** were found across the 15 main fields

No predictive model was used, so model-performance metrics such as accuracy, RMSE, or silhouette score are not applicable.

## Dashboard Structure

The workbook is organized into analysis-focused pages:

### 1. Workforce Overview

Provides a high-level view of:

- Total workforce
- Department distribution
- Gender composition
- Country and center distribution
- Experience distribution

### 2. Compensation Analysis

Focuses on:

- Monthly and annual salary
- Salary differences across departments
- Job-rate distribution
- Experience versus salary patterns

### 3. Attendance & Workload Analysis

Focuses on:

- Sick leaves
- Unpaid leaves
- Overtime hours
- Department-level attendance and workload patterns
- Potential relationships between overtime and sick leave

## Key Findings

### Workforce distribution

The dataset contains **689 employees**.

- **Manufacturing:** 140 employees
- **Quality Control:** 89 employees
- **Account Management:** 84 employees

Manufacturing is therefore the largest department in the dataset.

### Compensation

- **Average monthly salary:** 2,068.20
- **Average annual salary:** 24,818.42
- **Total annual salary represented in the dataset:** 17,099,892

Compensation varies across departments, making department-level comparison more informative than a single overall salary average.

### Overtime

- **Total overtime hours:** 9,441
- **Average overtime:** 13.70 hours per employee
- **Employees with overtime above zero:** 638 of 689

The concentration of overtime differs across departments and can be used to identify areas for deeper workload and resource investigation.

### Sick leave

Sick leave is a central part of this analysis:

- **Total sick leaves:** 1,109
- **Average sick leave:** 1.61 per employee
- **Employees with at least one sick leave:** 319
- **Employees with zero sick leave:** 370

Department-level differences in average sick leave provide a useful starting point for further investigation rather than assuming a single workforce-wide pattern.

### Workforce gender distribution

- **Male:** 449
- **Female:** 240

This provides visibility into workforce composition across the organization and its departments.

### Experience and salary

The relationship between **Years of Experience** and **Monthly Salary** is weak in this dataset.

This suggests that tenure alone does not explain salary variation and that other compensation drivers would need to be examined before drawing stronger conclusions.

## Business Implications

The analysis can support HR teams in:

- Monitoring workforce composition
- Comparing compensation across departments
- Identifying departments with elevated overtime
- Investigating attendance patterns
- Supporting workforce planning
- Identifying areas that require deeper analysis before making decisions

These findings are **descriptive**. They indicate where to investigate; they do not establish causation.

## Limitations

- The dataset is a workforce snapshot with employee start dates rather than a full historical headcount time series.
- Overtime and sick-leave relationships are observational and should not be interpreted as causal.
- The dataset does not contain fields such as termination date, performance history over time, or detailed workload drivers.
- Salary differences cannot be attributed to experience alone.

## Tools

- Microsoft Excel
- PivotTables
- PivotCharts / Excel Charts
- Slicers and interactive navigation
- Excel formulas and descriptive analysis

## Repository Structure

```text
HR-Workforce-Attendance-Analysis/
│
├── README.md
├── assets/
│   ├── dashboard-overview.png
│   ├── compensation-analysis.png
│   └── attendance-analysis.png
│
├── data/
│   └── README.md
│
└── workbook/
    └── HR_Workforce_Analytics.xlsx   # Add only a sanitized/public version
```

## Portfolio Focus

This project demonstrates how I approach data analysis from a **business-question-first** perspective:

**Raw Data → Business Questions → Analysis → Insights → Decision Support**

The objective is not simply to build a dashboard, but to make the data easier to interpret and more useful for HR decision-making.

## Author

**Mohamed Ezz**

- GitHub: [ezz076385](https://github.com/ezz076385)
- LinkedIn: [Mohamed Ezz](https://www.linkedin.com/in/mohamedezz076385/)

---

### Project Title

**HR Workforce & Attendance Analysis**

### Suggested Repository Description

> Workforce, compensation, attendance, sick-leave, and overtime analysis built from employee-level data using Microsoft Excel.
