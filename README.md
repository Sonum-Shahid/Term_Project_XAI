Channel Occupancy Prediction

1. Project Overview
This project focuses on channel occupancy prediction using Machine Learning and Deep Learning models with Explainable AI (XAI) techniques.

2. Models Implemented
- Random Forest (RF): For baseline comparison
- XGBoost: Gradient boosting for improved accuracy
- LSTM with Attention: Deep learning for temporal patterns

3. Explainability Methods
- SHAP (Shapley Additive exPlanations): Feature importance and contribution analysis
- LIME (Local Interpretable Model-agnostic Explanations): Local explanations for individual predictions

4. Repository Structure

```
Term_Project_XAI/
│
├── README.md
├── Requirements.txt
├── waca_dataset.csv
├── presentation.pdf
│
├── onecode/
│   ├── 1.Data prep.ipynb
│   ├── 2.Models.ipynb
│   ├── 3.explainability.ipynb
│   └── 4.LSTM.ipynb
│
└── outputs/
    ├── shap_rf_summary.png
    ├── shap_xgb_summary.png
    ├── all_models_comparison.png
    ├── bias_analysis.png
    ├── busy_idle_final.png
    ├── confidence_intervals.png
    ├── cross_validation.png
    ├── lime_rf_busy.png
    ├── lime_rf_idle.png
    ├── lime_xgb_busy.png
    ├── lime_xgb_idle.png
    ├── lstm_attention_heatmap.png
    ├── lstm_training.png
    ├── model_comparison.png
    ├── rf_throughput.png
    └── rssi_distribution.png
```
