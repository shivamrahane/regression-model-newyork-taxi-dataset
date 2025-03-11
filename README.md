New York Taxi Dataset EDA and Regression Model

>Project Summary

  This project focuses on exploratory data analysis (EDA) and predictive modeling for a dataset from New York City's taxi services. The primary goal is to 
  analyze the factors influencing taxi trip duration and develop a regression model to predict trip duration based on various features.

  The dataset comprises 1,458,644 rows and 11 columns, containing information on taxi trips, including:

   - pickup_datetime, dropoff_datetime

   - trip_distance

   -  pickup_longitude, pickup_latitude, dropoff_longitude, dropoff_latitude

   - passenger_count

   - trip_duration

>Key Steps:

  Data Cleaning & Preprocessing

   -  Verified no missing or duplicate values.

   -  Extracted temporal features: day, month, hour, weekday.

   -  Created new features for improved analysis (e.g., trip duration in minutes).

  Exploratory Data Analysis (EDA)

   -  Analyzed trip duration distribution.

   -  Explored the effect of time-based features (hour, weekday) on trip duration.

   -  Identified peak travel times and demand patterns.

   -  Evaluated correlations between trip distance and trip duration.

  Feature Engineering & Model Building

   -  Engineered features from datetime attributes.

   -  Applied scaling techniques for better model performance.

   -  Developed a regression model to predict trip duration.

>Problem Statement

  The objective of this project is to perform an exploratory data analysis (EDA) on the New York taxi dataset to uncover patterns and trends influencing trip 
  duration. Key factors such as trip duration, passenger count, pickup and drop-off locations, and time are analyzed to derive actionable insights. Based on the 
  findings, a regression model is developed to predict taxi trip duration, enabling better demand forecasting, pricing strategies, and operational optimization 
  for taxi services.

>Solution Approach

  To achieve the business objective, we adopted the following strategies:

   -  Understanding Demand Patterns: Analyzing peak travel times to help optimize taxi availability.

   -  Optimizing Pricing Strategies: Identifying seasonal and temporal trends for fare adjustments.

   -  Improving Customer Experience: Predicting trip durations more accurately to enhance service reliability.

   -  Operational Efficiency: Assisting taxi fleet management in planning and resource allocation.

>Regression Model & Results

  Several regression models were tested to predict trip duration, including:

   -  Linear Regression

   -  Decision Tree Regression

   -  Random Forest Regression

   -  Gradient Boosting Regression

  After evaluating model performance, Random Forest Regression was selected as the final model due to its:

   -  High R² score, indicating good predictive performance.

   -  Stable results across different test datasets.

   -  Robustness in handling outliers and feature importance.

>Conclusion

  This project successfully analyzed the New York Taxi dataset using PandasSQL for EDA and developed a regression model to predict trip duration. Key takeaways 
  include:

   -  Temporal factors significantly influence trip duration.

   -  Random Forest Regression outperformed other models in prediction accuracy.

   -  The model can assist taxi services in demand forecasting, route optimization, and pricing strategies.

  The insights gained from this project support data-driven decision-making for taxi services, improving overall efficiency and customer satisfaction.

>Future Enhancements:

   -  Incorporate real-time traffic data for better prediction accuracy.

   -  Use deep learning models for further improvements.

   -  Implement the model in a real-time taxi service application.

