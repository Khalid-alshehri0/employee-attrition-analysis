# Employee Attrition Analysis

## Project Overview

Employee turnover is one of the biggest challenges organizations face today. Losing skilled employees does not only increase hiring and training costs, but can also affect productivity, team performance, and long-term business growth.

In this project, I explored the factors behind employee attrition using data analytics techniques. The goal was to understand **why employees leave**, identify the main patterns associated with turnover, and transform raw HR data into meaningful business insights.

This project follows an end-to-end analytics workflow, starting from data preparation and exploratory analysis, followed by machine learning modeling and business recommendations.

---

# Project Objectives

The main objectives of this project were:

- Understand employee attrition patterns.
- Discover the factors that influence employee turnover.
- Analyze relationships between employee characteristics and attrition.
- Create meaningful visualizations to communicate insights.
- Build a baseline machine learning model to predict employee attrition.
- Provide actionable recommendations based on data findings.

---

# Dataset

To investigate employee turnover, this project uses the **IBM HR Analytics Employee Attrition Dataset**.

The dataset contains detailed information about employees, including:

- Demographic characteristics.
- Job-related information.
- Salary and compensation details.
- Employee satisfaction indicators.
- Work environment factors.

### Dataset Information

- **Source:** IBM HR Analytics Employee Attrition Dataset
- **Records:** 1,470 employees
- **Features:** 35 employee-related attributes

This dataset provides a realistic HR scenario for understanding the reasons behind employee decisions to leave an organization.

---

# Technologies Used

The project was developed using the following tools and technologies:

- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

These tools were used for data preprocessing, visualization, statistical exploration, and machine learning.

---

# Project Workflow

The project followed a structured data analytics workflow:

1. **Load Dataset**
   
   Importing the HR dataset and understanding the available features.

2. **Data Cleaning**

   Preparing the data by handling unnecessary columns, transforming variables, and making the dataset ready for analysis.

3. **Exploratory Data Analysis (EDA)**

   Exploring employee characteristics and identifying patterns related to attrition.

4. **Machine Learning**

   Developing a baseline classification model to predict employee attrition.

5. **Model Evaluation**

   Measuring model performance using classification metrics.

6. **Business Recommendations**

   Translating analytical findings into possible actions organizations can take.

---

# Exploratory Data Analysis (EDA)

After preparing the dataset, exploratory analysis was conducted to answer key questions:

- Which employees are more likely to leave?
- What factors are strongly associated with attrition?
- How do work conditions and satisfaction affect employee decisions?

## Attrition Distribution

The first step was understanding the overall distribution of employees who stayed versus employees who left the company.

![Attrition Distribution](images/Attrition%20Distribution.png)

---

## Correlation Matrix

The correlation matrix was used to explore relationships between numerical features and identify variables that may influence employee attrition.

![Correlation Matrix](images/Correlation%20Matrix.png)

---

## Monthly Income vs Attrition

Salary was analyzed to understand whether compensation levels were related to employee turnover.

The analysis showed that employees with lower monthly income had higher attrition rates.

![Monthly Income vs Attrition](images/Monthly%20Income%20vs%20Attrition.png)

---

## Overtime vs Attrition

Workload was another important factor investigated.

Employees working overtime showed a higher tendency to leave the organization, suggesting that excessive workload may negatively affect employee retention.

![Overtime vs Attrition](images/Overtime%20vs%20Attrition.png)

---

## Work-Life Balance vs Attrition

The analysis also explored how work-life balance impacts employee decisions.

Employees experiencing poorer work-life balance showed higher attrition rates.

![Work-Life Balance vs Attrition](images/Work-Life%20Balance%20vs%20Attrition.png)

---

## Job Satisfaction vs Attrition

Employee satisfaction was analyzed to understand its relationship with turnover.

Lower job satisfaction levels were associated with a higher probability of employees leaving.

![Job Satisfaction](images/job%20satisfaction.png)

---

# Key Insights

The exploratory analysis revealed several important patterns:

- Employees working overtime were more likely to leave the company.
- Lower monthly income was associated with higher attrition.
- Employees with lower job satisfaction showed higher turnover rates.
- Poor work-life balance increased the likelihood of resignation.
- Employees with fewer years at the company were more likely to leave.
- Younger employees showed higher attrition rates.

These findings highlight that employee retention is influenced by multiple factors, including compensation, workload, satisfaction, and workplace experience.

---

# Machine Learning

After understanding the factors behind attrition, a baseline machine learning model was developed to predict whether an employee is likely to leave the company.

A **Logistic Regression** model was selected as a starting point because it is simple, interpretable, and suitable for binary classification problems.

## Model Performance

| Metric | Score |
|---|---|
| Accuracy | 85.0% |
| Precision | 30.8% |
| Recall | 10.3% |
| F1 Score | 15.4% |

The model achieved good overall accuracy but struggled to correctly identify employees who actually left the company.

This limitation is mainly caused by **class imbalance**, where employees who stayed represent the majority of the dataset compared to employees who left.

---

# Business Recommendations

Based on the analysis results, the following recommendations were suggested:

### Reduce Excessive Overtime
Organizations should monitor workload and avoid continuous overtime to improve employee retention.

### Improve Employee Satisfaction
Regular feedback, career development opportunities, and engagement programs can increase satisfaction.

### Support New Employees
Employees with shorter tenure showed higher attrition, highlighting the importance of strong onboarding programs.

### Review Compensation Strategies
Competitive salaries and fair compensation can help reduce turnover.

### Promote Better Work-Life Balance
Creating a healthier balance between work and personal life can improve employee loyalty.

---

# Project Structure
