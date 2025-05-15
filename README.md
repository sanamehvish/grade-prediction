This project focuses on predicting student grades (A, B, C, D, F) based on various academic and demographic features using machine learning classification algorithms. The goal is to help educational institutions identify students' performance levels early and provide necessary support to improve learning outcomes.

## Features Used
- Average marks (numerical)
- Gender (categorical)
- Study hours per week
- Attendance percentage
- Other relevant student data (can be expanded)

## Dataset
A synthetic dataset of 1000 students was generated for this project, including grades as the target variable. The dataset includes both numerical and categorical features, preprocessed using label encoding.

## Methodology
- Data preprocessing (handling categorical variables, feature scaling)
- Train-test split (80-20)
- Model training using multiple algorithms: Random Forest, XGBoost, and Logistic Regression
- Model evaluation with accuracy, confusion matrix, and loss function analysis
- Visualizations comparing actual vs predicted grades

## Libraries Required
- numpy
- pandas
- scikit-learn
- xgboost
- matplotlib
- seaborn
