# 🎓 Student Performance — Exploratory Data Analysis (EDA)

This project explores the **UCI Student Performance** datasets (`student-mat` for Math ).  
Goal: understand patterns affecting student grades and identify features that may be useful for modeling **final grade `G3`**.

---

## 📦 Dataset
- **Source:** UCI Machine Learning Repository — Student Performance
- **Files used:** `student-mat.csv` (semicolon-separated)
- **Rows/Cols:** ~395 × 33 (Math)
- **Target:** `G3` (final grade, 0–20)

> Note: Data contains demographics, family, study habits, school support, absences, and prior grades (`G1`, `G2`).

---
## 🔍 Summary of Analysis

- Loaded semicolon-separated data correctly (sep=';', quotechar='"')

- Split features into categorical vs numeric/ordinal

- Ran univariate analysis (distributions, boxplots, countplots)

- Ran bivariate analysis:

- Correlation heatmap (G1/G2 strongly correlate with G3)

- Numeric vs G3 (scatter/boxplots)

- Categorical vs G3 (boxplots)

- Wrote clear insights: past performance dominates; most other features show weak standalone signal

## 📁 Files included:

- student_performance_eda.ipynb: Full Jupyter notebook with visuals and code

- student_performance_eda_notebook.pdf: PDF export for easy sharing/presentation
