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

- **Source:** IBM HR Analytics Employee Attrition Dataset
- **Records:** 1,470 employees
- **Features:** 35 employee-related attributes

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

1. Project Overview
2. Load Dataset
3. Data Cleaning
4. Exploratory Data Analysis (EDA)
5. Machine Learning
6. Model Evaluation
7. Business Recommendations
8. Conclusion

---

## Key Insights

The exploratory data analysis revealed several important findings:

- Employees working overtime were more likely to leave the company.
- Lower monthly income was associated with higher attrition.
- Employees with lower job satisfaction had higher turnover.
- Poor work-life balance increased the likelihood of attrition.
- Employees with fewer years at the company were more likely to resign.
- Younger employees showed a higher attrition rate.

---

## Machine Learning

A Logistic Regression model was developed as a baseline classification model to predict employee attrition.

### Model Performance

| Metric | Score |
|---------|-------|
| Accuracy | 85.0% |
| Precision | 30.8% |
| Recall | 10.3% |
| F1 Score | 15.4% |

The model achieved good overall accuracy but showed limited performance in identifying employees who actually left the company due to class imbalance.

---

## Business Recommendations

Based on the analysis, the following recommendations were proposed:

- Reduce excessive overtime.
- Improve employee job satisfaction.
- Support new employees through onboarding programs.
- Review compensation strategies.
- Promote a healthier work-life balance.

---

## Project Structure

```
employee-attrition-analysis/
│
├── Employee_Attrition_Analysis.ipynb
├── WA_Fn-UseC_-HR-Employee-Attrition.csv
├── README.md
└── requirements.txt
```

---

## How to Run

1. Clone this repository.
2. Install the required libraries.
3. Open the notebook using Jupyter Notebook or Google Colab.
4. Run the notebook cells sequentially.

---

## Author

**K Amer**

Management Information Systems (MIS) Student

King Faisal University
