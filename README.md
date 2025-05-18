# 📊 Unveiling Employment and Socioeconomic Patterns – PLFS Analysis

This repository contains statistical analysis of **Periodic Labour Force Survey (PLFS)** unit-level data conducted using Python. The project aims to uncover trends and patterns in employment, education, and demographics across Indian states.

---

## 📁 Contents

| File | Description |
|------|-------------|
| `plfs.ipynb` | Python notebook with full data cleaning, EDA, trend analysis, modeling, and visualizations |
| `Report_Mospi.docx` | Formal report summarizing the full analysis, methodology, outcomes |
| `data/README.md` | Placeholder note for the confidential PLFS dataset (not included) |

---

## 🎯 Objectives

- Analyze employment status across education levels, age groups, and gender.
- Study literacy and demographic patterns using EDA and correlation analysis.
- Identify regional differences in workforce participation.
- Build a predictive model to understand drivers of employment type.

---

## 🧪 Methodology

1. **Data Cleaning**: Addressed missing values, format issues, duplicates.
2. **Integration**: Combined household and person-level records for holistic analysis.
3. **Exploratory Analysis**: Generated visual insights into gender distribution, employment types, education levels, and age groups.
4. **Correlation Analysis**: Measured relationships between literacy and employment.
5. **Trend Analysis**: Tracked state-wise self-employment across working-age groups.
6. **Modeling**:
   - **Problem Statement**: Predict whether an individual is in a **regular wage/salary** job based on education level and demographics.
   - **Model Used**: Logistic Regression (Binary Classification)
   - **Performance**: 75% accuracy (limited by class imbalance)

---

## 📈 Key Findings

- **Regular wage/salary jobs** are the most common (≈45%), followed by **self-employment** (≈32%).
- The **literacy rate** is ~90%; most common education levels are middle and secondary.
- Workforce participation peaks in the **15–59 years** age range.
- **Correlation analysis** shows moderate links between education levels and employment categories.
- The logistic regression model performed well on the majority class but struggled with imbalance, suggesting the need for further refinement.

---

## 🧰 Tools & Technologies

- **Python**: pandas, seaborn, matplotlib, scikit-learn
- **Excel**: for initial inspection and manual transformation
- **Tableau**: for interactive dashboards and trend visualizations
