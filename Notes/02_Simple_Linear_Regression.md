# Simple Linear Regression

## What is Linear Regression?

Linear Regression is a supervised machine learning algorithm used to predict continuous numerical values.

It finds the relationship between two variables:

- **Feature (Independent Variable, X)** → Input value
- **Label (Dependent Variable, Y)** → Output value to predict

The goal of Linear Regression is to learn how changes in the feature affect the label.

Example:

Experience (Feature) → Salary (Label)

If years of experience increase, salary generally increases as well.

Examples:
- House Price Prediction
- Salary Prediction
- Sales Forecasting
- Rainfall Prediction

---

## Types of Linear Regression

### 1. Simple Linear Regression
Uses one input feature to predict one output value.

Example:

Experience → Salary

### 2. Multiple Linear Regression
Uses multiple input features to predict one output value.

Example:

Experience + Education + Skills → Salary

---

## Linear Regression Formula

The mathematical equation for Simple Linear Regression is:

\[
y = mx + b
\]

Where:

- **y** = Predicted value (Label)
- **x** = Input feature
- **m** = Slope of the line
- **b** = Intercept (value of y when x = 0)

Example:

\[
Salary = 5000 \times Experience + 25000
\]

This means:

- Every additional year of experience increases salary by ₹5000.
- Even with 0 years of experience, the starting salary is ₹25,000.

---

## Steps Involved in Simple Linear Regression

### Step 1: Plot the Data Points

First, we plot the feature and label values on a graph called a **scatter plot**.

Example:

| Experience (Years) | Salary (₹) |
|-------------------|-----------|
| 1 | 30000 |
| 2 | 40000 |
| 3 | 50000 |
| 4 | 60000 |
| 5 | 70000 |

The graph will contain points representing each observation.

---

### Step 2: Fit the Best Fit Line

The algorithm tries to draw a straight line that passes as close as possible to all data points.

This line is called the **Best Fit Line** or **Regression Line**.

The objective is to minimize the distance between the actual points and the line.

---

### Step 3: Learn the Relationship

During training, the model learns the best values for:

- Slope (m)
- Intercept (b)

These values define the regression line.

---

### Step 4: Make Predictions

Once the line is fitted, the model can predict new values.

Example:

If Experience = 6 years,

Predicted Salary:

\[
Salary = 5000 \times 6 + 25000
\]

\[
Salary = 55000
\]

---

## Workflow of Simple Linear Regression

Collect Data
↓
Plot Data Points
↓
Fit Best Fit Line
↓
Learn Slope and Intercept
↓
Make Predictions
