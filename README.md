# nyc-taxi-fare-prediction
Machine learning project to predict NYC taxi fares using geospatial and temporal data. Models include Linear Regression, Neural Network, and XGBoost, with feature engineering and evaluation based on RMSE and MAE.

# 🗽 NYC Taxi Fare Prediction Using Machine Learning

This project builds a machine learning model to predict New York City taxi fares using trip-specific information such as pickup and dropoff coordinates, time of day, and passenger count. It uses feature engineering and model comparison techniques to improve prediction accuracy, with XGBoost yielding the best results.

This project is run in Google Colab with all code and outputs available in the notebook.

---

## 📌 Project Overview and Goals

- Predict taxi fare amounts in NYC using real-world trip data.
- Engineer features like trip distance, time-of-day, and airport zones.
- Compare models: Linear Regression, Neural Network, and XGBoost.
- Evaluate with RMSE and MAE metrics to determine performance.
- Visualize fare trends and model accuracy with graphs and metrics.

---

## 🚀 Running the Project (Google Colab)

You can run this project entirely in the browser using Google Colab:

1. Click the **“Open in Colab”** badge above  
2. Follow in-notebook instructions to install any required packages (e.g., `xgboost`)  
3. Upload the dataset when prompted or modify paths as needed
<<<<<<< HEAD
=======
4. The link to the dataset is given in the README, also under data folder in git.
5. Upload the dataset zip file to the respective directory in Google Drive.
6. Make sure to not skip running any cell in the notebook.
>>>>>>> c1b84570ec9671a62402041ca1ec34e81dc57696

---

## 📦 Dependencies

Google Colab has most libraries pre-installed. The main packages used are:

- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `scikit-learn`
- `xgboost`

To manually install any missing package (if needed):
```python
!pip install xgboost
```

## 🗃️ Dataset

This project uses the NYC Taxi Fare Prediction dataset from Kaggle.

https://www.kaggle.com/competitions/new-york-city-taxi-fare-prediction/data

Place train.csv and test.csv into the Colab file system using the upload tool, or connect to Google Drive.

## 🧠 Assumptions & Notes
The dataset was filtered to 2 million rows for training efficiency.
Log transformation (log1p) was applied to reduce skewness in fare values.
Trip distance was calculated using the Haversine formula.
Binary flags and KMeans clusters were used to capture location-based patterns.

## 📄 License

This project is open-sourced under the MIT License.

## 👤 Author

Bhaskar Kuruvangattil Rejis
Texas State University – Computer Science
<<<<<<< HEAD

 
=======
>>>>>>> c1b84570ec9671a62402041ca1ec34e81dc57696
