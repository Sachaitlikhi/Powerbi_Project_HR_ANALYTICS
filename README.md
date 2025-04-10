# Employee Attrition Dashboard in Power BI

This repository contains a Power BI dashboard designed to analyze employee attrition. The dashboard provides insights into the factors influencing employee turnover, such as age, salary, tenure, education background, and job role. The goal of this project is to uncover trends and patterns that could help reduce attrition rates within an organization.

## Table of Contents

1. [Overview](#overview)
2. [Data Preparation and Cleaning](#data-preparation-and-cleaning)
3. [Key Performance Indicators (KPIs)](#key-performance-indicators-kpis)
4. [Visualizations](#visualizations)
5. [Key Insights](#key-insights)


## Overview

The Power BI dashboard is built to analyze and visualize employee attrition data. It includes data preparation, cleaning, DAX calculations, and visualization of key metrics to identify patterns in employee turnover.

## Data Preparation and Cleaning

The following steps were performed to prepare and clean the data:

- **Power Query Editor**: Used for initial data cleaning, including handling missing or null values.
- **Null Value Check**: Employed the "Column Quality" feature to identify and handle any missing values.
- **Duplicate Identification**: Removed duplicate entries by grouping and counting occurrences based on the Employee ID.
- **Attrition Count**: Created a custom column that converted the "Yes"/"No" attrition data to numerical values (1 for "Yes" and 0 for "No").
- **Attrition Rate Calculation**: Used DAX to calculate the attrition rate and set the column's data type for accuracy.

## Key Performance Indicators (KPIs)

The dashboard includes the following KPIs:

- **Average Salary**: The average salary across all employees.
- **Attrition Rate**: Percentage of employees who have left the company.
- **Average Age**: The average age of employees.
- **Average Tenure**: The average number of years employees have worked in the company.
- **Attrition by Gender**: Displays the attrition rate broken down by gender.

These KPIs provide a high-level overview of the employee attrition situation, helping stakeholders make data-driven decisions.

## Visualizations

The dashboard includes the following visualizations to uncover deeper insights into employee attrition:

1. **Donut Chart**: Shows attrition by education background, highlighting life sciences and medical fields as the highest contributors to attrition.
2. **Stacked Column Chart**: Illustrates attrition rates by age group, revealing the highest turnover among employees aged 26-35.
3. **Matrix Visual**: Displays the relationship between job roles, job satisfaction, and attrition count, with custom highlights for significant patterns.
4. **Stacked Bar Chart**: Represents attrition by salary slab, with the highest attrition rate among employees earning below the company average.
5. **Area Chart**: Depicts attrition by tenure, with the highest attrition occurring among employees with only one year of service.
6. **Stacked Bar Chart**: Highlights attrition by job role, identifying roles with the highest turnover.

## Key Insights

The dashboard provides several critical insights into employee attrition:

- **Education Background**: 38% of employees who left the company had a life sciences background, and 27% came from the medical field.
- **Age Group**: The highest attrition rate was observed among employees aged 26-35.
- **Salary**: Employees earning below the company average had the highest attrition rate.
- **Tenure**: The highest attrition occurred among employees who had been with the company for one year or less.
- **Job Roles**: The roles with the highest attrition rates were:
  1. Laboratory Technician
  2. Sales Executive
  3. Research Scientist



