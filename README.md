# California Housing Price Prediction

## Overview

This project is an end-to-end Machine Learning solution for predicting housing prices in California using the California Housing Dataset.

The project follows the complete machine learning workflow including:

- Data Collection and Loading
- Data Exploration and Visualization
- Data Cleaning
- Feature Engineering
- Data Preprocessing
- Model Training
- Model Evaluation
- Hyperparameter Tuning
- Final Model Selection

The goal is to predict the median house value based on various housing and demographic features.

---

## Dataset

The dataset contains information such as:

- Longitude
- Latitude
- Housing Median Age
- Total Rooms
- Total Bedrooms
- Population
- Households
- Median Income
- Ocean Proximity
- Median House Value (Target Variable)

Dataset Size: 20,640 records

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-Learn
- Jupyter Notebook

---

## Machine Learning Workflow

### 1. Data Loading

The housing dataset is loaded using Pandas.

### 2. Exploratory Data Analysis

- Data inspection
- Summary statistics
- Histograms
- Feature analysis

### 3. Data Preprocessing

- Handling missing values using SimpleImputer
- Feature scaling using StandardScaler
- Feature engineering
- Pipeline creation

### 4. Feature Engineering

Additional features created:

- Rooms per Household
- Bedrooms per Room
- Population per Household

### 5. Data Transformation

- Numerical Pipeline
- Categorical Encoding
- Full Preprocessing Pipeline

### 6. Model Training

Implemented models:

#### Linear Regression

Baseline regression model.

#### Decision Tree Regressor

Non-linear regression model.

#### Random Forest Regressor

Ensemble learning model with improved prediction performance.

---

## Model Evaluation

Evaluation metrics used:

- Root Mean Squared Error (RMSE)
- Mean Absolute Error (MAE)
- Cross Validation Scores

---

## Hyperparameter Tuning

GridSearchCV is used to find the optimal parameters for the Random Forest Regressor.

Parameters tuned:

- n_estimators
- max_features
- bootstrap

---

## Best Model

Random Forest Regressor achieved the best performance after hyperparameter tuning and was selected as the final model.

---

## Project Structure

```
Project/
│
├── housing.csv
├── End_to_End_ML_Project.ipynb
├── end_to_end.html
├── README.md
└── requirements.txt
```

---

## Installation

```bash
pip install pandas numpy matplotlib scikit-learn
```

---

## Run the Project

```bash
jupyter notebook
```

Open:

```
End_to_End_ML_Project.ipynb
```

---

## Learning Outcomes

This project demonstrates:

- Data Analysis
- Data Cleaning
- Feature Engineering
- Machine Learning Pipelines
- Model Evaluation
- Hyperparameter Tuning
- End-to-End ML Development

---

## Author

Ankith A

BCA Graduate | Data Science & Artificial Intelligence Enthusiast

