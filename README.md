# ❤️ Heart Disease Prediction

A Machine Learning web application that predicts the likelihood of heart disease using clinical patient data. The project combines data preprocessing, feature scaling, and a trained K-Nearest Neighbors (KNN) classification model to provide fast and accurate predictions through a simple Flask-based web interface.

---

## 📖 Overview

Heart disease remains one of the leading causes of death worldwide. Early prediction can help identify high-risk individuals and support timely medical intervention.

This application allows users to enter patient health information and instantly predicts whether the patient is likely to have heart disease using a trained machine learning model.

---

## 🚀 Features

- Predicts heart disease risk from clinical parameters.
- Interactive web interface built with Flask.
- Machine Learning prediction using KNN.
- Data preprocessing and feature scaling.
- Fast and responsive prediction system.
- Clean and lightweight application.

---

## 🛠 Tech Stack

- Python
- Flask
- Scikit-learn
- Pandas
- NumPy
- Pickle

---

## 📂 Project Structure

```
heart-disease-prediction
│
├── app.py
├── HeartdiseaseFinal.ipynb
├── knn_heart_model.pkl
├── heart_scaler.pkl
├── heart_columns.pkl
├── static/
├── templates/
└── README.md
```

---

## 📊 Machine Learning Workflow

- Data Collection
- Data Cleaning
- Exploratory Data Analysis (EDA)
- Feature Selection
- Feature Scaling
- Model Training
- Model Evaluation
- Model Serialization
- Flask Deployment

---

## 📋 Input Parameters

The model predicts heart disease using the following patient attributes:

- Age
- Gender
- Chest Pain Type
- Resting Blood Pressure
- Cholesterol
- Fasting Blood Sugar
- Resting ECG
- Maximum Heart Rate
- Exercise Induced Angina
- ST Depression
- Slope of ST Segment
- Number of Major Vessels
- Thalassemia

---

## ⚙️ Installation

### Clone the repository

```bash
git clone https://github.com/aradhyaganiga/heart-disease-prediction.git
```

### Navigate to the project

```bash
cd heart-disease-prediction
```

### Install dependencies

```bash
pip install -r requirements.txt
```

If a `requirements.txt` file is unavailable, install manually:

```bash
pip install flask pandas numpy scikit-learn
```

---

## ▶️ Run the Application

```bash
python app.py
```

Open your browser and visit

```
http://127.0.0.1:5000
```

---

## 📈 Future Enhancements

- Compare multiple machine learning algorithms
- Improve prediction accuracy
- Add model performance visualization
- Deploy the application using Render
- Improve user interface and responsiveness
- Add prediction history storage
- Integrate explainable AI techniques

---

## 📸 Application Preview

> Add screenshots of the application's home page and prediction results here.

---

## 🤝 Contributing

Contributions are welcome.

1. Fork the repository
2. Create a feature branch
3. Commit your changes
4. Push the branch
5. Open a Pull Request

---

## 👨‍💻 Author

**Aradhya Ganiga**

- GitHub: https://github.com/aradhyaganiga
- LinkedIn: https://linkedin.com/in/aradhya-ganiga
