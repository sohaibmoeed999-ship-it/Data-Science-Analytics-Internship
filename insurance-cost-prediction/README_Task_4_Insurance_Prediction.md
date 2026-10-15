# 🩺 Task 4 — Predicting Insurance Claim Amounts

<p align="center">
  <strong>DevelopersHub Corporation · Data Science & Analytics Internship</strong><br>
  <em>Regression | Exploratory Data Analysis | Model Evaluation</em>
</p>

---

## 📌 Project Overview

This project builds a **Linear Regression model** to estimate medical insurance charges from personal and lifestyle-related features. The analysis focuses on how age, Body Mass Index (BMI), and smoking status relate to insurance charges.

The notebook follows a full introductory machine-learning workflow: data inspection, cleaning, visualization, categorical encoding, model training, and evaluation.

## 🎯 Objectives

- Explore and clean the Medical Cost Personal Dataset.
- Review missing values and duplicate rows.
- Visualize relationships between age, BMI, smoking status, and charges.
- Encode categorical features for regression.
- Train a Linear Regression model using a train-test split.
- Evaluate predictions using MAE, RMSE, and R-squared.
- Inspect predicted-versus-actual values and residuals.

## 🗂️ Dataset

**Dataset:** Medical Cost Personal Dataset  
**Required file:** `insurance.csv`  
**Source:** [Kaggle — Medical Cost Personal Dataset](https://www.kaggle.com/datasets/mirichoi0218/insurance)

The target variable is `charges`, representing the medical insurance charges recorded in the dataset.

| Feature | Description |
|---|---|
| `age` | Customer age |
| `sex` | Recorded sex category |
| `bmi` | Body Mass Index |
| `children` | Number of children/dependents recorded |
| `smoker` | Smoking-status category |
| `region` | Residential region category |
| `charges` | Insurance charges to predict |

## 🔍 Workflow & Visualizations

1. Load the CSV and inspect its dimensions and columns.
2. Review descriptive statistics, missing values, and duplicate rows.
3. Remove duplicate rows and handle missing values.
4. Create an **age vs. charges** scatter plot.
5. Create a **BMI vs. charges** scatter plot.
6. Use a **smoking status vs. charges** box plot.
7. Encode categorical features using one-hot encoding.
8. Separate predictors from the `charges` target.
9. Split the dataset into training and testing sets.
10. Train a Linear Regression model.
11. Compare actual and predicted charges.
12. Evaluate MAE, RMSE, and R-squared.
13. Plot predictions against actual values, inspect residuals, and review model coefficients.

## 📊 Evaluation Metrics

| Metric | What it tells us |
|---|---|
| **MAE** — Mean Absolute Error | Average absolute difference between actual and predicted charges, in the target's units |
| **RMSE** — Root Mean Squared Error | Penalizes larger prediction errors more strongly; in the target's units |
| **R²** — R-squared | Indicates how much target variation is explained by the fitted model on the evaluated data |

Use the actual values printed by your executed notebook when reporting results. No performance scores are fabricated in this README.

## 🧰 Tools & Libraries

- Python
- Jupyter Notebook
- Pandas and NumPy
- Matplotlib and Seaborn
- Scikit-learn

## ▶️ How to Run

1. Download `insurance.csv` from the dataset source.
2. Place `insurance.csv` in the same folder as `Task4_Insurance_Prediction.ipynb`.
3. Install dependencies:

   ```bash
   python -m pip install pandas numpy matplotlib seaborn scikit-learn jupyter
   ```

4. Open the notebook in VS Code or Jupyter Notebook.
5. Run all cells from top to bottom.

## 💡 Interpretation & Limitations

The visualizations help explore associations between customer characteristics and charges, while the regression metrics quantify prediction error. Associations in this dataset do not establish causation. This is an educational project and should not be used on its own to determine real insurance pricing or individual eligibility.

## 📁 Suggested Repository Structure

```text
Task_4_Insurance_Prediction/
├── README.md
├── Task4_Insurance_Prediction.ipynb
└── insurance.csv
```

If you prefer not to publish the dataset file, link to the source and explain how to download it.

## 👩‍💻 Skills Demonstrated

`Python` · `Data Cleaning` · `EDA` · `Data Visualization` · `One-Hot Encoding` · `Linear Regression` · `MAE` · `RMSE` · `R²`

---

*Prepared as part of the DevelopersHub Corporation Data Science & Analytics Internship.*
