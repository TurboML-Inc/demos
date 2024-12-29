# Demos

This folder contains two Python scripts that demonstrate comparative analyses of machine learning models in different scenarios. Each script provides insights into the performance and characteristics of the models being studied.

## Files

### 1. `effects_of_retraining.ipynb`
This script focuses on evaluating the performance of **Static**, **Batch**, and **Online Incremental Learning** models in dynamic data environments. Key highlights include:
- **Windowed Accuracy Analysis**: A metric for understanding model performance over time in evolving data streams.
- **Comparative Insights**: Analysis of the advantages and trade-offs of retraining models versus using incremental learning techniques.

### 2. `comparison_with_xgboost.ipynb`
This script compares the performance of **Online Incremental Learning** models with **XGBoost** in dynamic data environments. Key highlights include:
- **Scenario-Based Analysis**: Explores how different learning models adapt to changing data distributions.
- **Visualization and Metrics**: Detailed visualizations and performance metrics for direct comparison.

## Note
- These scripts are intended to be executed within the Google Colab environment to utilize its pre-configured setup and resources.
- You can get the `BACKEND_URL` and `API_KEY` after you signup on [TurboML](https://turboml.com/).