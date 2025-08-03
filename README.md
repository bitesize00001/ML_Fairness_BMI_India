#  Machine Learning Fairness in Predicting Underweight, Overweight and Adiposity Across Socioeconomic and Caste Groups in India

This project investigates how fairly machine learning (ML) models can predict underweight, overweight/obesity, and central adiposity among older adults in India—specifically across caste and socioeconomic subgroups—using data from the Longitudinal Ageing Study in India (LASI). It was conducted as part of the study published in **[Journal Title or preprint server, 2025]**.

---

##  Objective

To evaluate and improve the fairness of ML models in public health prediction by:

- Assessing model performance on BMI-related outcomes
- Identifying bias across caste and socioeconomic groups
- Applying and comparing bias mitigation strategies (pre-, in-, post-processing)


## How to Run

1. Clone the repo:
   ```bash
   git clone https://github.com/yourusername/BMI_Fairness_India.git
   cd BMI_Fairness_India
Install requirements:

bash
Copy
Edit
pip install -r requirements.txt
Run notebooks in order (1 → 5.4) for full pipeline.

## Methodology Breakdown
Notebook	Description
1_model_evaluation_bootstrap	Train & evaluate classifiers using bootstrapped AUROC, accuracy, etc.
2_prediction_density_analysis	Compare prediction distributions across caste/MPCE groups.
3_additional_features_analysis	Assess effect of socioeconomic & health features on model performance.
4_feature_importance_shap	Use SHAP to explain feature contribution to predictions.
5_1_fairness_baseline_subgroups	Stratify performance by subgroup to establish baseline unfairness.
5_2_bias_preprocessing	Apply pre-processing bias mitigation (reweighting, impact removal).
5_3_bias_inprocessing	Apply in-processing methods (adversarial, exponentiated gradient).
5_4_bias_postprocessing	Post-processing fairness techniques (equalized odds, ROC).

## Outputs
📈 Figures: ROC curves, SHAP plots, subgroup fairness charts (Fig 1–4)

📋 Tables: Performance metrics, fairness scores (Supplementary Tables)

## Keywords
Machine Learning · Fairness · Health Equity · Public Health · India · AIF360 · Bias Mitigation · LASI Dataset · Adiposity · BMI · SHAP

## Citation
John Tayu Lee al. (2025). Machine Learning Fairness in Predicting Underweight, Overweight and Adiposity Across Socioeconomic and Caste Group in India. [Journal/medRxiv].
