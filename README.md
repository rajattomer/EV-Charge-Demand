# ⚡ EV Charging Demand Prediction

This project predicts electric vehicle (EV) charging demand by analyzing EV population data at the county level. The analysis is implemented in a Jupyter Notebook and is aimed at supporting infrastructure planning and energy resource allocation for EV adoption.

## 📊 Problem Statement

As electric vehicle (EV) adoption surges, urban planners must anticipate infrastructure needs—especially charging stations. Inadequate planning can cause bottlenecks and reduce user satisfaction.

## 📊 Dataset

**Dataset Name:** EV Population by County

* County Name
* Number of Registered EVs
* Vehicle Types
* Year
 Dataset Source: [Kaggle Dataset Link](https://www.kaggle.com/datasets/sahirmaharajj/electric-vehicle-population-size-2024)

## 📌 Objectives

* Analyze EV population distribution across counties.
* Build a model to forecast future EV charging demand.
* Identify high-demand regions to inform infrastructure development.

## 🧠 Future Work

* Incorporate charging station location data
* Use time-series forecasting (ARIMA, Prophet)
* Add real-time traffic or energy consumption data

## 🧠 Model

- **Algorithm Used**: Random Forest Regressor
- **Modeling Techniques**:
  - Lag features (1, 2, 3-month EV counts)
  - Rolling averages and percentage change
  - EV growth slope (trend over past 6 months)
  - RandomizedSearchCV for hyperparameter tuning


## 👨‍💻 Author

Rajat Kumar Tomer
