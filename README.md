# 🌦️ Weather Prediction using Machine Learning

![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python)
![Machine Learning](https://img.shields.io/badge/Machine%20Learning-Random%20Forest-green)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-ML-orange?logo=scikitlearn)
![Status](https://img.shields.io/badge/Project-Completed-success)

An end-to-end **Machine Learning** project that predicts weather conditions using historical weather data. This project demonstrates the complete data science workflow, including data preprocessing, exploratory data analysis (EDA), feature engineering, model training, evaluation, and prediction using the **Random Forest Classifier**.

---

# 📌 Project Overview

The **Weather Prediction using Machine Learning** project is designed to classify weather conditions based on historical meteorological observations.

The model predicts weather categories such as:

- ☀️ Sun
- 🌧️ Rain
- 🌦️ Drizzle
- 🌫️ Fog
- ❄️ Snow

using environmental features including precipitation, maximum temperature, minimum temperature, and wind speed.

---

# 🎯 Project Objectives

- Analyze historical weather data.
- Perform Exploratory Data Analysis (EDA).
- Clean and preprocess the dataset.
- Identify relationships between weather features.
- Build a Machine Learning classification model.
- Evaluate model performance.
- Predict weather conditions for unseen data.
- Save and reload the trained model.

---

# 🚀 Key Features

- Historical Weather Data Analysis
- Data Cleaning & Preprocessing
- Exploratory Data Analysis (EDA)
- Feature Engineering
- Feature Selection
- Label Encoding
- Feature Scaling
- Random Forest Classification
- Model Evaluation
- Weather Prediction
- Model Persistence using Joblib

---

# 🛠️ Technologies Used

| Category | Technologies |
|----------|--------------|
| Programming Language | Python |
| Development Environment | Google Colab |
| Data Processing | Pandas, NumPy |
| Data Visualization | Matplotlib, Seaborn |
| Machine Learning | Scikit-learn |
| Model Serialization | Joblib |
| Version Control | Git & GitHub |

---

# 📂 Dataset Information

**Dataset Name**

Seattle Weather Dataset

### Dataset Features

| Feature | Description |
|----------|-------------|
| Date | Weather observation date |
| Precipitation | Rainfall amount (mm) |
| Temp Max | Maximum temperature (°C) |
| Temp Min | Minimum temperature (°C) |
| Wind | Wind speed |
| Weather | Target variable |

---

# 🎯 Prediction Target

The model predicts the following weather conditions:

- ☀️ Sun
- 🌧️ Rain
- 🌦️ Drizzle
- 🌫️ Fog
- ❄️ Snow

---

# 🤖 Machine Learning Workflow

```
Import Libraries
        ↓
Load Dataset
        ↓
Understand Dataset
        ↓
Exploratory Data Analysis (EDA)
        ↓
Feature Relationship Analysis
        ↓
Remove Outliers
        ↓
Data Cleaning
        ↓
Feature Engineering
        ↓
Feature Selection
        ↓
Label Encoding
        ↓
Train-Test Split
        ↓
Feature Scaling
        ↓
Create Random Forest Model
        ↓
Train Model
        ↓
Predict Test Data
        ↓
Evaluate Model
        ↓
Save Model
        ↓
Load Model
        ↓
Predict New Weather
```

---

# 📊 Exploratory Data Analysis (EDA)

The following analyses were performed:

- Dataset Overview
- Statistical Summary
- Missing Value Analysis
- Duplicate Record Removal
- Correlation Analysis
- Feature Relationship Analysis
- Outlier Detection
- Data Visualization

---

# 📈 Visualizations

The project includes:

- Weather Distribution
- Correlation Heatmap
- Histogram
- Scatter Plot
- Pair Plot
- KDE Plot
- Violin Plot
- Box Plot
- Bar Plot
- Pie Chart
- Count Plot

---

# 🧠 Machine Learning Model

### Algorithm Used

**Random Forest Classifier**

Random Forest is an ensemble machine learning algorithm that combines multiple decision trees to improve prediction accuracy while reducing overfitting.

---

# 📏 Model Evaluation

The model is evaluated using:

- Accuracy Score
- Confusion Matrix
- Classification Report

| Metric | Value |
|---------|-------|
| Accuracy | 81 % |
| Precision | 81 % |
| Recall | 81 % |
| F1-Score | 81 % |

> Replace these values with your actual model performance.

---

# 💾 Model Persistence

The trained model and preprocessing files are saved using **Joblib**.

Generated Files

```
weather_prediction_model.pkl
feature_scaler.pkl
label_encoder.pkl
```

---

# 📁 Project Structure

```
Weather-Prediction/
│
├── Dataset/
│   └── seattle-weather.csv
│
├── Notebook/
│   └── Weather_Prediction.ipynb
│
├── Model/
│   ├── weather_prediction_model.pkl
│   ├── feature_scaler.pkl
│   └── label_encoder.pkl
│
├── Images/
│   ├── weather_distribution.png
│   ├── correlation_heatmap.png
│   ├── histogram.png
│   ├── scatter_plot.png
│   ├── pair_plot.png
│   ├── violin_plot.png
│   ├── box_plot.png
│   └── count_plot.png
│
├── requirements.txt
├── README.md
├── LICENSE
└── .gitignore
```

---

# ▶️ Installation

### Clone the Repository

```bash
https://github.com/Yusvaanth15/AIML-3-7-26/blob/main/AIML_CT_PROJECT_(2).ipynb
```

### Navigate to the Project

```bash
cd Weather-Prediction
```

### Install Required Libraries

```bash
pip install -r requirements.txt
```

### Run the Notebook

Open **Weather_Prediction.ipynb** in **Google Colab** or **Jupyter Notebook** and execute all cells.

---

# 🔮 Future Enhancements

- Real-time Weather API Integration
- Compare Multiple Machine Learning Algorithms
- Improve Prediction Accuracy
- Streamlit Web Application
- Interactive Dashboard
- Location-based Weather Prediction

---

# 👨‍💻 Developer

**Yusvaanth A S**

B.E. Computer Science and Engineering

Nehru Institute of Engineering and Technology

---

# 📖 Learning Outcomes

This project demonstrates practical implementation of:

- Python Programming
- Data Analysis
- Data Cleaning
- Exploratory Data Analysis (EDA)
- Data Visualization
- Feature Engineering
- Machine Learning Classification
- Model Evaluation
- Model Persistence using Joblib

---

# ⭐ If you found this project useful

Please consider giving this repository a **⭐ Star** on GitHub.

---

# 📜 License

This project is developed for **academic and educational purposes**.
