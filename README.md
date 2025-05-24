# heart-disease-logistic-model
Analyzing heart disease risk using statistical tests and logistic regression in R. Includes data visualization, correlation analysis, and ROC evaluation.
# Heart Disease Risk Analysis Using Logistic Regression

This project explores the relationship between physiological and demographic factors and the risk of heart disease. It uses statistical methods and logistic regression modeling in R to analyze clinical indicators such as age, cholesterol, sex, and resting blood pressure.

---

## 📊 Overview

The analysis is based on the [Heart Disease UCI dataset](https://www.kaggle.com/datasets/fedesoriano/heart-failure-prediction), cleaned and transformed to suit research questions focused on predicting heart disease.

Key methods:
- Spearman correlation
- Chi-square test
- Mann-Whitney U test
- Logistic regression modeling
- ROC curve & AUC evaluation

---

## 🔧 Tools & Technologies

- **R** & **RMarkdown**
- **ggplot2**, **Hmisc**, **pROC**, **car**
- Statistical methods and visualizations

---

## 📁 Files Included

- `heart_disease_analysis.Rmd`: Full analysis and code in R Markdown
- `Final-Project.pdf`: Rendered report including visualizations and interpretations
- `README.md`: Project overview and instructions

---

## ▶️ How to Use

1. Open the `.Rmd` file in RStudio
2. Knit the file to PDF or HTML (requires necessary R packages)
3. Explore the detailed report in the provided PDF

---

## 🎯 Key Findings

- **Age** and **sex** (male) are strong predictors of heart disease.
- **Cholesterol** and **resting blood pressure** also show positive associations.
- The final logistic regression model achieved an AUC of **0.76**, indicating strong predictive power.
- Statistical tests (Mann-Whitney, Chi-square) confirm significance of relationships.

---

## 📌 Note

This is a completed academic project. All analysis, outputs, and visualizations are embedded in the `.pdf` report and `.Rmd` file. No rerunning is necessary.

---

## 👨‍⚕️ Clinical Implications

This model could be useful in clinical decision-making for early identification of individuals at higher risk of heart disease. Further validation and expanded datasets are recommended for real-world applications.

---

## 🧑‍💻 Author

Group 4 – Final Project (2024)  
Data Science Course  
Indiana University–Purdue University, Indianapolis
