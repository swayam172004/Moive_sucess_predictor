# 🎬 Movie Success Predictor

![Logo](https://img.shields.io/badge/ML-Powered-blue?style=flat-square\&logo=python)
[![Streamlit](https://img.shields.io/badge/Streamlit-App-red?style=flat-square\&logo=streamlit)](https://streamlit.io/)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg?style=flat-square)](LICENSE)
[![Python](https://img.shields.io/badge/Python-3.8+-yellow.svg?style=flat-square\&logo=python)](https://www.python.org/)

> Predict if your movie will be a **Hit** or a **Flop** based on budget, cast, marketing, and more — powered by machine learning.

---

## 🚀 Features

* **Interactive** web interface with sliders & dropdowns
* **Real-time prediction** based on trained ML model
* **Customizable inputs** like genre, budget, director score, and more
* **Simple deployment** with Streamlit

---

## 📂 Project Structure

```
├── app.py              # Main Streamlit application
├── requirements.txt    # Dependencies
├── data/
│   └── movies_100k.csv # Dataset for training
└── src/
    └── model.py        # Model training and prediction logic
```

---

## 📦 Installation

1. **Clone the repository**

```bash
git clone https://github.com/your-username/movie-success-predictor.git
cd movie-success-predictor
```

2. **Install dependencies**

```bash
pip install -r requirements.txt
```

3. **Run the app**

```bash
streamlit run app.py
```

---

## 📊 How It Works

1. The dataset (`movies_100k.csv`) is used to train the model.
2. User inputs are collected via the web UI.
3. The model returns a prediction: **🎉 Hit!** or **❌ Flop**.

---

## 📷 Preview

![App Screenshot](https://via.placeholder.com/800x400.png?text=App+Preview)
*(Replace with actual screenshot or GIF of your app)*

---

## 🛠 Requirements

* Python 3.8+
* Streamlit
* Pandas
* NumPy
* Scikit-learn
* Joblib

---

## 📜 License

This project is licensed under the [MIT License](LICENSE).

---
