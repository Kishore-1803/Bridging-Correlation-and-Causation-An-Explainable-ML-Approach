# Bridging-Correlation-and-Causation-An-Explainable-ML-Approach

## Overview

An machine learning project that predicts using both traditional and **causal-informed** modeling approaches. The project emphasizes **explainability** and **trust**, leveraging causal inference, SHAP analysis, and interactive visualizations to help users understand not just the predictions, but the reasons behind them.

---

## Features

- **Data Cleaning & Exploration:** Robust preprocessing and smart outlier removal on real insurance data.
- **Causal Inference:** Identifies and quantifies the true drivers of insurance charges (e.g., smoking, age, BMI) using DoWhy.
- **Causal-Informed Modeling:** Incorporates causal effects into Ridge and Gradient Boosting models for improved interpretability.
- **Explainability:** SHAP analysis and interactive dashboards for transparent, business-friendly insights.
- **What-If Analysis:** Simulate lifestyle changes and see their impact on insurance costs.
- **Deployment Ready:** Model can be served via FastAPI for real-world integration.

---
## Key Results

- **Top Causal Driver:** Smoking increases insurance costs by ~$23,800, making it the most influential factor.
- **Model Performance:**
  - **Causal-Informed Gradient Boosting (GB):**
    - **R² ≈ 0.93**
    - **MAE ≈ $1,250**
    - **Reliability Grade: A**
    - **Best overall performance and interpretability**
  - **Traditional Models (Ridge, GB):**
    - Good performance, but less aligned with true causal effects and less interpretable.
- **Explainability:** SHAP analysis and causal graphs provide clear, actionable insights into what drives insurance costs.
---
## Example Insights

- **Quitting smoking** or **reducing BMI** can significantly lower predicted insurance costs (From Dataset I used).

---

## Tech Stack

- **Python 3.12+**
- **pandas** — Data manipulation and analysis
- **numpy** — Numerical computing
- **matplotlib & seaborn** — Data visualization
- **scikit-learn** — Machine learning models and metrics
- **DoWhy** — Causal inference and effect estimation
- **SHAP** — Model explainability and feature attribution
- **plotly** — Interactive visualizations and dashboards
- **joblib** — Model serialization
---
