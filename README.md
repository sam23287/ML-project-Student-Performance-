# Student Performance Analysis

![8741017](https://github.com/user-attachments/assets/b091e3c6-4293-4059-9dbc-ed91b7874ec3)

## Project Overview
This project aims to analyze the relationship between students' academic performance in mathematics and various demographic factors. By leveraging statistical techniques and machine learning models, the goal is to identify key factors influencing performance and predict outcomes based on these factors.

## Dataset Information
The dataset contains the following features:

- **Gender**: Gender of the student (Male/Female).
- **Race/Ethnicity**: The race or ethnicity group the student belongs to.
- **Parental Level of Education**: The highest level of education completed by the student's parents.
- **Lunch**: Type of lunch the student receives (standard or free/reduced).
- **Test Preparation Course**: Whether the student completed a test preparation course (completed/not completed).
- **Math Score**: The student's score in the mathematics exam.
- **Reading Score**: The student's score in the reading exam.
- **Writing Score**: The student's score in the writing exam.

## Problem Statement
The objective of this project is to:
1. Analyze the factors that influence students' mathematics performance.
2. Build predictive models to estimate students' math scores based on demographic and other relevant features.

## Project Workflow

### Data Cleaning & Preprocessing
- Handle missing values, outliers, and incorrect data entries.
- Encode categorical variables and normalize numerical features where necessary.

### Exploratory Data Analysis (EDA)
- Gain insights into relationships between features.
- Visualize data distributions, correlations, and key patterns.
- Univariate, Bivariate and Multivariate Analysis.

### Feature Engineering
- Create new features or modify existing ones to enhance the performance of the machine learning models.

### Modeling
- Implement various regression models to predict the students’ mathematics scores. Models explored include:
  - Linear Regression
  - Decision Trees
  - Random Forest
  - Gradient Boosting
  - K-Nearest Neighbors
  - Support Vector Regression
  - CatBoost Regressor
  - XGBoost Regressor

### Evaluation
- Use evaluation metrics such as Mean Absolute Error (MAE), Mean Squared Error (MSE), and R² to assess model performance.

## Tools and Technologies
- **Python**: For data analysis and model building.
- **Libraries**:
  - Pandas, NumPy: Data manipulation and analysis.
  - Scikit-learn: Machine learning models and evaluation.
  - Matplotlib, Seaborn: Data visualization.
  - CatBoost, XGBoost: Advanced regression models.
  - Flask: For creating the API.

## Results
- **Insights**: Key demographic factors influencing student performance in mathematics were identified.
- **Model Performance**: The best-performing model achieved an R² score of 88%.

## Conclusion
This project provides insights into the academic performance of students and builds a predictive model that can assist educators and policymakers in identifying students who may need additional support based on demographic factors.
