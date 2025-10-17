Explainable AI for Alzheimer’s Disease Prediction

This project applies explainable machine learning methods to evaluate fairness in Alzheimer's disease prediction models using the NACC UDS dataset. The work focuses on understanding how model behavior varies across demographic groups and how local explanations reflect potential bias.

🧠 Project Goal

Investigate how predictive models behave across sex, race, and ethnicity groups, and use explainability tools to:

Interpret model decisions

Detect discrepancies across subpopulations

Support algorithmic fairness analysis

✅ Models Used

Artificial Neural Network (ANN)

k-Nearest Neighbors (KNN)

Evaluation metrics:

Accuracy

F1 Score

False Positive Rate (FPR)

True Positive Rate (TPR)

Equalized Odds

Equal Opportunity Difference

🔍 Explainability Methods
SHAP (SHapley Additive Explanations)

Used to analyze feature contributions globally and within each demographic subgroup.

LIME (Local Interpretable Model-Agnostic Explanations)

Used to generate local explanations for individual predictions and compare interpretability across slices.

📊 Fairness Analysis

The project examines:

Performance gaps across demographic groups

Distribution of feature importance using SHAP and LIME

Disparities in fairness metrics

Demographic attributes analyzed:

Sex

Race

Ethnicity

🧾 Tools & Libraries

Python

pandas, numpy

scikit-learn

SHAP

LIME

matplotlib (optional for visualizations)

🚀 Future Directions

Add confidence measures to explanation outputs

Expand to additional model types

Incorporate causal or counterfactual fairness analysis

Explore intersectional subgroup comparisons
