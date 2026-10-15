# 🌸 Task 1 — Exploring & Visualizing the Iris Dataset

<p align="center">
  <strong>DevelopersHub Corporation · Data Science & Analytics Internship</strong><br>
  <em>Exploratory Data Analysis | Data Visualization | Python</em>
</p>

---

## 📌 Project Overview

This project explores the classic **Iris flower dataset** to understand how data can be inspected, summarized, and communicated through visualizations. The notebook examines flower measurements and compares patterns across the three Iris species.

The focus is on building a clear, reproducible exploratory data analysis (EDA) workflow—not on training a predictive machine-learning model.

## 🎯 Objectives

- Load and inspect the dataset using Pandas.
- Review dataset dimensions, columns, descriptive statistics, missing values, and duplicate records.
- Explore relationships between sepal and petal measurements.
- Visualize distributions and compare measurements across species.
- Use a correlation heatmap to inspect relationships between numerical features.

## 🗂️ Dataset

**Dataset:** Iris  
**Source:** Scikit-learn's built-in Iris dataset.

The dataset contains measurements of iris flowers, including:

| Feature | Description |
|---|---|
| `sepal length (cm)` | Sepal length in centimetres |
| `sepal width (cm)` | Sepal width in centimetres |
| `petal length (cm)` | Petal length in centimetres |
| `petal width (cm)` | Petal width in centimetres |
| `species` | Iris species label |

The notebook creates a Pandas DataFrame from the dataset and maps the target labels to species names.

## 🔍 Analysis & Visualizations

The notebook includes:

- **Scatter plot:** Sepal length versus petal length, coloured by species.
- **Histogram:** Distribution of petal length.
- **Box plot:** Petal length comparison across species; useful for reviewing spread and potential outliers.
- **Correlation heatmap:** Relationships among numerical flower measurements.
- **Data inspection:** Dataset shape, columns, summary statistics, missing values, duplicates, and species counts.

## 🧰 Tools & Libraries

- Python
- Jupyter Notebook
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn (built-in Iris dataset)

## ▶️ How to Run

1. Clone or download this repository.
2. Open `Task_1_Iris.ipynb` in VS Code or Jupyter Notebook.
3. Ensure the required libraries are installed:

   ```bash
   python -m pip install pandas matplotlib seaborn scikit-learn jupyter
   ```

4. Run the notebook cells from top to bottom.

> **Note:** This notebook uses Scikit-learn's built-in Iris dataset, so a separate CSV file is not required.

## 📈 Key Takeaway

EDA helps turn raw measurements into understandable patterns. The plots in this project make it easier to compare species, inspect distributions, and see relationships among flower measurements. Refer to the notebook's executed outputs for the actual visual findings.

## 📁 Suggested Repository Structure

```text
Task_1_Iris/
├── README.md
└── Task_1_Iris.ipynb
```

## 👩‍💻 Skills Demonstrated

`Python` · `Pandas` · `EDA` · `Data Cleaning` · `Matplotlib` · `Seaborn` · `Data Visualization`

---

*Prepared as part of the DevelopersHub Corporation Data Science & Analytics Internship.*
