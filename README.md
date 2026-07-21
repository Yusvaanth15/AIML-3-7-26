# 🌦️ Weather Prediction using Machine Learning

An end-to-end Machine Learning project that predicts weather conditions using historical weather data. The project applies data preprocessing, exploratory data analysis (EDA), feature engineering, and a Random Forest Classifier to accurately classify weather conditions. It demonstrates a complete machine learning workflow from raw data analysis to model deployment.

---

# 📌 Project Overview

The **Weather Prediction using Machine Learning** project is designed to classify weather conditions based on historical meteorological observations. Using features such as precipitation, maximum temperature, minimum temperature, and wind speed, the model predicts weather categories including **Sun, Rain, Drizzle, Fog, and Snow**.

The project follows an end-to-end data science workflow, including data preprocessing, visualization, feature engineering, machine learning model development, evaluation, and model persistence.

---

# 🎯 Project Objectives

- Analyze historical weather data.
- Perform Exploratory Data Analysis (EDA).
- Clean and preprocess the dataset.
- Identify relationships between weather features.
- Build an accurate machine learning classification model.
- Evaluate model performance using standard metrics.
- Predict weather conditions for unseen data.
- Save and reload the trained model for future use.

---

# 🚀 Key Features

- Historical weather data analysis
- Data preprocessing and cleaning
- Exploratory Data Analysis (EDA)
- Feature engineering and feature selection
- Label encoding and feature scaling
- Weather classification using Random Forest
- Model evaluation with accuracy and confusion matrix
- Save and load trained model using Joblib
- Beginner-friendly implementation using Python

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
| Date | Date of weather observation |
| Precipitation | Rainfall amount (mm) |
| Temp Max | Maximum temperature (°C) |
| Temp Min | Minimum temperature (°C) |
| Wind | Wind speed |
| Weather | Weather condition (Target Variable) |

---

# 🎯 Prediction Target

The trained model predicts the following weather conditions:

- ☀️ Sun
- 🌧️ Rain
- 🌦️ Drizzle
- 🌫️ Fog
- ❄️ Snow

---

# 🤖 Machine Learning Workflow

The project follows a complete Machine Learning pipeline:

- Import Libraries
- Load Dataset
- Understand Dataset
- Exploratory Data Analysis (EDA)
- Feature Relationship Analysis
- Remove Outliers
- Data Cleaning
- Feature Engineering
- Feature Selection
- Label Encoding
- Train-Test Split
- Feature Scaling
- Model Creation
- Model Training
- Prediction
- Model Evaluation
- Save Model
- Load Model
- Predict New Weather Data

---

# 📊 Exploratory Data Analysis

The project includes comprehensive data analysis such as:

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

The following visualizations were performed:

- Weather Distribution
- Correlation Heatmap
- Histogram
- Scatter Plot
- Pair Plot
- KDE Plot
- Violin Plot
- Box Plot
- Bar Plot
- Count Plot
- Pie Chart

---

# 🧠 Machine Learning Model

### Algorithm Used

**Random Forest Classifier**

Random Forest is an ensemble learning algorithm that combines multiple decision trees to improve classification accuracy while reducing overfitting.

---

# 📏 Model Evaluation

The model performance is evaluated using:

- Accuracy Score
- Confusion Matrix
- Classification Report

> **Note:** Replace the evaluation metrics below with your actual results after training.

| Metric | Value |
|---------|-------|
| Accuracy | XX.XX % |
| Precision | XX.XX % |
| Recall | XX.XX % |
| F1-Score | XX.XX % |

---

# 💾 Model Persistence

The trained model and preprocessing objects are saved using **Joblib**.

Generated Files:

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
├── requirements.txt
├── README.md
└── LICENSE
```

---

# ▶️ Installation

### Clone the Repository

```bash
git clone https://github.com/your-username/Weather-Prediction.git
```

### Navigate to the Project

```bash
cd Weather-Prediction
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Run the Notebook

Open **Weather_Prediction.ipynb** using **Google Colab** or **Jupyter Notebook**, then execute all cells sequentially.

---

# 🔮 Future Enhancements

- Integrate real-time weather APIs.
- Compare multiple machine learning algorithms.
- Improve prediction accuracy using advanced ensemble methods.
- Deploy the model as a Streamlit web application.
- Develop a weather analytics dashboard.
- Support location-based weather prediction.

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
- Data Preprocessing
- Exploratory Data Analysis (EDA)
- Data Visualization
- Feature Engineering
- Machine Learning Classification
- Model Evaluation
- Model Persistence using Joblib

---

# 📜 License

This project is developed for **academic and educational purposes**. Feel free to use it for learning and research.
