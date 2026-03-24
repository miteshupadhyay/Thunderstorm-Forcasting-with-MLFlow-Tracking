🌩️ Thunderstorm (TH) Forecasting System

A production-ready Machine Learning application for predicting Thunderstorm (TH) occurrence using atmospheric indices, with experiment tracking powered by MLflow.

🚀 Overview

This project delivers an end-to-end ML inference system designed for:

🌦️ Weather prediction use cases
⚡ Real-time thunderstorm risk estimation
🧪 Reproducible experimentation using MLflow

The system uses a pre-trained Random Forest model, optimized for performance and deployed via an interactive Streamlit interface.

✨ Key Features
🧠 Pre-trained Random Forest Model (no retraining required)
📊 Experiment Tracking with MLflow
⚡ Fast inference with Joblib compression
🎯 Handles class imbalance using SMOTE
🖥️ Interactive UI built with Streamlit
🐳 Docker-ready for deployment
☁️ Deployable on AWS / Render / Cloud platforms
🧩 Modular and scalable project architecture
📊 Input Features

The model leverages key atmospheric indicators to predict thunderstorm occurrence:

🌡️ SWEAT Index
🌪️ K Index
☁️ Totals Totals Index
🌍 Environmental Stability
💧 Moisture Indices
⚡ Convective Potential
🌡️ Temperature Pressure
🌫️ Moisture Temperature Profiles
🧠 Model Architecture
Component	Details
Algorithm	Random Forest Classifier
Training	Offline (separate pipeline)
Imbalance Handling	SMOTE
Model Format	Joblib
Model Size	~5–10 MB (compressed)
📈 Evaluation Metrics

The model performance is evaluated using both standard ML metrics and meteorological skill scores:

🔹 Standard Metrics
Accuracy
Precision
Recall
F1 Score
🔹 Domain-Specific Metrics
🌩️ Probability of Detection (POD)
🚨 False Alarm Rate (FAR)
📊 Heidke Skill Score (HSS)
🎯 Critical Success Index (CSI)
🧪 Experiment Tracking (MLflow)

All experiments are tracked using MLflow, enabling:

📌 Parameter logging
📊 Metric tracking
📦 Model versioning
🔁 Reproducibility

👉 This ensures a robust and auditable ML lifecycle

🖥️ Application Interface

The system provides a user-friendly interface built with Streamlit:

Input atmospheric parameters
Get real-time predictions
View probability outputs
🐳 Deployment Ready

This project is designed for seamless deployment:

✅ Docker support
✅ Cloud-ready (AWS / Render)
✅ Lightweight model for fast startup
