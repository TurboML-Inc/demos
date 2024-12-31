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

### 2. `real-time-data-with-llms/`
- **`prompts-with-real-time-data.ipynb`**  
  - Demonstrates how to **inject fresh data** from TurboML’s feature platform into LLM prompts.

### 3. `real-time-streaming-data/`
- **`streaming-anomaly-detection-stock-data.ipynb`**  
  - Showcases an end-to-end pipeline for **anomaly detection** on streaming stock data.   
  - Learn how to set up continuous model updates with minimal latency.

### 4. `why-incremental-stateful-algorithms/`
- **`comparison_with_xgboost.ipynb`**  
  - Compares **Online Incremental Learning** models with **XGBoost** in dynamic data scenarios.  
  - Highlights how incremental models adapt to data distribution shifts without the overhead of repeated full-batch retraining.

> **Note**: You can get the `BACKEND_URL` and `API_KEY` after you signup on [TurboML](https://turboml.com/). These notebooks are designed to run in **Google Colab** or a similar environment. 

Enjoy exploring these examples and building your own real-time ML pipelines with **TurboML**!  