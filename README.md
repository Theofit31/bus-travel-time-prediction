# Bus Travel Time Prediction using PySpark

This project focuses on predicting bus travel time per route using
GTFS Realtime data and weather data.

## Objective
- Predict travel time of bus routes
- Process large-scale transport data using PySpark

## Technologies
- Python
- PySpark
- Spark SQL
- Spark MLlib

## Description
The data is processed through ETL steps including data cleaning,
feature engineering (distance, speed, travel time), and aggregation
per route. A linear regression model is used to predict travel time
and evaluated using MAE, RMSE, and R² metrics.
