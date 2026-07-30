# Employee Attrition Analysis

## Project Overview

Employee attrition is a major challenge for organizations because losing experienced employees can increase recruitment costs, reduce productivity, and impact overall business performance.

This project presents an end-to-end data analytics workflow using Python to analyze employee attrition. The project includes data cleaning, exploratory data analysis (EDA), business insights, and a baseline machine learning model to predict employee attrition.

---

## Project Objectives

- Analyze employee attrition patterns.
- Identify the key factors associated with employee turnover.
- Visualize important business insights.
- Build a baseline machine learning model for attrition prediction.
- Provide business recommendations based on data-driven findings.

---

## Dataset

**Source:** IBM HR Analytics Employee Attrition Dataset  
**Records:** 1,470 employees  
**Features:** 35 employee-related attributes  

The dataset contains demographic information, job-related characteristics, compensation details, and employee satisfaction indicators.

---

## Technologies Used

- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## Project Workflow

1. Load Dataset
2. Data Cleaning
3. Exploratory Data Analysis (EDA)
4. Machine Learning
5. Model Evaluation
6. Business Recommendations
7. Conclusion

---

# Exploratory Data Analysis (EDA)

## Attrition Distribution

This visualization shows the distribution of employees who stayed and employees who left the company.

![Attrition Distribution](images/Attrition%20Distribution.png)

---

## Correlation Matrix

The correlation matrix helps identify relationships between numerical features and employee attrition.

![Correlation Matrix](images/Correlation%20Matrix.png)

---

## Monthly Income vs Attrition

Employees with lower monthly income showed higher attrition rates compared to employees with higher income levels.

![Monthly Income vs Attrition](images/Monthly%20Income%20vs%20Attrition.png)

---

## Overtime vs Attrition

Employees working overtime had a higher likelihood of leaving the company.

![Overtime vs Attrition](images/Overtime%20vs%20Attrition.png)

---

## Work-Life Balance vs Attrition

Poor work-life balance was associated with higher employee turnover.

![Work-Life Balance vs Attrition](images/Work-Life%20Balance%20vs%20Attrition.png)

---

## Job Satisfaction vs Attrition

Employees with lower job satisfaction showed higher attrition rates.

![Job Satisfaction](images/job%20satisfaction.png)

---

# Key Insights

The exploratory data analysis revealed several important findings:

- Employees working overtime were more likely to leave the company.
- Lower monthly income was associated with higher attrition.
- Employees with lower job satisfaction had higher turnover.
- Poor work-life balance increased the likelihood of attrition.
- Employees with fewer years at the company were more likely to resign.
- Younger employees showed a higher attrition rate.

---

# Machine Learning

A Logistic Regression model was developed as a baseline classification model to predict employee attrition.

## Model Performance

| Metric | Score |
|---|---|
| Accuracy | 85.0% |
| Precision | 30.8% |
| Recall | 10.3% |
| F1 Score | 15.4% |

The model achieved good overall accuracy but showed limited performance in identifying employees who actually left the company due to class imbalance.

---

# Business Recommendations

Based on the analysis, the following recommendations were proposed:

- Reduce excessive overtime.
- Improve employee job satisfaction.
- Support new employees through onboarding programs.
- Review compensation strategies.
- Promote a healthier work-life balance.

---

# Project Structure

```
employee-attrition-analysis/
│
├── Employee_Attrition_Analysis.ipynb
├── WA_Fn-UseC_-HR-Employee-Attrition.csv
├── README.md
├── requirements.txt
│
└── images/
    ├── Attrition Distribution.png
    ├── Correlation Matrix.png
    ├── Monthly Income vs Attrition.png
    ├── Overtime vs Attrition.png
    ├── Work-Life Balance vs Attrition.png
    └── job satisfaction.png
```

---

# How to Run

1. Clone this repository.
2. Install the required libraries.
3. Open the notebook using Jupyter Notebook or Google Colab.
4. Run the notebook cells sequentially.

---

# Author

**Khalid Alshehri**

Management Information Systems (MIS) Student  

King Faisal University
