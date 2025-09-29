# 📌 Project Overview

Inx Future Inc. is a global company aiming to improve employee satisfaction, retention, and performance.
This dataset captures employee-related information, including demographics, performance ratings, promotions, awards, and turnover status.

## The primary goals of this project are:

1) To analyze workforce patterns.

2) To predict employee attrition (whether an employee will leave).

3) To identify key factors influencing promotions and performance.

4) To assist HR teams in taking data-driven decisions for employee management.

# 📂 Dataset Description

The dataset contains information about employees across multiple departments.

## Key Columns (may vary slightly depending on source):

1) Employee ID → Unique identifier.

2) Department → Department of employee.

3) Education → Qualification level.

4) Joining Year → Year employee joined.

5) City → Work location.

6) Age → Age of employee.

7) Gender → Male/Female.

8) EverBenched → Whether employee was ever on bench (Yes/No).

9) ExperienceInCurrentDomain → Years of domain experience.

10) LeaveOrNot → Target variable (1 = employee left, 0 = retained).
    
# ⚙️ Problem Statements

## Attrition Prediction

Build classification models to predict whether an employee will leave.

## Promotion Likelihood

Identify factors affecting promotions and predict promotion eligibility.

## Employee Insights

Generate visualizations & dashboards to assist HR in workforce planning.

# 🛠️ Tech Stack

Programming: Python (pandas, numpy, scikit-learn, keras/tensorflow)

Visualization: Matplotlib, Seaborn

ML Models: Logistic Regression, SVM, Decision Tree, Random Forest, Naïve Bayes, KNN, Artificial Neural Network (ANN)

Optimization: GridSearchCV for hyperparameter tuning

# ⚙️ Methodology

1)  Data Preprocessing

Handled missing values & outliers.

Encoded categorical variables.

Scaled numerical features.

2) Exploratory Data Analysis (EDA)

Age distribution, gender ratio, departmental attrition, bench-time analysis.

Correlation heatmaps for feature relationships.

3) Feature Engineering

Created new features such as total experience buckets and tenure groups.

4) Model Building & Evaluation
   
Models used:

1) Logistic Regression

2) Support Vector Machine (SVM)

3) Decision Tree (with GridSearchCV)

4) Random Forest (with GridSearchCV)

5) Naïve Bayes (Bernoulli)

6) K-Nearest Neighbors (KNN)

7) Artificial Neural Network (ANN)

Evaluation Metrics: Accuracy, Precision, Recall, F1-score, ROC-AUC.
