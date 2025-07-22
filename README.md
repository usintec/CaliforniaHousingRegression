# 🏠 Predicting California Housing Prices Using Linear Regression

This project introduces linear regression using the **California Housing dataset**, with the goal of understanding how various factors (like income, location, population, etc.) influence housing prices in California. The notebook performs data exploration, model training, and evaluation using simple linear regression techniques.

---

## 📌 Objectives

- Understand the foundational principles of **linear regression**
- Perform **exploratory data analysis (EDA)** on California housing data
- Build and evaluate a **linear regression model** to predict median house values
- Visualize relationships between variables and model performance

---

## 📁 Project Structure


---

## 📊 Dataset Description

The dataset used is the **California Housing dataset**, originally derived from the 1990 U.S. Census and made available via `sklearn.datasets`. It includes the following features:

| Feature                | Description                                        |
|------------------------|----------------------------------------------------|
| `MedInc`              | Median income in block group                       |
| `HouseAge`            | Median house age in block group                    |
| `AveRooms`            | Average number of rooms per household              |
| `AveBedrms`           | Average number of bedrooms per household           |
| `Population`          | Block group population                             |
| `AveOccup`           | Average household occupancy                         |
| `Latitude`            | Block group latitude                               |
| `Longitude`           | Block group longitude                              |
| `MedHouseVal`         | **Target**: Median house value in $100,000s        |

---

## 🔍 What’s Inside the Notebook?

1. **Loading the dataset**
   - Using `sklearn.datasets.fetch_california_housing()`
2. **Exploratory Data Analysis**
   - Summary statistics
   - Pairwise correlations
   - Visualizations using `matplotlib` and `seaborn`
3. **Linear Regression Modeling**
   - Train-test split using `train_test_split`
   - Model training with `LinearRegression()`
   - Coefficients and intercept interpretation
4. **Model Evaluation**
   - R-squared, MAE, RMSE
   - Prediction vs actual comparison
   - Residual analysis
5. **Visualizations**
   - Scatter plots
   - Regression line plots
   - Residual distributions

---

## 📈 Key Findings

- **Income (`MedInc`) is the strongest predictor** of housing prices.
- Model performance (R²) is decent for an introductory linear model but can be improved with:
  - Polynomial features
  - Feature engineering
  - Regularization methods

---

## ⚙️ Requirements

Install dependencies from `requirements.txt`:

```bash
pip install -r requirements.txt
or install individually
pip install pandas numpy matplotlib seaborn scikit-learn

▶️ How to Run
Clone the repo or upload housing.ipynb to Google Colab.

Run each cell sequentially.

(Optional) Export plots or metrics if you wish to build a report or dashboard.

🧠 Concepts Covered
Linear regression theory and application

Feature-target relationships

Model fitting and evaluation

Visual data storytelling

📌 Future Enhancements
Multiple regression with all predictors

Ridge/Lasso regression

Feature scaling and transformation

Hyperparameter tuning with GridSearchCV

🧑‍💻 Author
Yusuf Olatayo Kareem
MSc Sociology | Data & ML Enthusiast | Computational Social Researcher
📍 GitHub • LinkedIn

📚 References
Scikit-learn: https://scikit-learn.org

California Housing Dataset: sklearn.datasets.fetch_california_housing
