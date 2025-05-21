# 📈 Anomaly Detection in Time Series Data

This project implements an anomaly detection system using deep learning (Autoencoders) on time series data. It is useful for identifying unusual behavior in sequences such as network traffic, sensor data, or stock prices.

---

## 📌 Problem Statement

Given a univariate time series, the task is to train an unsupervised model that can learn the normal behavior and detect anomalies (unusual data points) based on reconstruction error.

---

## 📊 Dataset

- `ambient_temperature_system_failure.csv` is the dataset.
- Contains regular patterns and occasional anomalies

---

## 🔧 Technologies Used

- Python
- Jupyter Notebook
- Pandas, NumPy
- TensorFlow, Keras
- Matplotlib

---

## 🧠 Deep Learning Model

- **Autoencoder Neural Network** (Unsupervised Learning)
  - Input → Dense → Bottleneck → Dense → Output
  - Trained to reconstruct normal data
  - High reconstruction error → Potential anomaly

---

## ✅ Steps Performed

1. Data Loading & Preprocessing
2. Autoencoder Model Design & Training
3. Reconstruction Loss Calculation
4. Threshold Selection for Anomalies
5. Visualization of Detected Anomalies

---

## 📈 Evaluation Metrics

- Precision
- Recall
- F1-Score

Used `precision_recall_fscore_support` from `sklearn.metrics` for evaluation.

---

## 📌 Output

The model successfully identifies anomalies in the time series based on reconstruction error, and plots them for visual inspection.
