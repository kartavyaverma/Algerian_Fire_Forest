# Algerian Forest Fire Prediction 🔥

This project is an **end-to-end Machine Learning web application** that predicts the **Fire Weather Index (FWI)** using environmental features such as temperature, humidity, wind speed, and rainfall.

The model is deployed using **Flask** and allows users to input values through a web interface to obtain predictions.

---

## 📌 Project Overview

The goal of this project is to build a machine learning model that predicts the **Fire Weather Index (FWI)** for Algerian forest regions.

The system takes multiple environmental parameters as input and returns a predicted FWI value using a **Ridge Regression model**.

---

## ⚙️ Technologies Used

* Python
* Flask
* Scikit-Learn
* NumPy
* Pandas
* HTML
* Jinja2

---

## 📊 Features Used for Prediction

* Temperature
* Relative Humidity (RH)
* Wind Speed (Ws)
* Rain
* FFMC
* DMC
* ISI
* Classes
* Region

---

## 🧠 Machine Learning Model

The trained model used in this project:

**Ridge Regression**

Steps performed:

1. Data preprocessing
2. Feature scaling using **StandardScaler**
3. Model training
4. Model serialization using **pickle**
5. Deployment with **Flask**

---

## 📂 Project Structure

```
Algerian_Fire-Prediction
│
├── application.py
├── requirements.txt
├── README.md
│
├── models
│   ├── ridge.pkl
│   └── scaler.pkl
│
├── templates
│   ├── index.html
│   └── home.html
│
└── Algerian.ipynb
```

---

## 🚀 How to Run the Project

### 1. Clone the repository

```
git clone <your-repo-link>
```

### 2. Install dependencies

```
pip install -r requirements.txt
```

### 3. Run the Flask application

```
python application.py
```

### 4. Open in browser

```
http://127.0.0.1:5000
```

---

## 📈 Future Improvements

* Improve UI using Bootstrap
* Add model evaluation metrics
* Deploy on cloud platforms (Render / AWS / Heroku)

---

## 👨‍💻 Author

Kartavya Verma
