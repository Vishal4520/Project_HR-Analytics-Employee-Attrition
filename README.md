# HR Analytics – Employee Attrition Dashboard

## Project Overview
This project is a comprehensive HR Analytics Dashboard built in **Power BI** using the IBM HR Employee Attrition Dataset.  
The goal is to **analyze employee attrition**, identify key drivers, and provide actionable insights for HR decision-making.

## Dataset
- **Source:** IBM HR Analytics Employee Attrition Dataset (cleaned version)  
- **Records:** 1470 employees  
- **Key Columns:** Demographics, Job-related, Satisfaction, Attrition (target)

## Data Preparation
- Cleaned and preprocessed in Python (`Data_Cleaning.ipynb`)  
- Loaded cleaned dataset into Power BI (`HR_Attrition_Dashboard.pbix`)  
- Created **salary bins, age bands**, and **DAX measures** for KPIs

## Dashboard Features
- KPI Cards: Total Employees, Employees Left, Attrition Rate  
- Attrition Analysis Charts: Department, Job Role, Gender, Salary, Job Satisfaction  
- Employee Details Table  
- Filters / Slicers: Department, Gender, Education Field, Age Band

## Insights & Recommendations
- Low Salary → Higher Attrition  
- High Overtime → Increased Attrition  
- Low Job Satisfaction → Retention Risk  
- Departments like Sales & R&D → Need targeted strategies  
- Younger employees (<30) and those with <3 years tenure are more likely to leave


## How to Use
1. Open `HR_Attrition_Dashboard.pbix` in Power BI  
2. Explore KPIs, charts, and filters to analyze attrition trends  
3. Use `Data_Cleaning.ipynb` for preprocessing or data updates  

**Author:** Vishal Wavtlikar  
**LinkedIn :**  www.linkedin.com/in/vishal-wavtlikar-3aab2a20a 
