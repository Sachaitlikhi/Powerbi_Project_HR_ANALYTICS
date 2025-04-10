# Powerbi_Project_HR_ANALYTICS

I have developed a Power BI dashboard to analyze employee attrition, focusing on various factors that could help uncover why employees are leaving the company. Below is a detailed breakdown of the steps I took to prepare the data, perform analysis, and visualize the insights.

Data Preparation and Cleaning:
•	Power Query Editor: I used Power Query Editor to perform initial data cleaning, ensuring the data was well-prepared for analysis.
•	Null Value Check: Using the "Column Quality" feature, I checked for any missing or null values and took appropriate action to handle them.
•	Duplicate Identification: I identified and removed duplicates by leveraging the "Group By" option and counting occurrences based on the Employee ID column. Additionally, I replaced any special character values.
•	Attrition Count: I created a custom column to calculate the attrition count by converting "Yes" and "No" values from the attrition column into 1 and 0 respectively. This allowed me to track how many employees had left the company.
•	Attrition Rate Calculation: Using DAX, I calculated the attrition rate and changed the data type of the corresponding column to ensure accuracy.
Key Performance Indicators (KPIs):
•	I created KPIs to provide a quick overview of key metrics, including:
o	Average Salary
o	Attrition Rate
o	Average Age
o	Average Tenure (Years Worked in the Company)
o	Attrition by Gender
These KPIs were designed to present important data to stakeholders and highlight areas of concern.
Visualizations:
To uncover insights into employee attrition, I created a series of visualizations:
1.	Donut Chart: Showed which education fields had the highest attrition rates, highlighting that employees with a life sciences background accounted for 38% of those leaving, followed by 27% from the medical field.
2.	Stacked Column Chart: Illustrated attrition rates by age group, with the highest attrition occurring among employees aged 26-35.
3.	Matrix Visual: Displayed the relationship between job roles, job satisfaction (rated from 1 to 4), and attrition count. I incorporated a custom highlight effect where cells with higher values were shaded darker, making it easy to identify significant patterns.
4.	Stacked Bar Chart: Represented attrition by salary slab, showing that employees with salaries below the company average had the highest attrition rate.
5.	Area Chart: Depicted attrition by tenure in the company, with the highest attrition occurring in employees who had been with the company for only 1 year.
6.	Stacked Bar Chart: Highlighted attrition by job role, helping to identify which roles had the highest turnover.
Additional Features:
•	I customized the background of the dashboard to align with the company’s branding, providing a professional and cohesive look.
Key Insights:
The dashboard revealed several critical insights into employee attrition:
•	Education Background: 38% of employees who left the company had a life sciences background, and 27% came from the medical field.
•	Age Group: The highest attrition rate was observed among employees aged 26-35.
•	Salary: Employees with salaries below the company’s average were the most likely to leave.
•	Tenure: The highest attrition occurred among employees who had been with the company for only one year.
•	Job Roles: The job roles with the highest attrition rates were:
1.	Laboratory Technician
2.	Sales Executive
3.	Research Scientist
These insights provide a comprehensive understanding of the factors influencing employee turnover and can help inform strategic decisions to reduce attrition in the future.
