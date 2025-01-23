# Sonic Log Prediction
## Field Application of Intelligent Algorithms for Sonic Log Prediction in the Mishrif Oil Formation, Iraq

This repository contains the code, data, and documentation for predicting **sonic logs** using intelligent algorithms, specifically applied to the **Mishrif Oil Formation in Iraq**. The project demonstrates the effectiveness of machine learning models, such as **XGBoost**, **Artificial Neural Networks (ANN)**, and **Random Forest (RF)**, in predicting sonic logs from well log data.

---

## Table of Contents
1. [Introduction](#introduction)
2. [Methodology](#methodology)
3. [Results](#results)
4. [Repository Structure](#repository-structure)

---

## Introduction
Sonic logs, which measure the travel time of sound waves through subsurface formations, are critical for **reservoir characterization**, **geomechanical analysis**, and **drilling optimization**. However, acquiring sonic logs can be expensive and time-consuming. This project leverages **machine learning** to predict sonic logs from other well log data, such as gamma ray, resistivity, density, and neutron porosity.

The study focuses on the **Mishrif Formation**, a major carbonate reservoir in Iraq, known for its heterogeneity and complex lithology.

---

## Methodology
### Data Preparation
- **Input Data**: Well log data including Gamma Ray (GR), Deep Resistivity (LLD), Shallow Resistivity (LLS), Bulk Density (RHOB), and Neutron Porosity (NPHI).
- **Target Variable**: Sonic log (DT - compressional wave travel time).
- **Preprocessing**:
  - Handling missing values.
  - Normalizing/standardizing data.
  - Splitting data into training and testing sets.

### Machine Learning Models
- **Algorithms**:
  - **XGBoost**: A gradient-boosting algorithm known for its accuracy and efficiency.
  - **Artificial Neural Networks (ANN)**: Captures complex, non-linear relationships.
  - **Random Forest (RF)**: An ensemble method suitable for high-dimensional data.
- **Evaluation Metrics**:
  - **R² (Coefficient of Determination)**: Measures how well the model explains the variance in the target variable.
  - **RMSE (Root Mean Squared Error)**: Quantifies the prediction error.
  - **MAE (Mean Absolute Error)**: Provides a straightforward measure of error magnitude.

---

## Results
- **XGBoost** achieved the highest R² (e.g., 0.85) and lowest RMSE, indicating superior predictive accuracy.
- **ANN** performed well but required more computational resources.
- **RF** provided robust predictions but was slightly less accurate than XGBoost.
- **Feature Importance**: Bulk Density (RHOB) and Neutron Porosity (NPHI) were the most influential features for predicting sonic logs.

---

## Repository Structure
