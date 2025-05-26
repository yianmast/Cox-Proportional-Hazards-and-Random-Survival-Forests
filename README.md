# Cox Proportional Hazards and Random Survival Forests

This project was completed as part of the "AI for Medical Prognosis" course on Coursera. It focuses on two advanced modeling techniques used in survival analysis: the Cox Proportional Hazards model and Random Survival Forests.

We work with a dataset of patients suffering from Primary Biliary Cirrhosis (PBC), a progressive liver disease. The goal is to predict survival outcomes and understand how different patient features influence risk.

## 📘 Project Overview

This notebook walks through building both linear and non-linear survival models to estimate patient risk over time.

### Topics Covered

- Data preprocessing for survival models
- Cox Proportional Hazards model implementation and interpretation
- One-hot encoding for categorical variables
- Hazard ratio calculation between individuals
- Harrell’s C-index to evaluate model performance
- Random Survival Forest modeling with R (`rpy2`)
- Permutation-based feature importance (VIMP)

## 📊 Key Insights

- Treatment was shown to reduce risk, with a hazard ratio < 1
- The Cox model achieved high C-index scores (~0.85)
- Random Survival Forest slightly outperformed the Cox model in validation and test sets
- `edema` was consistently the most important variable across both models, while `bili` was only significant in the Random Survival Forest

---

📚 Part of the [AI for Medical Prognosis](https://www.coursera.org/learn/ai-for-medical-prognosis) specialization by DeepLearning.AI.
