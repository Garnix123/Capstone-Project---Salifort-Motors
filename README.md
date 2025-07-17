# Salifort Motors Employee Attrition Prediction

This project was completed as part of the **Google Advanced Data Analytics Professional Certificate** on Coursera. The objective is to analyze HR data from Salifort Motors and build a predictive model to determine whether an employee will leave the company.

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

### Attrition by Salary Level  
*(Insert bar chart image here if available)*

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
![Confusion Matrix](images/confusion_matrix.png)  
*The model demonstrates high accuracy with minimal false predictions.*

---

## ✅ Conclusions
- Main factors for attrition: **low satisfaction**, **high workload**, and **lack of promotion**.
- **Recommendations:**
  - Improve employee engagement.
  - Balance workload.
  - Increase career growth opportunities.
