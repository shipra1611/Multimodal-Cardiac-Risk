# Multimodal Cardiac Risk Prediction

Multimodal machine learning pipeline combining ECG-derived HRV biomarkers with structured clinical data for cardiac disease prediction.

## Overview
This project integrates ECG signal processing with clinical features to improve cardiac risk prediction using Random Forest fusion and SHAP explainability.

## Pipeline
- ECG preprocessing and HRV extraction (NeuroKit)
- Clinical modeling (UCI Cleveland Heart Disease)
- Feature-level multimodal fusion
- SHAP explainability

## Results

| Model | ROC-AUC |
|------|--------|
| Clinical Only | 0.89 |
| ECG Only | ~0.75 |
| Multimodal Fusion | **1.00** |

> Results obtained on limited aligned samples.

## Tech Stack
Python, NeuroKit2, Scikit-learn, SHAP, Google Colab
