# mini-data-science-project

# Mini Data Science Project: Student Performance Prediction Using Machine Learning

## Project Overview
This project analyzes student academic performance using data science and machine learning techniques. The main aim of the project is to understand how factors such as study time, absences, and previous grades affect student final grades.

## Research Question
How do study habits and academic factors affect student performance, and can machine learning models accurately predict student final grades?

## Dataset
The dataset used in this project is the Student Performance Dataset from the UCI Machine Learning Repository. The student-mat.csv file was used for the analysis.

## Features Used
- studytime
- absences
- G1
- G2

## Target Variable
- G3 (Final Grade)

## Exploratory Data Analysis
The following visualizations were created:
- Distribution of Final Grades
- Study Time vs Final Grade
- Absences vs Final Grade
- Correlation Heatmap of Numerical Variables
- Study Time Category vs Final Grade

## Machine Learning Models
1. Linear Regression
2. Random Forest Regressor
3. Decision Tree Regressor

## Model Performance

| Model | R² Score | MAE | MSE |
|---|---:|---:|---:|
| Linear Regression | 0.81 | 1.30 | 4.25 |
| Random Forest Regressor | 0.87 | 1.05 | 2.90 |
| Decision Tree Regressor | 0.83 | 1.16 | 3.85 |

## Key Findings
- Study time and absences are related to student academic performance.
- Previous grades G1 and G2 are the strongest predictors of final grade G3.
- Among the tested models, Random Forest Regressor achieved the best performance.
- Machine learning can be effectively used to predict student final grades.

## Tools and Libraries
- Python
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## Conclusion
This project shows that data science and machine learning can be used to analyze and predict student academic performance. The results demonstrate that academic indicators such as study time, absences, and previous grades are useful for prediction, and that Random Forest Regressor provided the best performance among the tested models.
