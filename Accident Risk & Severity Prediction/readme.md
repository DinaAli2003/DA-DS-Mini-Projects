# 📌 Accident Risk & Severity Prediction

## 🚗 Project Title

**Accident Risk & Severity Prediction using Machine Learning**

## 📖 Overview

This project focuses on analyzing large-scale traffic accident data and building machine learning models to predict accident severity. The goal is to extract meaningful insights that help improve road safety and support data-driven decision-making for transportation authorities and policymakers.

## 🎯 Objectives

* Analyze historical accident data
* Identify high-risk locations and patterns
* Predict accident severity (multi-class classification)
* Provide actionable insights for road safety improvement

## 📊 Dataset

* **Source:** Kaggle – US Accidents Dataset
* **Size:** 7+ million records
* **Features include:**

  * Location (latitude, longitude, city, state)
  * Weather conditions (temperature, humidity, visibility)
  * Road infrastructure (traffic signals, crossings, junctions)
  * Temporal data (time, day, month)
* **Target Variable:** `Severity (1–4)`

## ⚙️ Project Pipeline

### 1. Data Preprocessing

* Handling missing values (median & mode imputation)
* Removing duplicates and irrelevant columns
* Feature encoding (frequency encoding, binary encoding, target encoding)
* Feature scaling using StandardScaler
* Outlier handling and capping

### 2. Feature Engineering

* Extracted time-based features (hour, day, month, year)
* Created **Rush Hour** indicator
* Applied cyclical encoding (sin/cos transformations)
* Calculated accident duration

### 3. Exploratory Data Analysis (EDA)

* Identified temporal trends (rush hours, weekdays)
* Analyzed weather impact on accidents
* Detected geographical hotspots
* Examined class imbalance

### 4. Handling Class Imbalance

* Oversampling minority classes
* Undersampling majority class
* Applying class weights

### 5. Modeling

Implemented and compared multiple models:

* XGBoost
* LightGBM
* CatBoost
* Neural Network

### 6. Evaluation Metrics

* Precision
* Recall
* F1-Score (Primary metric)
* Macro & Weighted averages

## 🏆 Results

* **Best Model:** XGBoost
* **Performance:**

  * Accuracy: 85.7%
  * Macro F1-score: 0.674
  * Weighted F1-score: 0.861

### Key Insights

* Strong performance on majority class (Severity 2)
* Difficulty in predicting rare severe accidents (Severity 4)
* Misclassification often occurs between adjacent severity levels

## 📊 Tools & Technologies

* Python (pandas, numpy, sklearn)
* XGBoost, LightGBM, CatBoost
* Matplotlib, Seaborn
* Power BI (for dashboard)
* Kaggle environment

## 📈 Output

* Predictive model for accident severity
* Interactive dashboard for visualization
* Insights for road safety improvement

## 🔮 Future Work

* Improve minority class prediction
* Apply advanced resampling techniques
* Deploy real-time prediction system

## 👥 Team

* **Dina Ali** – Preprocessing, Modeling, Presentation
* Nada Shady – Data Collection & Modeling
* Marwa Ashraf – Encoding, Modeling & Dashboard

## 🏛️ Program

Developed under **Digilians Initiative**
Supervised by the **Ministry of Communications and Information Technology (MCIT)**
In collaboration with the **Egyptian Military Academy**

