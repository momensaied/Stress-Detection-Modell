# Stress Detection Using Machine Learning

This project focuses on detecting stress using physiological signals from the WESAD dataset. The goal is to build a binary classification model that distinguishes between stressed and non-stressed states.

---

##  Dataset: WESAD

The WESAD (Wearable Stress and Affect Detection) dataset is a multimodal dataset collected from wearable sensors, including:

- Electrodermal Activity (EDA)
- Heart Rate (HR)
- Accelerometer (ACC)

It contains data collected in real-life scenarios such as baseline, stress, and amusement conditions.

---

##  Project Pipeline

1. **Data Preprocessing**
   - Handling missing values
   - Normalizing signals
   - Windowing time-series data

2. **Feature Extraction**
   - Statistical features: mean, std, min, max, skewness, kurtosis, etc.
   - Features calculated for each window of EDA signals

3. **Model Training**
   - Binary classification: Stress vs Non-Stress
   - Train-test split used
   - Oversampling (e.g., SMOTE) applied to balance classes

4. **Model Evaluation**
   - Metrics used: Accuracy, Precision, Recall, F1 Score, ROC-AUC

---

##  Results

The model showed promising performance in detecting stress based on ECG features. Evaluation metrics were used to validate its effectiveness and reliability.

---

##  Files Included

- `stress_detection.ipynb`: Main notebook with final code
- `stress_detection.py`: Python script version 
- `Stress Detection.pptx`: Project presentation slides
- `README.md`: this file

---
