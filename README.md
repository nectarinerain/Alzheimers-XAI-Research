###Explainable AI for Alzheimer’s Disease Prediction

#####This project applies explainable machine learning methods to evaluate fairness in Alzheimer's disease prediction models using the NACC UDS dataset. The work focuses on understanding how model behavior varies across demographic groups and how local explanations (via SHAP and LIME) reflect potential bias.

🧠 Project Goal

To investigate how different machine learning models behave across sex, race, and ethnicity groups, and use explainability tools to:

Interpret model decisions

Detect discrepancies across subpopulations

Support algorithmic fairness analysis

✅ Models Used

Artificial Neural Network (ANN)

k-Nearest Neighbors (KNN)

Performance evaluated using:

Accuracy

F1 score

False Positive Rate (FPR)

True Positive Rate (TPR)

Equalized Odds

Equal Opportunity Difference

🔍 Explainability Methods
✅ SHAP (SHapley Additive Explanations)

Used to analyze feature contributions globally and by subgroup.

✅ LIME (Local Interpretable Model-Agnostic Explanations)

Used to generate local explanations for individual predictions and compare interpretability across demographic slices.

📊 Fairness Analysis

The project examines:

Performance gaps across demographic groups

Distribution of feature importance in SHAP/LIME

Group-based disparities using fairness metrics

Demographic groups evaluated:

Sex (Male/Female)

Race

Ethnicity (Hispanic/Non-Hispanic)
