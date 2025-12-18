# 🌾 Crop Prediction Web App

A machine learning-powered **crop prediction web application** that suggests the most suitable crop based on soil and environmental parameters. Farmers and users can input soil quality and weather values to get accurate crop recommendations.

---

## 🚀 Features

✔ Predicts best crop for cultivation using a trained ML model  
✔ Simple and intuitive web interface  
✔ Runs locally with Python and Flask  
✔ Takes into account soil properties like N, P, K, pH + weather conditions  

---

## 🧠 How It Works

The app uses a pre-trained machine learning model (`crop_prediction_compressed.joblib`) and a label encoder (`label_encoder.joblib`) to:  
1. Accept inputs from the user (soil & environment).  
2. Process them with the ML model.  
3. Return the best crop recommendation based on learned patterns.

---

## 🗂 Repository Structure

