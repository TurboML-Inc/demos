# TurboML Examples: Real-Time ML

Welcome to the **TurboML** demo examples repository! This repository showcases how to build and deploy machine learning pipelines that handle **real-time data** using TurboML’s platform. Whether you’re exploring **incremental learning**, analyzing the **effects of retraining**, or enriching **LLM prompts** with live features, these notebooks demonstrate end-to-end workflows to jumpstart your own real-time ML solutions.

## Why TurboML?

**TurboML** is a machine learning platform **reinvented for real-time**. That means everything—from data ingestion and feature engineering to modeling and deployment—is designed to handle streaming or rapidly changing data with minimal latency. 

## Repository Contents

### 1. `effects-of-retraining/`
- **`effects_of_retraining.ipynb`**  
  - Shows how **Static**, **Batch**, and **Online Incremental Learning** models perform over time.  
  - Includes a **Windowed Accuracy Analysis** to illustrate performance in dynamic environments.  
  - Explores trade-offs between frequent retraining and using incremental techniques.

### 2. `why-incremental-stateful-algorithms/`
- **`comparison_with_xgboost.ipynb`**  
  - Compares **Online Incremental Learning** models with **XGBoost** in dynamic data scenarios.  
  - Highlights how incremental models adapt to data distribution shifts without the overhead of repeated full-batch retraining.

### 3. `real-time-streaming-data/`
- **`streaming-anomaly-detection-stock-data.ipynb`**  
  - Showcases an end-to-end pipeline for **anomaly detection** on streaming stock data.   
  - Learn how to set up continuous model updates with minimal latency.

### 4. `real-time-data-with-llms/`
- **`prompts-with-real-time-data.ipynb`**  
  - Demonstrates how to **inject fresh data** from TurboML’s feature platform into LLM prompts.

### 5. `benchmark-dataset-upload-time/`
- **`benchmark_dataset_upload_time.ipynb`**  
  - Benchmarks **dataset validation and upload time** with the [IEEE-CIS Fraud Detection](https://www.kaggle.com/c/ieee-fraud-detection/data) dataset.
  - Analyzes:
    - Average time to upload datasets of varying sizes [10k, 50k, 100k, 250k, 500k].
    - Rows processed per second.

### 6. `benchmark-model-inferences/`
- **`benchmark_model_inferences.ipynb`**  
  - Benchmarks **single and batch model inference response times** of TurboML's **Adaptive XGBoost** and **Hoeffding Tree Classifier** models trained on [IEEE-CIS Fraud Detection](https://www.kaggle.com/c/ieee-fraud-detection/data) dataset.
  - Analyzes and compares TurboML's Adaptive XGBoost and Hoeffding Tree Classifier models on the following metrics:
    - Windowed Accuracy.
    - Average inference response time for single data points.
    - Average inference response time for varying batch sizes.

> **Note**: You can get the `BACKEND_URL` and `API_KEY` after you signup on [TurboML](https://turboml.com/). These notebooks are designed to run in **Google Colab** or a similar environment. 

Enjoy exploring these examples and building your own real-time ML pipelines with **TurboML**!  
