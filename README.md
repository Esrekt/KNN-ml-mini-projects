# Machine Learning Mini Projects - KNN

This repository contains two small machine learning projects focused on applying the K-Nearest Neighbors (KNN) algorithm to both classification and regression problems.

---

## 1️Health Risk Classification

In this project, a classification model is built to predict a person's health risk status (`high_risk_flag`).

Features used:
- `bmi_score`
- `blood_pressure_variation`
- `activity_level_index`

### Why KNN?
KNN is a distance-based and intuitive algorithm. It performs well on small to medium-sized numerical datasets and is useful for understanding how similarity-based learning works.

### Why StandardScaler?
Since KNN relies on distance calculations, feature scaling is essential. StandardScaler was applied to ensure all features contribute equally to the distance metric.

---

## House Energy Consumption Regression

In this project, a regression model is built to predict daily energy consumption (`daily_energy_consumption_kwh`).

Features used:
- `avg_indoor_temp_change`
- `outdoor_humidity_level`

### Why KNN Regressor?
KNN Regressor can model non-linear relationships without assuming a specific functional form. It is effective for small datasets and provides a simple baseline model.

### Why Feature Scaling?
Because KNN is distance-based, scaling is necessary to prevent features with larger numeric ranges from dominating the model.

---

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib

---

## Purpose

These projects were developed to demonstrate the practical implementation of fundamental machine learning techniques, particularly KNN, for both classification and regression tasks.