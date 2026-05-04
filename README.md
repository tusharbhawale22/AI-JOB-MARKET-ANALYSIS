# AI-JOB-MARKET-ANALYSIS

📌 Overview

This project analyzes salary trends in the tech industry and builds a machine learning model to predict salaries based on various factors such as job role, experience level, skills, and company type.

The goal is to extract meaningful insights and help understand what drives higher salaries in tech roles.

🎯 Objectives
Analyze salary distribution across job roles
Study salary trends over time
Understand impact of experience on salary
Identify top skills associated with high salaries
Compare salaries across company types
Build a regression model to predict salaries

📂 Dataset Features
Job_Title – Role (Data Analyst, ML Engineer, etc.)
Experience_Level – Entry, Mid, Senior
Salary_USD – Salary in USD
Salary_INR – Converted salary
Company_Type – Big Tech, Startup, Freelance
Country – Work location
Top_Skill – Key skill (Python, SQL, etc.)
Year – Year of record

🧹 Data Cleaning Steps
Removed missing values and duplicates
Standardized column names
Converted salary from USD to INR
Created salary in lakhs for better readability
Encoded categorical variables for modeling

📊 Exploratory Data Analysis
Key Insights:
NLP Engineers have the highest salaries
AI/ML roles dominate high-paying jobs
Salary increases significantly with experience
Python and ML frameworks are top skills
Company type has minimal impact on salary

📈 Visualizations
Average Salary by Job Role
Salary Trend Over Years
Salary Distribution by Experience
Top Skills for High Salary
Average Salary by Company

🤖 Machine Learning Model
Model Used:
Linear Regression
Features Used:
Job Role
Experience Level
Company Type
Skills
Country
Evaluation Metrics:
R² Score: ~0.86
MAE: ~15 LPA
MSE: Calculated

Interpretation:
The model explains ~86% of salary variation, showing strong predictive performance.
