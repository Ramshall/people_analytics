# People Analytics: Employee Satisfaction Analysis
---

## Project Overbiew
This project aims to visualize and analyze employee satisfaction levels based on a Likert scale of 1-5, where higher values indicate higher satisfaction. The analysis results are presented in two interactive dashboards in Power BI: Overview and Multivariate Analysis.

## Dashboard Insights
### Overview
<img width="1625" height="1002" alt="image" src="https://github.com/user-attachments/assets/7c99ce75-c5bd-486b-9502-641db5ae2f84" />

This dashboard provides a general overview of employee satisfaction levels and other important attributes. Visualizations include:
* Average satisfaction, workload, work-life balance, level of stress, and work environment for all employees and per department.
* Employee age distribution.
* Number of employees by job level.

This dashboard also features interactive filters based on gender, contract type, and department for deeper data exploration.

### Multivariate Analysis: Matrix Correlation
<img width="1626" height="1007" alt="image" src="https://github.com/user-attachments/assets/e1217f42-7942-47a0-b273-2f39382d82a4" />

This dashboard focuses on the relationships between variables, displaying:
* A Pearson correlation matrix to identify relationships between key variables.
* A detailed table showing individual employee satisfaction levels.

---

## Repo Content
This repository contains the main compnenent of the project
* **Power BI Report/**: This folder contains the Power BI `.pbix` file that you can open and explore.
* **Data/**: This folder contains the cleaned dataset in `.csv` format used for visualization.
* **EDA/**: This folder contains the Jupyter Notebook (`.ipynb`) documenting the Exploratory Data Analysis (EDA) process, including data cleaning and manipulation steps.

---

## Workflow
The project workflow follows these steps:
1. Exploratory Data Analysis (EDA): Raw data is analyzed, cleaned, and manipulated using Python/Jupyter Notebook. Details of this process can be found in the .ipynb file in the EDA/ folder.
2. Clean Data Storage: The cleaned data is saved in .csv format in the Data/ folder.
3. Data Visualization: The clean data is then used to build interactive visualizations in Power BI.
4. DAX Implementation: Several DAX (Data Analysis Expressions) formulas were created in Power BI to add conditional coloring logic to tables, highlighting the highest averages across departments.

---

## Tools
* Microsoft Power BI: For creating interactive dashboards and data visualizations.
* Python / Jupyter Notebook: For Exploratory Data Analysis (EDA), data cleaning, and manipulation.



