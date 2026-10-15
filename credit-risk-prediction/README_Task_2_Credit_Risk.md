# 💳 Task 2 — Credit Risk Prediction

<p align="center">
  <strong>DevelopersHub Corporation · Data Science & Analytics Internship</strong><br>
  <em>Classification | Data Preparation | Model Evaluation</em>
</p>

---

## 📌 Project Overview

This project uses applicant information from a loan prediction dataset to build a **classification model for loan approval status**. It explores selected applicant characteristics, prepares numerical and categorical data, and evaluates a Logistic Regression model.

**Important distinction:** The notebook predicts the dataset's `Loan_Status` label (approval/rejection). This is a practical loan-outcome classification exercise; it does not directly model whether an approved borrower later defaults.

## 🎯 Objectives

- Inspect the loan prediction dataset and its data types.
- Review missing values and duplicate records.
- Explore applicant income, loan amount, education, and loan status.
- Prepare numerical and categorical features for modelling.
- Train a Logistic Regression classifier.
- Evaluate predictions with accuracy, a confusion matrix, and a classification report.

## 🗂️ Dataset

**Dataset:** Loan Prediction Dataset  
**Typical source:** Kaggle Loan Prediction dataset.

The notebook loads a CSV file named:

```text
train_u6lujuX_CVtuZ9i (1).csv
```

Make sure the CSV is in the same folder as the notebook, or update the path in the loading cell.

Key fields used in the notebook include:

| Feature | Purpose |
|---|---|
| `ApplicantIncome` | Applicant income exploration |
| `LoanAmount` | Loan amount distribution analysis |
| `Education` | Education category exploration |
| `Loan_Status` | Target label to classify |
| `Loan_ID` | Identifier excluded from model features |

Other available applicant attributes are prepared as part of the model pipeline.

## 🔍 Workflow

1. Load the CSV file and inspect its structure.
2. Explore the data and review missing/duplicate records.
3. Plot loan amount and applicant income distributions.
4. Compare education categories and loan status.
5. Exclude rows without a known target label.
6. Separate features from `Loan_Status` and exclude the identifier `Loan_ID`.
7. Split the data into training and testing sets.
8. Prepare numerical and categorical features and fit Logistic Regression.
9. Evaluate model predictions.

## 📊 Evaluation

The notebook reports:

- **Accuracy:** Overall proportion of correctly classified test examples.
- **Confusion matrix:** Counts of correct and incorrect classifications by class.
- **Classification report:** Precision, recall, F1-score, and support for each class.

Use the values produced by running the notebook as the project's actual results; this README intentionally does not invent scores.

## 🧰 Tools & Libraries

- Python
- Jupyter Notebook
- Pandas and NumPy
- Matplotlib and Seaborn
- Scikit-learn

## ▶️ How to Run

1. Place the notebook and dataset CSV in the same folder.
2. Install dependencies:

   ```bash
   python -m pip install pandas numpy matplotlib seaborn scikit-learn jupyter
   ```

3. Open `Task_2_Credit_Risk.ipynb` in VS Code or Jupyter Notebook.
4. Confirm the CSV filename in the `pd.read_csv(...)` cell matches your file.
5. Run the notebook cells from top to bottom.

## 💡 Business Relevance

A classification workflow can help organize applicant data and assess how well a model distinguishes recorded approval outcomes. Any real lending decision would require careful validation, fairness checks, suitable governance, and additional information beyond a classroom model.

## 📁 Suggested Repository Structure

```text
Task_2_Credit_Risk/
├── README.md
├── Task_2_Credit_Risk.ipynb
└── train_u6lujuX_CVtuZ9i (1).csv
```

If you prefer not to publish the dataset file, include its official download/source link and instructions instead.

## 👩‍💻 Skills Demonstrated

`Python` · `Pandas` · `Data Cleaning` · `EDA` · `Categorical Encoding` · `Logistic Regression` · `Classification Metrics`

---

*Prepared as part of the DevelopersHub Corporation Data Science & Analytics Internship.*
