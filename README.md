# 🌱 Crop Prediction Web Application

A machine learning–based web application built using Flask that predicts the most suitable crop based on soil and environmental conditions.

---

## 📌 Overview

Agriculture productivity depends on soil nutrients and climate conditions. This application uses a trained machine learning model to recommend crops based on user-provided inputs such as soil nutrients, temperature, humidity, pH, and rainfall.

---

## 🚀 Features

- Crop prediction using Machine Learning  
- Flask-based web interface  
- Pre-trained model loaded with joblib  
- Label encoding for accurate predictions  
- Simple and user-friendly UI  

---

## 🧠 Machine Learning Model

- Model file: `crop_prediction_compressed.joblib`
- Label encoder: `label_encoder.joblib`
- Dataset used: `cr2.csv`
- Algorithm trained using Scikit-Learn

---

## 📂 Project Structure

```text
Crop-Prediction/
├── static/
│   └── image/
├── templates/
│   ├── index.html
│   └── result.html
├── app.py
├── cr2.csv
├── crop_prediction_compressed.joblib
├── label_encoder.joblib
├── requirements.txt
├── .gitignore
└── README.md
```

---

## 🛠 Technologies Used

- Python
- Flask
- Scikit-Learn
- Joblib
- Pandas
- NumPy
- HTML / CSS

---

## ⚙ Installation

```bash
git clone https://github.com/kesarwani2509/Crop-Prediction.git
cd Crop-Prediction
pip install -r requirements.txt
```

---

## ▶ Run the Application

```bash
python app.py
```

Open browser and visit:

```text
http://127.0.0.1:5000/
```

---

## 🧪 Input Parameters

- Nitrogen (N)
- Phosphorus (P)
- Potassium (K)
- Temperature
- Humidity
- pH
- Rainfall

---

## 📊 Output

- Displays the predicted crop based on inputs  
- Prediction result shown on a separate result page  

---

## 📦 Dependencies

All required libraries are listed in `requirements.txt`.

---

## 🚀 Future Scope

- Cloud deployment  
- Model accuracy improvement  
- API integration  
- Mobile-responsive UI  

---

## 📄 License

No license specified.

---

## ⭐ Acknowledgment

This project is created for educational and practical learning purposes.

---

## 👨‍💻 Author

Kesarwani2509  
GitHub: https://github.com/kesarwani2509
Website: https://crop-prediction-87hr.onrender.com/
