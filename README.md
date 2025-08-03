# Student Dropout Prediction Using Machine Learning

## Project Overview
This project aims to predict the likelihood of students dropping out based on various academic, behavioral, and demographic features. By leveraging machine learning models, the solution helps educational institutions take early intervention measures to improve retention and student success.

## Problem Statement
Student dropout is a persistent issue that impacts institutional performance, funding, and student futures. Identifying at-risk students early using predictive analytics allows stakeholders to offer targeted support and prevent dropouts.

## Data Source
- **Student Dropout Dataset** from a public repository.
- Includes features like age, course grades, parental education, absenteeism, etc.
- Data cleaned, encoded, and prepared for binary classification (Dropout vs. Not Dropout).

## Steps Performed
1. **Data Preprocessing**
   - Handled missing values and outliers.
   - Performed label encoding and normalization.

2. **Exploratory Data Analysis (EDA)**
   - Visualized feature correlations and class distributions.
   - Identified key influencing factors such as attendance, age, and prior grades.

3. **Model Development**
   - Trained and tested multiple classification models:
     - Logistic Regression
     - Random Forest
     - Gradient Boosting
     - Support Vector Machine (SVM)
   - Tuned hyperparameters using cross-validation.

4. **Evaluation**
   - Compared models using accuracy, precision, recall, and F1-score.
   - Selected the best-performing model based on balanced performance.

5. **Insights**
   - Attendance, academic performance, and parental background strongly influenced dropout risk.
   - Provided actionable insights to educators.

## ⚙ Requirements

- Python 3.8+
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- jupyter

```bash
pip install -r requirements.txt
