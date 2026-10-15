# 🏦 Task 3 — Customer Churn Prediction

<p align="center">
  <strong>DevelopersHub Corporation · Data Science & Analytics Internship</strong><br>
  <em>Customer Analytics | Binary Classification | Feature Analysis</em>
</p>

---

## 📌 Project Overview

Customer churn occurs when a customer stops using a company's service. This project explores bank-customer data and builds classification models to predict whether a customer is likely to leave the bank.

The notebook uses `Exited` as the target variable, compares Logistic Regression with Random Forest, and explores which features are associated with churn predictions.

## 🎯 Objectives

- Load and inspect the customer churn dataset.
- Explore churn patterns across customer characteristics.
- Prepare categorical and numerical features for modelling.
- Train and evaluate classification models.
- Review a confusion matrix and classification report.
- Examine model coefficients and Random Forest feature importances.

## 🗂️ Dataset

**Dataset:** Churn Modelling  
**Required file:** `Churn_Modelling.csv`

The dataset includes customer and account attributes. The notebook uses features such as gender, age, and balance for exploratory analysis and uses `Exited` as the prediction target.

| Field | Meaning in the notebook |
|---|---|
| `Exited` | Target label: `0` = stayed, `1` = exited |
| `Gender` | Customer gender category, used in a churn comparison plot |
| `Age` | Customer age, explored against churn status |
| `Balance` | Account balance, compared across churn classes |

The notebook also encodes categorical columns and excludes irrelevant identifier-type columns where specified in its preparation steps.

## 🔍 Workflow

1. Load `Churn_Modelling.csv` and inspect the target distribution.
2. Explore churn by gender.
3. Compare age distributions for customers who stayed and exited.
4. Compare account balance across churn groups.
5. Encode categorical features and prepare `X` and `y`.
6. Split the dataset into training and test sets.
7. Train a Logistic Regression classifier.
8. Evaluate performance using accuracy, a classification report, and a confusion matrix.
9. Train a Random Forest classifier and compare its accuracy with Logistic Regression.
10. Visualize Logistic Regression coefficients and Random Forest feature importances.

## 📊 Model Evaluation

The notebook provides:

- **Accuracy comparison:** Logistic Regression versus Random Forest.
- **Confusion matrix:** Displays correct and incorrect predictions for stayed/exited customers.
- **Classification report:** Precision, recall, F1-score, and support.
- **Feature analysis:** Logistic Regression coefficients and Random Forest feature-importance rankings.

Check the executed notebook for actual metric values and plots. Performance numbers are not hard-coded in this README.

## 🧰 Tools & Libraries

- Python
- Jupyter Notebook
- Pandas and NumPy
- Matplotlib and Seaborn
- Scikit-learn

## ▶️ How to Run

1. Put `task_3.ipynb` and `Churn_Modelling.csv` in the same folder.
2. Install dependencies:

   ```bash
   python -m pip install pandas numpy matplotlib seaborn scikit-learn jupyter
   ```

3. Open `task_3.ipynb` in VS Code or Jupyter Notebook.
4. Confirm that `Churn_Modelling.csv` is in the expected location.
5. Run all cells in order.

## 💡 Business Relevance

Churn predictions can help a bank investigate customer groups that may need additional attention. Feature-importance results indicate patterns learned by the model; they do **not** prove that a feature causes a customer to leave. Any real-world use should include model validation, privacy safeguards, and fairness review.

## 📁 Suggested Repository Structure

```text
Task_3_Customer_Churn/
├── README.md
├── task_3.ipynb
└── Churn_Modelling.csv
```

If you do not want to publish the dataset itself, provide a source link and clear download instructions instead.

## 👩‍💻 Skills Demonstrated

`Python` · `EDA` · `Data Preparation` · `One-Hot Encoding` · `Logistic Regression` · `Random Forest` · `Confusion Matrix` · `Feature Importance`

---

*Prepared as part of the DevelopersHub Corporation Data Science & Analytics Internship.*
