# Share Price Prediction Project

## Overview
This project aims to assess literature on share price prediction, exploring various forecasting techniques and their performance. It involves building and evaluating machine learning models discussed in the literature, employing feature engineering, and adjusting hyperparameters to improve predictive accuracy. The goal is to visualize model performance and provide insights on predictive capabilities.

## Literature Review
Modern machine learning (ML) methods outperform traditional forecasting techniques significantly. Techniques like SVR, Random Forest, and Linear Regression perform well over short prediction periods, while LSTM and Stateful LSTM excel over longer periods. Linear Regression emerges as the best-performing model due to strong linearity in predictor-target relationships.

## Methodology
The project explores regression-based approaches (SVR, Random Forest) and neural network approaches (LSTM, RNN). Feature engineering and hyperparameter tuning are employed to enhance model performance. Various ML models are compared based on their accuracies across different prediction periods and datasets.

## Results
ML methods generally outperform baseline models like ARIMA. Linear and ridge regression perform well across all prediction periods. LSTM accuracy increases with longer prediction horizons. Random Forest encounters scaling issues but still shows promise. RNN and CNN exhibit poorer performance compared to other ML models.

## Conclusion
Modern ML techniques show superiority over traditional methods in share price prediction. Linear regression and SVR perform consistently well, while LSTM excels over longer prediction periods. Future research could explore sentiment analysis, incorporate macroeconomic data, and extend prediction horizons for further insights.

## Recommendations for Future Research
Future research could focus on integrating sentiment analysis from social media data, incorporating macroeconomic indicators, and extending prediction horizons. Additionally, exploring advanced natural language processing techniques and analyzing individual company reports could enhance model accuracy and robustness.
