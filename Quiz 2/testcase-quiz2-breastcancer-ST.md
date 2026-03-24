TC-identifier: Sakthi Thanigai

Testcase name: Quiz 2 Breast Cancer Explainability

Objective:
Evaluate classification and explainability on the Breast Cancer dataset using a whitebox and blackbox model with LIME and SHAP.

Dataset:
Breast Cancer dataset

Task:
Binary classification to predict cancer class.

Models:
- Logistic Regression
- Random Forest

Explanation methods:
- LIME
- SHAP

Input:
Breast Cancer dataset features after train/test split.

Expected behavior:
- Logistic Regression should produce a strong classification baseline.
- Random Forest should also produce strong predictive performance.
- LIME should provide local explanations for individual predictions.
- SHAP should provide feature importance information for global interpretation.

Evaluation criteria:
- Model accuracy
- Classification report
- Interpretability of important features
- Agreement or differences between LIME and SHAP explanations

Notes:
The notebook compares model performance and feature importance patterns across both explainability methods.
