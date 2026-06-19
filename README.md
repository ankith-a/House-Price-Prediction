# 🏠 House Price Prediction — End-to-End ML Project

## 📌 Project Overview

This project implements a complete Machine Learning pipeline to predict California housing prices using demographic and geographical housing data.

The project covers the entire machine learning lifecycle:

- Data Collection
- Data Cleaning
- Exploratory Data Analysis
- Feature Engineering
- Data Preprocessing
- Model Training
- Model Evaluation
- Hyperparameter Tuning
- Model Saving

---

## 🎯 Objective

To build a predictive model that estimates housing prices based on various housing attributes such as:

- Median Income
- Population
- Total Rooms
- Total Bedrooms
- Housing Age
- Location Coordinates
- Ocean Proximity

---

## 🛠 Technologies Used

| Technology | Purpose |
|------------|----------|
| Python | Programming Language |
| Pandas | Data Manipulation |
| NumPy | Numerical Computing |
| Matplotlib | Data Visualization |
| Scikit-Learn | Machine Learning |
| Joblib | Model Serialization |

---

## 📂 Dataset

California Housing Dataset

Features:

- Longitude
- Latitude
- Housing Median Age
- Total Rooms
- Total Bedrooms
- Population
- Households
- Median Income
- Ocean Proximity

Target:

- Median House Value

---

## 📊 Exploratory Data Analysis

Performed:

✔ Data Inspection

✔ Missing Value Analysis

✔ Correlation Analysis

✔ Scatter Plots

✔ Histograms

✔ Feature Relationship Visualization

---

## ⚙️ Feature Engineering

Created new features:

- Rooms Per Household
- Population Per Household
- Bedrooms Per Room

These engineered features improved model performance significantly.

---

## 🔄 Data Preprocessing Pipeline

Implemented using Scikit-Learn Pipelines:

### Numerical Pipeline

- Missing Value Imputation
- Feature Engineering
- Standard Scaling

### Categorical Pipeline

- One-Hot Encoding

Combined using:

```python
ColumnTransformer
```

---

## 🤖 Models Implemented

### 1. Linear Regression

Used as baseline model.

### 2. Decision Tree Regressor

Captured non-linear relationships.

### 3. Random Forest Regressor

Provided the best performance.

---

## 📈 Model Evaluation

Metrics Used:

- RMSE (Root Mean Squared Error)
- MAE (Mean Absolute Error)
- Cross Validation Score

---

## 🔍 Hyperparameter Tuning

Implemented:

```python
GridSearchCV
```

Parameters tuned:

- n_estimators
- max_features
- bootstrap

Result:

Best Random Forest model selected automatically.

---

## 💾 Model Deployment Preparation

Saved trained model using:

```python
joblib
```

Example:

```python
joblib.dump(model, "lin_reg.pkl")
```

---

## 📁 Project Structure

```
End-to-End-Housing-Price-Prediction/
│
├── housing.csv
├── housing_prediction.ipynb
├── lin_reg.pkl
├── README.md
└── requirements.txt
```

---

## 🚀 Future Improvements

- Flask Web Application
- Streamlit Dashboard
- Real-Time Prediction API
- Advanced Ensemble Models
- Model Monitoring

---

## 👨‍💻 Author

Ankith A

BCA Graduate

Data Science & Artificial Intelligence Enthusiast

Web Developer | Machine Learning Learner

---

## ⭐ If you found this project useful

Give this repository a Star ⭐
