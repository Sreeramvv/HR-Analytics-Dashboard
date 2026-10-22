# HR-Analytics-Dashboard

# Employee Attrition Analysis

## Overview
An exploratory analysis of an HR dataset (1,480 employee records, 38 columns) to understand which factors are associated with employee attrition. Overall attrition in the data is **16.3%** (241 employees).

## Objectives
- Measure attrition across departments, job roles, age groups and job levels
- Identify the workforce characteristics most associated with employees leaving
- Audit the dataset for quality issues before reporting

- ## Data Quality Issues Identified
- 16 duplicate `EmpID` values (2 exact duplicate rows, the rest with conflicting values)
- Inconsistent labels in `BusinessTravel` (`Travel_Rarely` vs `TravelRarely`)
- Two overlapping, inconsistent age-group columns (`Age_group`, `AgeGroup`)
- 61 missing values in `YearsWithCurrManager`
- Constant or redundant columns (`EmployeeCount`, `Over18`, `StandardWorkingHours`, `HourlyRate`)

![Image alt](https://github.com/Sreeramvv/HR-Analytics-Dashboard/blob/1f27f300f2146b140cf9316881cc843660db3f0c/HR%20Analytics%20Dashboard.png)

📈 Key Insights
- Overall attrition is 16.3% (241 of 1,480)
- Attrition is about 37–40% for ages 18–25 and falls to about 9% for ages 36–45.
- About 42% of leavers had 2 or fewer years at the company, compared with 23% of all employees.
- Sales Representatives show a higher attrition rate: 40.5% attrition.
- Attrition is 15.2% for women and 17.0% for men, a small gap.
- Operations, the largest department at 540 people, has the lowest attrition (8.3%).
