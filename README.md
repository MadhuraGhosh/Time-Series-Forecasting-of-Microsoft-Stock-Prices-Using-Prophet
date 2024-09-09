# Time-Series-Forecasting-of-Microsoft-Stock-Prices-Using-Prophet
This project demonstrates time series forecasting on Microsoft stock price data using Facebook’s Prophet model. The goal is to predict future stock prices based on historical data and evaluate the accuracy of the predictions using Root Mean Squared Error (RMSE).

Prophet is designed for analyzing time series data with daily observations that display trends and seasonality. It allows for easy integration and forecasting of time series data.
Dataset
The dataset contains historical stock price data for Microsoft, with columns including:

Date: The date of the stock price observation.
Close: The closing price of Microsoft stock on that day.
Steps of the Forecasting Process
Data Preparation: The dataset is pre-processed to fit Prophet’s requirements (date as ds and target variable as y).
Model Training: The Prophet model is trained on the historical stock price data.
Future Predictions: The trained model is used to forecast future stock prices.
Model Evaluation: RMSE (Root Mean Squared Error) is used to evaluate the forecast's accuracy.
Visualization: The forecast and its components (trend and seasonality) are visualized.
Dependencies
This project requires the following libraries:

prophet==1.1.0
pandas==1.5.3
matplotlib==3.6.1
scikit-learn==1.0.2
