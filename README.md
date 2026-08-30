# Employee Salary Prediction

## Project Objective

The objective of this project is to build and compare different machine learning regression models for predicting employee salaries. The project focuses on data preprocessing, categorical feature encoding, numerical feature scaling, model development, and evaluation using appropriate regression metrics.

## Dataset Description

The dataset contains employee-related information used for salary prediction. It includes features such as Employee ID, Age, Gender, Department, Experience Years, and Performance Score.

- Problem Type: Regression
- Target Variable: Salary
- Total Records Used: 1,000
- Training Records: 800
- Testing Records: 200

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- Jupyter Notebook

## Data Preprocessing

The following preprocessing steps were performed:

1. Loaded the dataset.
2. Handled missing values.
3. Removed duplicate records.
4. Encoded categorical features.
5. Scaled numerical features using StandardScaler.
6. Split the dataset into training and testing sets using an 80:20 ratio.

## Machine Learning Models

Three regression models were developed:

1. Linear Regression
2. Decision Tree Regressor
3. Random Forest Regressor

## Model Evaluation

The models were evaluated using:

- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- R² Score

## Model Comparison

Linear Regression performed the best among the three models based on the evaluation results.

### Advantages

- Linear Regression: Simple and fast.
- Decision Tree: Easy to understand.
- Random Forest: Good prediction performance.

### Limitations

- Linear Regression: Assumes a linear relationship.
- Decision Tree: Can overfit.
- Random Forest: More complex and slower.

## Conclusion

The project successfully developed and compared three machine learning regression models for employee salary prediction. Linear Regression performed the best, achieving the lowest prediction errors and the highest R² Score of 0.721. Therefore, Linear Regression is recommended as the best-performing model for this dataset.

## Project Structure

```text
Employee_Salary_Prediction/
│
├── dataset/
│   └── employee_performance.csv
│
├── notebook/
│   └── Employee_Salary_Prediction.ipynb
│
├── report/
│   └── Report2.pdf
│
└── README.md
```

## Student / Author Name
Student Name: Aima Shahid
