# Anomaly Detection in Ship Engine Sensor Data

This project applies unsupervised anomaly detection techniques to identify potential faults in engine sensor readings. The aim is to detect outlier weeks that show abnormal behaviour based on multiple features.

---

## Project Overview

Sensor data from a ship engine is analysed to flag operational anomalies using both statistical and machine learning methods. The project evaluates which method produces interpretable and consistent results within an expected anomaly range.

**Techniques used:**
- IQR-based outlier detection (per feature)
- One-Class SVM
- Isolation Forest (tuned for 1–5% anomaly rate)
- Dimensionality reduction via PCA for 2D visualisation

*Full PDF report included in the repo.*

---

## Key Steps

1. Clean and preprocess the weekly sensor data
2. Detect outliers with IQR on individual features
3. Apply ML-based models (One-Class SVM, Isolation Forest)
4. Visualise detected anomalies using PCA
5. Compare anomaly counts and overlap across methods

---

## Status

The entire analysis is implemented in a single Jupyter Notebook.  
The notebook is self-contained and includes all necessary code, visualisations, and results.
