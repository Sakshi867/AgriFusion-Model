# 🌱 AI-Powered Crop Recommendation System

## 📌 Overview
This project provides a *Machine Learning based Crop Recommendation System* that suggests the most suitable crop for cultivation given soil and environmental conditions.  
It supports *sustainable agriculture* by enabling data-driven decisions for better yield and optimized resource use.

---

## 📂 Dataset
- *File:* Crop_recommendation.csv
- *Size:* 2200 records × 8 columns
- *Features:*
  - N → Nitrogen content in soil
  - P → Phosphorus content in soil
  - K → Potassium content in soil
  - temperature → Temperature in °C
  - humidity → Relative humidity (%)
  - ph → Soil pH value
  - rainfall → Rainfall in mm
- *Target:* label → Crop name (e.g., rice, maize, wheat, etc.)

---

## 🛠 Methodology
1. Data preprocessing: encoding, scaling
2. Model training: Random Forest Classifier (best accuracy)
3. Evaluation: accuracy, precision, recall, F1-score
4. Deployment: Streamlit web app


