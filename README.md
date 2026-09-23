## Simple Linear Regression: Salary Prediction
**Project Overview**

This project demonstrates Simple Linear Regression to investigate the relationship between Years of Experience and Salary.

The model was implemented using three different approaches:

- Gradient Descent from scratch
- Scikit-learn LinearRegression
- Statsmodels Ordinary Least Squares (OLS)

The results from all three approaches were compared to verify that the manually implemented Gradient Descent model produced results consistent with established Python libraries.

**Dataset**

The dataset contains 30 observations with two main variables:

- YearsExperience — years of professional experience
- Salary — annual salary

The dataset is located in:

data/salary_data.csv

**Objective**

The main objectives of this project are to:

1. Understand the mathematical foundation of Simple Linear Regression.
2. Implement Linear Regression using Gradient Descent from scratch.
3. Implement Linear Regression using Scikit-learn.
4. Perform OLS regression using Statsmodels.
5. Compare the results from all three approaches.
6. Evaluate the relationship between Years of Experience and Salary.
   
**Libraries Used**
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Statsmodels
  
**Methodology**

The project follows these main steps:

1. Load and inspect the dataset.
2. Explore the relationship between Years of Experience and Salary.
3. Visualize the data using a scatter plot.
4. Implement the Linear Regression cost function.
5. Calculate gradients for the model parameters.
6. Optimize the parameters using Gradient Descent.
7. Fit the model using Scikit-learn.
8. Fit the model using Statsmodels OLS.
9. Compare the slope and intercept from all three methods.
10. Evaluate the regression model using R² and other statistical measures.
    
**Linear Regression Model**

The regression model is:

ŷ = wx + b

where:

- ŷ = predicted salary
- x = years of experience
- w = slope
- b = intercept

The final regression equation was approximately:

ŷ = 9449.96x + 24848.20

The slope indicates that each additional year of experience is associated with approximately a $9,450 increase in predicted salary within this dataset.

**Model Comparison**

Gradient Descent, Scikit-learn LinearRegression, and Statsmodels OLS produced nearly identical slope and intercept values.
| Method | Slope | Intercept |
|---|---:|---:|
| Gradient Descent | 9449.96 | 24848.20 |
| Scikit-learn | 9449.96 | 24848.20 |
| Statsmodels OLS | 9449.96 | 24848.20 |


**Model Performance**

The Statsmodels OLS model produced an R² value of approximately 0.957, indicating that Years of Experience explains approximately 95.7% of the variation in Salary in this dataset.

**Conclusion**

This project provided practical experience with the mathematical foundation of Linear Regression, optimization using Gradient Descent, Python implementation, and statistical analysis.

The comparison between Gradient Descent, Scikit-learn, and Statsmodels demonstrated that different implementations can produce essentially the same regression coefficients when they solve the same least-squares regression problem.
