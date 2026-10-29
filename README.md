# Emergency Department Analytics

### Statistical Analysis and Predictive Modeling Using Python

## Project Overview

This project explores emergency department patient data through statistical hypothesis testing, exploratory data analysis, and predictive modeling.

The objective is to investigate factors associated with emergency department length of stay and evaluate whether patient characteristics and operational measures can predict hospital admission.

## Analytical Methods

- Data exploration, validation, and visualization
- Welch's two-sample t-test
- One-way ANOVA
- Logistic regression
- Decision Tree and Random Forest classifiers
- Model evaluation using accuracy, sensitivity, specificity, and ROC-AUC
- Feature importance and classification threshold analysis

## Key Findings

- Admitted patients had a longer average ED stay, but the observed difference was not statistically significant at the 5% level (p = 0.054).
- Average ED length of stay did not differ significantly across triage severity levels (ANOVA p = 0.886).
- Random Forest achieved the highest test ROC-AUC (0.645), although overall predictive performance was limited.
- Classification threshold analysis demonstrated the trade-off between sensitivity and specificity.

## Tools

Python, pandas, NumPy, SciPy, matplotlib, seaborn, scikit-learn, and Jupyter Notebook.

## Dataset and Limitations

This is an educational case study based on a practice dataset provided through a Coursera course. The dataset is not included in this repository.

The analysis uses 400 observations, with predictive models evaluated on a held-out test set of 80 observations. Findings are exploratory and are not intended for clinical decision-making.

## Project Notebook

Open [HealthcareCaseStudy.ipynb](HealthcareCaseStudy.ipynb) to review the Python code, statistical analyses, visualizations, and results.
