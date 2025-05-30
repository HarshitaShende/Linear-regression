# Task-3---Linear-regression
Linear Regression

# 📊 Task 3: Simple and Multiple Linear Regression

## 🎯 Objective
The objective of this task is to **implement and understand** both simple and multiple linear regression models using the `scikit-learn` library. The task includes data preprocessing, model training, evaluation, and interpretation of results.


- **Description:** The dataset contains numerical and categorical features, including a target variable to be predicted using regression models.

---

## 🛠️ Steps Performed

### 1. 📥 Data Import and Preprocessing
- Loaded the dataset using `pandas`.
- Dropped rows with missing values to simplify the initial modeling.
- Selected appropriate **feature(s)** and **target** for regression.
  - For simple regression: used one feature (e.g., `feature1`)
  - For multiple regression: used more than one feature (e.g., `feature1`, `feature2`)

### 2. ✂️ Train-Test Split
- Used `train_test_split()` to divide the data into training and testing sets with an 80/20 ratio.
- Ensured reproducibility with `random_state=42`.

### 3. 🤖 Model Fitting
- Used `LinearRegression()` from `sklearn.linear_model` to fit:
  - A **Simple Linear Regression** model
  - A **Multiple Linear Regression** model
- Trained models on training data using `.fit()`

### 4. 📈 Model Evaluation
- Evaluated model predictions using:
  - **MAE** (Mean Absolute Error)
  - **MSE** (Mean Squared Error)
  - **R² Score** (Coefficient of Determination)
- Compared model performance between simple and multiple regression.

### 5. 📉 Visualization & Interpretation
- **Plotted the regression line** for the simple linear regression model.
- **Interpreted model coefficients** to understand the influence of each feature on the target variable.

---

## 📌 Key Learnings
- Simple Linear Regression models relationships between one feature and the target.
- Multiple Linear Regression can improve prediction performance by using more features.
- R² Score helps understand how well the model explains variance in the data.
- MAE and MSE help quantify prediction error.
- Coefficients explain how each input feature impacts the output prediction.



