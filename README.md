# Simple Linear Regression Using Scikit-learn

## 📌 Project Overview

This project demonstrates how to implement **Simple Linear Regression using Scikit-learn** to predict salary based on years of experience.

The project covers the complete machine learning workflow, including data preparation, model training, coefficient interpretation, prediction, model evaluation, and visualization.

## 🎯 Objectives

- Understand Simple Linear Regression.
- Train a regression model using Scikit-learn.
- Extract the slope and intercept.
- Predict salary for a new input.
- Evaluate model performance using the R² score.
- Visualize actual observations and the regression line.

## 🛠️ Technologies Used

- Python
- NumPy
- Matplotlib
- Scikit-learn

## 📊 Dataset

This project uses a small sample dataset created for learning purposes.

| Years of Experience | Salary (units) |
|---:|---:|
| 1 | 30 |
| 2 | 35 |
| 3 | 40 |
| 4 | 45 |
| 5 | 50 |
| 6 | 55 |
| 7 | 60 |
| 8 | 65 |

**Features:**
- Independent variable (X): Years of Experience
- Dependent variable (y): Salary

**Note:** The salary values are illustrative and do not represent actual salary data.

## 🧮 Mathematical Concept

Simple Linear Regression models the relationship between one independent variable and a continuous dependent variable.

The equation is:

\[
\hat{y} = b_0 + b_1x
\]

Where:

- \(\hat{y}\) = Predicted salary
- \(b_0\) = Intercept
- \(b_1\) = Slope or regression coefficient
- \(x\) = Years of experience

### Model Equation

For this dataset, the fitted equation is:

\[
\text{Salary} = 25 + 5 \times \text{Experience}
\]

### Interpretation

- **Slope = 5:** The predicted salary increases by 5 units for every additional year of experience.
- **Intercept = 25:** The model estimates a salary of 25 units at zero years of experience.

## ⚙️ Project Workflow

1. Import the required libraries.
2. Create the dataset using NumPy.
3. Reshape the input feature into a two-dimensional array.
4. Create a `LinearRegression` model.
5. Train the model using `model.fit()`.
6. Extract the slope and intercept.
7. Generate predictions using `model.predict()`.
8. Predict salary for 10 years of experience.
9. Evaluate model performance using the R² score.
10. Visualize the actual data and regression line using Matplotlib.

## 📈 Model Evaluation

The model is evaluated using the **R² score (coefficient of determination)**.

\[
R^2 = 1 - \frac{SSE}{SST}
\]

Where:

- SSE = Sum of Squared Errors
- SST = Total Sum of Squares

### Result

| Metric | Value |
|---|---:|
| Slope | 5 |
| Intercept | 25 |
| R² Score | 1.00 |
| Predicted Salary for 10 Years | 75 |

**Interpretation:** The R² score of 1.00 indicates that the model perfectly fits this sample dataset.

This result occurs because the sample data follows an exact linear relationship. Real-world salary data is generally more variable.

## 📉 Visualization

The project uses a scatter plot and a regression line to visualize the model.

- **Scatter plot:** Represents the actual salary observations.
- **Regression line:** Represents the salary values predicted by the model.
- **Prediction marker:** Highlights the predicted salary for 10 years of experience.

The visualization helps demonstrate how Simple Linear Regression learns a linear relationship between experience and salary.

## ▶️ How to Run the Project

### Prerequisites

Install Python on your system.

### Step 1: Clone the Repository

```bash
git clone https://github.com/Ethan2417/YOUR-REPOSITORY-NAME.git
```

Replace `YOUR-REPOSITORY-NAME` with your actual GitHub repository name.

### Step 2: Navigate to the Project Folder

```bash
cd YOUR-REPOSITORY-NAME
```

### Step 3: Install Dependencies

```bash
pip install numpy matplotlib scikit-learn
```

### Step 4: Run the Python Script

```bash
python simple_linear_regression.py
```

Replace `simple_linear_regression.py` with your actual Python filename if it differs.

## 📚 Key Learnings

Through this project, I practiced:

- Preparing data for Scikit-learn.
- Understanding feature shapes using NumPy.
- Training a Simple Linear Regression model.
- Extracting coefficients and intercepts.
- Predicting new values with `model.predict()`.
- Evaluating regression performance using R².
- Visualizing the regression line with Matplotlib.
- Interpreting the relationship between an independent variable and a continuous target.

## ⚠️ Limitations

- The dataset contains only eight observations.
- The data is artificially created for learning purposes.
- The R² score is calculated on the same dataset used to train the model.
- The perfect R² score does not demonstrate how well the model generalizes to unseen data.
- Salary depends on many factors beyond years of experience.

For a more realistic evaluation, a larger dataset and a train/test split should be used.

## 🚀 Future Improvements

- Use a real-world salary dataset.
- Split the dataset into training and testing sets.
- Evaluate the model on unseen data.
- Calculate MAE, MSE, and RMSE.
- Compare the results with a manually implemented OLS model.
- Extend the project to Multiple Linear Regression.

## 👨‍💻 Author

**Prasanjit Lal**

GitHub: [Ethan2417](https://github.com/Ethan2417)

---
