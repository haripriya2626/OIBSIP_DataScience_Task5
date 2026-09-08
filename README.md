# OIBSIP Data Science Task 5 – Sales Prediction Using Python

## Objective

The objective of this project is to build a machine learning regression model that predicts product sales based on advertising expenditure across TV, Radio, and Newspaper channels.

## Dataset

The project uses the classic Advertising dataset containing:

- TV Advertising Spend
- Radio Advertising Spend
- Newspaper Advertising Spend
- Sales

## Steps Performed

1. Loaded the Advertising dataset
2. Removed the unnecessary index column
3. Checked dataset shape, columns, data types, missing values, and duplicates
4. Performed descriptive statistical analysis
5. Created a pairplot of all variables
6. Created scatter plots:
   - Sales vs TV
   - Sales vs Radio
   - Sales vs Newspaper
7. Generated a correlation heatmap
8. Split the dataset into 80% training and 20% testing
9. Trained a Linear Regression model
10. Trained a Random Forest Regressor
11. Evaluated both models using MAE, RMSE, and R² score
12. Compared the performance of both models
13. Generated a residual plot for the best model
14. Analysed feature importance
15. Predicted sales for a new advertising budget

## Tools and Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook
- VS Code

## Model Performance

| Model | MAE | RMSE | R² Score |
|---|---:|---:|---:|
| Linear Regression | 1.4608 | 1.7816 | 0.8994 |
| Random Forest Regressor | 0.6289 | 0.7577 | 0.9818 |

## Best Model

The **Random Forest Regressor** was selected as the best-performing model because it achieved the lowest MAE and RMSE and the highest R² score.

## Feature Importance

- TV: 0.6247
- Radio: 0.3621
- Newspaper: 0.0131

TV advertising had the highest impact on sales, followed by Radio, while Newspaper had the least influence.

## Conclusion

The project successfully demonstrates the use of machine learning regression techniques for sales prediction. Random Forest Regressor performed better than Linear Regression and was selected as the final model.