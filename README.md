# 🚕 Ride-Sharing Demand Prediction System

A spatio-temporal machine learning system built to predict ride-sharing demand hotspots by zone and time to optimize driver allocation.

## 📌 Problem Statement
Ride-sharing platforms struggle to position drivers efficiently without knowing where demand will spike next. This system predicts demand hotspots by zone and time to guide driver repositioning.

## 🛠️ System Architecture & Modules
1. **Ride Request Data Service:** Ingests and cleans NYC Taxi trip data into spatio-temporal grid zones.
2. **Demand Prediction Engine:** Machine Learning model (Random Forest Regressor) predicting hourly demand per zone.
3. **Driver Recommendation Service:** Intelligent repositioning alerts based on predicted demand intensity.
4. **Heatmap Dashboard:** Interactive Folium heatmap visualizing real-time high-demand hotspots.

## 📊 Performance Metrics
- **Mean Absolute Error (MAE):** 2.94
- **Root Mean Squared Error (RMSE):** 5.00

## 🚀 How to Run
1. Open `Ride_Sharing_Demand_Prediction.ipynb` in Google Colab.
2. Upload your `kaggle.json` credentials to download the NYC Taxi dataset.
3. Run all cells sequentially to generate model artifacts and render the heatmap dashboard.
