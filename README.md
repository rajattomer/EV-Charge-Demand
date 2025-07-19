# ⚡ EV Charging Demand Prediction

This project predicts electric vehicle (EV) charging demand by analyzing EV population data at the county level. The analysis is implemented in a Jupyter Notebook and is aimed at supporting infrastructure planning and energy resource allocation for EV adoption.

## 📊 Dataset

**Dataset Name:** EV Population by County

* County Name
* Number of Registered EVs
* Vehicle Types
* Year

## 📌 Objectives

* Analyze EV population distribution across counties.
* Build a model to forecast future EV charging demand.
* Identify high-demand regions to inform infrastructure development.

## 🛠️ Requirements

Install required packages using pip or conda:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn xgboost
```

Or via conda:

```bash
conda install pandas numpy matplotlib seaborn scikit-learn
conda install -c conda-forge xgboost
```

## 🚀 How to Run

1. Clone the repository or download the files.
2. Ensure the dataset is in the correct folder.
3. Launch Jupyter Notebook:

   ```bash
   jupyter notebook
   ```
4. Open `EV_Charging_Demand_Prediction.ipynb.ipynb` and run the cells sequentially.


## 📌 Example Visualizations

* County-level heatmap of EV density
* Predicted vs. Actual charging demand plots
* Feature importance rankings

## 🧠 Future Work

* Incorporate charging station location data
* Use time-series forecasting (ARIMA, Prophet)
* Add real-time traffic or energy consumption data

## 👨‍💻 Author

Rajat Kumar Tomer
