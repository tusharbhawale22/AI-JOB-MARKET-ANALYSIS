# 🤖 AI Job Market — Salary Analysis & Prediction

![Python](https://img.shields.io/badge/Python-3.10-blue?style=flat&logo=python)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-150458?style=flat&logo=pandas)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-ML-F7931E?style=flat&logo=scikit-learn)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen?style=flat)

---

## 📌 Project Overview

This project performs **Exploratory Data Analysis (EDA)** and **Salary Prediction** on the AI job market dataset.
It uncovers key salary trends across job roles, countries, experience levels, company types, and in-demand skills —
and builds a **Linear Regression model** to predict salaries with **86.7% accuracy (R² = 0.867)**.

> **Business Goal:** Help job seekers, HR teams, and companies make data-driven salary decisions in the AI industry.

---

## 📂 Project Structure

```
AI-JOB-MARKET-ANALYSIS/
│
├── data/
│   └── ai_job_market_dataset.csv       # Dataset used for analysis
│
├── notebooks/
│   └── salary_analysis.ipynb           # Main Jupyter Notebook
│
├── images/                             # Chart screenshots
│   ├── avg_salary_by_role.png
│   ├── salary_trend_over_years.png
│   ├── salary_by_experience.png
│   ├── top_skills_high_salary.png
│   └── salary_by_company_type.png
│
├── requirements.txt                    # Required Python libraries
└── README.md                           # Project documentation
```

---

## 📊 Dataset Information

| Feature | Description |
|---|---|
| `Year` | Year of job posting (2022–2026) |
| `Job_Title` | Role (Data Scientist, AI Engineer, etc.) |
| `Country` | Country of the job (USA, India, UK, etc.) |
| `Company_Type` | Startup / Big Tech / Freelance |
| `Experience_Level` | Entry / Mid / Senior |
| `Salary_USD` | Salary in US Dollars |
| `Remote` | Remote work availability (Yes/No) |
| `Top_Skill` | Most in-demand skill for the role |

- **Rows:** 2,000
- **Columns:** 8
- **Missing Values:** None
- **Source:** [Kaggle — AI Job Market Dataset](https://www.kaggle.com/)

---

## 🔍 Key Insights from EDA

### 1. 💼 Average Salary by Job Role
- **ML Engineers & AI Engineers** earn the highest average salaries
- **Data Analysts** are at the lower end of the pay scale
- Specialized AI roles clearly command a premium over general data roles

### 2. 📈 Salary Trend Over Years (2022–2026)
- Salaries show a **steady upward trend** across all job roles
- Indicates growing demand and increasing compensation in the AI industry

### 3. 🎓 Salary by Experience Level
- **Senior-level** professionals earn significantly higher with a wider salary spread
- **Entry-level** salaries are tightly clustered at the lower range
- Experience is the **single biggest salary differentiator**

### 4. 🛠️ Top Skills for High Salary
- **Python** and **PyTorch** dominate among high-earning professionals
- Deep learning and programming proficiency are key to higher pay

### 5. 🏢 Salary by Company Type
- **Big Tech** companies offer the highest average salaries
- **Freelance** roles have the most variable and generally lower compensation

---

## 🤖 Salary Prediction Model

| Metric | Value |
|---|---|
| Algorithm | Linear Regression |
| Train/Test Split | 80% / 20% |
| R² Score | **0.867** |
| MAE | 15.35 (Lakhs) |

> The model explains **~87% of salary variation**, making it reliable for salary estimation based on role, experience, country, and skills.

---

## 🚀 How to Run

### 1. Clone the Repository
```bash
git clone https://github.com/tusharbhawale22/AI-JOB-MARKET-ANALYSIS.git
cd AI-JOB-MARKET-ANALYSIS
```

### 2. Install Dependencies
```bash
pip install -r requirements.txt
```

### 3. Run the Notebook
```bash
jupyter notebook notebooks/salary_analysis.ipynb
```

---

## 🛠️ Libraries Used

```
pandas
numpy
matplotlib
seaborn
scikit-learn
jupyter
```

---

## 💡 Business Recommendations

Based on the analysis:

- 📌 **For Job Seekers:** Upskill in **Python & PyTorch** and aim for **Senior-level** roles in **Big Tech** for maximum salary growth.
- 📌 **For HR/Recruiters:** Benchmark salaries by experience level and country to stay competitive in attracting AI talent.
- 📌 **For Companies:** Invest in retaining Senior AI Engineers — their salary gap from Entry-level justifies the ROI in productivity.

---

## 📬 Connect with Me

**Tushar Bhawale**
- 🔗 GitHub: [@tusharbhawale22](https://github.com/tusharbhawale22)

---

## 📄 License

This project is open-source and available under the [MIT License](LICENSE).
