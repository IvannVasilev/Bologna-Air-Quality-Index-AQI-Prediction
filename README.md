Bologna Air Quality Index (AQI) Prediction

This project analyzes and predicts the Air Quality Index (AQI) in Bologna, Italy, using historical air pollution and meteorological data.
The goal is to classify air quality into categories (Good, Moderate, Unhealthy, etc.) and explore which factors most influence pollution levels.

📌 Project Overview

Objective: Predict AQI category for Bologna based on pollutant levels and weather conditions.

Data: Historical air quality measurements (e.g., PM2.5, PM10, NO₂, O₃) combined with temporal features (season, hour, etc.).

Approach:

Data cleaning & preprocessing

Exploratory Data Analysis (EDA)

Feature engineering (seasonality, lag features, cyclic encoding)

Machine Learning modeling (Random Forest, Logistic Regression, XGBoost, etc.)

Model evaluation with classification metrics

🗂 Dataset

Source: https://opendata.comune.bologna.it

Features include pollutant concentrations, timestamps, and possibly meteorological variables.

Target variable: AQI category (multiclass classification).

⚙️ Methods & Models

Machine Learning models tested:

Logistic Regression

Random Forest

XGBoost

Feature Engineering:

Hour, day, month (with sine/cos encoding for cycles)

Lag features (previous AQI values)

Seasonal patterns

📊 Results

Best performing model: Random Forest Classifier

Achieved:

Accuracy: 0.9886882129277567 %

F1-Score (macro):  0.98 %
               
Key features: PM2.5, PM10, temperature, seasonality

📈 Visualizations

Some insights generated:

Distribution of AQI categories over time

Correlation heatmap of pollutants

Feature importance ranking


🚀 How to Run

Clone the repository:

git clone https://github.com/IvannVasilev/Bologna-Air-Quality-Index-AQI-.git
cd Bologna-Air-Quality-Index-AQI-


Open the Jupyter Notebook:

jupyter notebook "Bologna Air Quality Index Final Project.ipynb"



📌 Author

👤 Ivan Vasilev

GitHub: IvannVasilev

Interests: Data Science, Machine Learning, Data Analysis, Data Engineering
