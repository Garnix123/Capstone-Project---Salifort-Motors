# Employee Attrition Prediction using Random Forest on HR Dataset - Salifort Motors

This project was completed as part of the **Google Advanced Data Analytics Professional Certificate** on Coursera. The objective is to analyze HR data from Salifort Motors and build a predictive model to determine whether an employee will leave the company.

## Introduction

Salifort Motors is a fictitious multinational company in the automotive industry, created for educational and analytical purposes. It is known for its commitment to innovation, quality, and operational efficiency, supplying advanced components and consulting solutions to leading car manufacturers worldwide. With a diverse workforce across multiple regions, Salifort Motors emphasizes talent-driven growth and continuous improvement. As part of its strategic objectives, the company aims to leverage data analytics to address business challenges—such as understanding employee attrition—to maintain a productive and engaged workforce.

---

## 📂 Project Overview
- **Goal:** Predict employee attrition and identify factors contributing to turnover.
- **Dataset:** HR dataset with 15,000 records including satisfaction level, evaluation scores, working hours, and salary.
- **Tech Stack:** Python, Pandas, Matplotlib, Seaborn, Scikit-learn.

---

## 📊 Dataset Overview
The dataset contains the following columns:

- `satisfaction_level`: Employee satisfaction (0–1)
- `last_evaluation`: Last evaluation score
- `number_project`: Number of projects
- `average_montly_hours`: Average monthly working hours
- `time_spend_company`: Tenure in years
- `Work_accident`: Had a work accident (0/1)
- `left`: Employee left company (target)
- `promotion_last_5years`: Promotion in the last 5 years (0/1)
- `Department`: Department name
- `salary`: Salary category (low, medium, high)

---

### 📑 Sample of Dataset
<img width="552" height="314" alt="Image" src="https://github.com/user-attachments/assets/6c178be8-0957-4704-846d-eb97f10dc5c0" />  

The dataset contains 10 columns with both numerical and categorical variables.*

---

## 🔍 Key Insights
- Employees with **low satisfaction levels** and **very high or very low working hours** are more likely to leave.
- Attrition is higher among **low-salary employees** and **sales department staff**.
- Very few employees were promoted in the last 5 years.

---

## 📈 Visualizations

### Feature Correlation Heatmap  
<img width="966" height="620" alt="Image" src="https://github.com/user-attachments/assets/ad41f9e9-0728-4fa7-be16-e8d8e2c94280" />

The correlation heatmap confirms that the number of projects, monthly hours, and evaluation scores all have some positive correlation with each other, and whether an employee leaves is negatively correlated with their satisfaction level.

### Attrition rate by Salary Level  

<img width="552" height="320" alt="Image" src="https://github.com/user-attachments/assets/a6c43528-a6d1-44a7-91e6-4bbeedfde6c7" />

### Attrition rate by Department

<img width="638" height="290" alt="Image" src="https://github.com/user-attachments/assets/90719e7a-8770-4392-8d07-3d3f3ef59247" />

---

## 🧠 Model & Performance
Two models were tested:
- **Logistic Regression**
- **Random Forest Classifier** (Best Performance)

### Metrics for Random Forest:
- **Accuracy:** ~97%
- **Precision:** 0.94
- **Recall:** 0.88
- **F1-score:** 0.91

---

### Confusion Matrix
<img width="343" height="265" alt="Image" src="https://github.com/user-attachments/assets/ea276e61-8957-4f44-986d-e0fb803d18fa" />  

The model demonstrates high accuracy with minimal false predictions.*

---

## ✅ Conclusions
- The analysis confirms that overwork and lack of career growth are key drivers of attrition at Salifort Motors. Employees with excessive workloads, long hours, and no promotions are more likely to leave.
- **Recommendations:**
  - Limit the number of projects per employee.

  - Reward or compensate overtime work and clearly communicate policies.

  - Consider promoting employees with longer tenure or investigate their dissatisfaction.

  - Promote a healthier work-life balance and transparent expectations.


