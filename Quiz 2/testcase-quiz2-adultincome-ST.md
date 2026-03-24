TC-identifier: Sakthi Thanigai

Testcase name: Quiz 2 Adult Income Explainability

Objective:
Evaluate classification and explainability on the Adult Income dataset using a whitebox and blackbox model with LIME and SHAP.

Dataset:
Adult Income dataset

Task:
Binary classification to predict whether income is above or below 50K.

Models:
- Logistic Regression
- Random Forest

Explanation methods:
- LIME
- SHAP

Input:
Adult Income dataset after preprocessing and one-hot encoding.

Expected behavior:
- Logistic Regression should provide an interpretable whitebox baseline.
- Random Forest should provide a strong blackbox comparison.
- LIME should explain individual predictions.
- SHAP should highlight globally important features such as age, education, and hours worked per week.

Evaluation criteria:
- Model accuracy
- Classification report
- Quality of local and global explanations
- Comparison between whitebox and blackbox interpretability

Notes:
The Adult Income dataset required preprocessing and one-hot encoding before training the models.
