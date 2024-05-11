# Demystifying Linear Regression

## A Core Machine Learning Model

Linear regression is a fundamental statistical method and a foundational machine learning model widely used for **predicting a continuous target variable based on a linear relationship with one or more predictor variables**. Here's a breakdown of its key concepts and formulas:

**1. Model Form:**

The linear regression model assumes a linear relationship between the predictor variable(s) (X) and the target variable (y) represented by the equation:

```
y = β₀ + β₁X₁ + β₂X₂ + ... + βₙXₙ + ε
```

where:

- y is the predicted target variable (dependent variable)
- X₁ to Xₙ are the predictor variables (independent variables)
- β₀ is the intercept (y-axis value where the regression line crosses)
- β₁ to βₙ are the coefficients (slopes) for each predictor variable
- ε is the error term (accounts for the difference between the actual y values and the predicted y values)

**2. Assumptions:**

- Linear relationship between X and y
- Homoscedasticity: Constant variance of errors across the entire range of X
- Independence of errors: Errors for different data points are not related
- Normality of errors: Errors are normally distributed

**3. Least Squares Estimation:**

The goal is to find the values of β₀, β₁, ..., βₙ that minimize the sum of squared errors between the predicted y values and the actual y values. This process is called least squares estimation.

**4. Formulas:**

- **Slope (β) for a single predictor:**

```
β₁ = Σ((X₁ - X̅) * (y - ȳ)) / Σ(X₁ - X̅)²
```

where:

- X̅ is the mean of all X₁ values
- ȳ is the mean of all y values

- **Multiple predictors:** Similar formula with matrix operations for efficiency.

**5. Model Evaluation:**

- **R-squared:** Measures the proportion of variance in the target variable explained by the model (0 to 1, closer to 1 indicates better fit)
- **Mean Squared Error (MSE):** Average squared difference between predicted and actual y values (lower is better)

**6. Applications:**

Linear regression finds applications in various domains, including:

- Predicting housing prices based on features like size and location
- Forecasting sales based on historical data and marketing campaigns
- Analyzing customer behavior based on purchase history

**Remember:**

- Linear regression is a powerful tool for modeling linear relationships.
- Understanding its assumptions and limitations is crucial for interpreting results and choosing the appropriate ML model.