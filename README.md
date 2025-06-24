# 🌾 Crop Recommendation System using Decision Tree

This project leverages a *Decision Tree Classifier* to recommend the most suitable crop to grow based on key environmental and soil parameters such as nitrogen (N), phosphorus (P), potassium (K), temperature, humidity, pH, and rainfall. It provides a machine learning-based solution to help farmers make data-driven agricultural decisions.

---

## 📌 Objective

To develop an accurate and interpretable crop recommendation system using a supervised machine learning approach.

---

## 🧠 Model Overview

- *Algorithm:* Decision Tree Classifier
- *Advantages:*
  - Easy to understand and visualize
  - Works well with small to medium-sized datasets
  - Handles numerical and categorical features effectively

---

## 📊 Dataset Description
- *Source:* [Kaggle - Crop Recommendation Dataset](https://www.kaggle.com/datasets/atharvaingle/crop-recommendation-dataset)
- *Features:*
  - N – Nitrogen content in soil
  - P – Phosphorus content in soil
  - K – Potassium content in soil
  - temperature – Average temperature (°C)
  - humidity – Relative humidity (%)
  - ph – Soil pH level
  - rainfall – Rainfall (mm)
  - label – Recommended crop

---

## 🔍 Workflow

1. Data loading and preprocessing
2. Exploratory Data Analysis (EDA)
3. Model training using Decision Tree Classifier
4. Model evaluation using classification metrics
5. Predictions on new input data

---

## ✅ Model Performance

- *Accuracy:* ~98%
- *Metrics Used:*
  - Confusion Matrix
  - Precision, Recall, F1-Score
  - Classification Report

---
## 💡 Sample Prediction

```python
sample_input = [[90, 42, 43, 20.87, 82.00, 6.5, 202.93]]
prediction = model.predict(sample_input)
print(prediction)
# Output: ['rice']
