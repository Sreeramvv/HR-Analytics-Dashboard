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
