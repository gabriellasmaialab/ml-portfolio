# 📈 Linear Regression: Predicting California Housing Prices

This project applies a **simple linear regression model** to predict housing prices in California using median income as the main predictor. The dataset comes from the *Hands-On Machine Learning* book by Aurélien Géron.

---

## 📊 Dataset

- **Source**: [California Housing Dataset](https://github.com/ageron/handson-ml/tree/master/datasets/housing)
- **Format**: CSV
- **Target**: `median_house_value`
- **Feature used**: `median_income` (for univariate regression)

---

## 🔎 Project Structure

| Step | Description |
|------|-------------|
| 1. 📚 Import Libraries | Load required packages like `pandas`, `numpy`, `scikit-learn`, and `matplotlib` |
| 2. 📥 Load Dataset | Read CSV file directly from GitHub or local path |
| 3. 🔍 Exploratory Data Analysis (EDA) | Summary stats, missing values, correlation heatmap, distributions |
| 4. 🎯 Feature Selection | Chose the feature `median_income` for univariate regression |
| 5. 🤖 Model Training | Used `LinearRegression` from `sklearn` with train/test split |
| 6. 📈 Prediction & Evaluation | Used R² Score and MSE, plotted predictions vs true values |

---

## 📈 Example Output

```text
Intercept: 44635.79
Coefficient: 134134.54

Mean Squared Error (MSE): 5.18e+09
R² Score: 0.47
