Salifort Motors Employee Attrition Prediction
This project is part of the Google Advanced Data Analytics Professional Certificate on Coursera. The objective is to analyze HR data from Salifort Motors and build a predictive model to determine whether an employee will leave the company.

📂 Project Overview
Goal: Predict employee attrition and identify factors contributing to turnover.

Dataset: Contains HR-related information for 15,000 employees, including satisfaction level, evaluation score, projects handled, average monthly hours, promotions, and salary.

Tech Stack: Python, Pandas, Matplotlib, Seaborn, Scikit-learn.

📊 Dataset Overview
The dataset includes the following features:

satisfaction_level (float): Employee satisfaction (0–1)

last_evaluation (float): Last evaluation score

number_project (int): Number of projects assigned

average_montly_hours (int): Average monthly working hours

time_spend_company (int): Years at company

Work_accident (binary): Had a work accident (0/1)

left (binary): Employee left company (target variable)

promotion_last_5years (binary): Promotion in last 5 years

Department (object): Department name

salary (object): Salary category (low, medium, high)

<img width="552" height="314" alt="Image" src="https://github.com/user-attachments/assets/6c178be8-0957-4704-846d-eb97f10dc5c0" />


🔍 Key Insights
Employees with low satisfaction levels and high working hours are more likely to leave.

The majority of attrition comes from the sales department and low salary category.

Very few employees received promotions in the last 5 years.

📈 Visualizations
Feature Correlation Heatmap
(Include heatmap image here)

Attrition by Salary Level
(Include bar chart showing attrition by salary)

🧠 Model & Performance
We applied Logistic Regression and Random Forest Classifier to predict attrition. After evaluation:

Best Model: Random Forest Classifier

Accuracy: ~97%

Key Metrics:

Precision: 0.94

Recall: 0.88

F1-score: 0.91

Confusion Matrix


✅ Conclusions
Main drivers of attrition: low satisfaction, long working hours, and lack of promotion.

Recommendation: Improve work-life balance and recognition programs.
