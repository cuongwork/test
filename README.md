# test
House Price Prediction

This is a machine learning project I built to practice data preprocessing, feature engineering, and model training in Python. I am currently learning data science and wanted to build a complete pipeline from reading raw data to evaluating different regression models.

## Project Overview

The main goal of this project is to predict housing prices based on various property features. Instead of just feeding raw data into an algorithm, I spent time exploring the dataset and creating new features to see if they could help the models learn better.

## What I Learned and Implemented

During this project, I experimented with several machine learning concepts:

*   **Feature Engineering**: I created custom variables that made logical sense to me, such as `area_per_bedroom`, `bath_per_room`, and a custom `luxury_score` based on the number of premium amenities a house has.
*   **Data Scaling**: I wasn't sure which scaling method would work best, so I wrote code to test and compare both `StandardScaler` and `MinMaxScaler`.
*   **Target Transformation**: I learned that housing prices are often skewed, so I applied a log transformation (`np.log1p`) to the price variable to see if it improves the model's accuracy.
*   **Model Comparison**: I trained and compared multiple models including Random Forest, Gradient Boosting, and XGBoost.
