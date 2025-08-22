# Student Score Prediction 
Task 1 @ Elevvo ML Internship 

## Instructions
1. Dataset (Recommended): Student Performance Factors ([Kaggle](https://www.kaggle.com/)). 
2. Build a model to predict students' exam scores based on their study hours.
3. Perform data cleaning and basic visualization to understand the dataset.
4. Split the dataset into training and testing set.
5. Train a linear regression model to estimate final scores.
6. Visualize predictions and evaluate model performance.
### Bonus:
1. Try polynomial regression and compare performance .
2. Try experimenting with different feature combinations (e.g., removing or adding features like sleep, participation, etc.).

## Dataset
- [Student Score Dataset](https://www.kaggle.com/datasets/lainguyn123/student-performance-factors)

## Notebook
- [Student Score Prediction](https://github.com/Asma-Nasr/Student-Score-Prediction/blob/main/student_score_prediction.ipynb)

## Performance Comparison

| Models                     | MSE       | R^2        |
|---------------------------|-----------|-----------|
| Model1 with outliers      | 5.082608  | 0.667794  |
| Model2 without outliers    | 1.255329  | 0.875017  |
