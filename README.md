# Air Quality Forecasting Using Machine Learning
Prediction of C02 level using a historic dataset. Used various ML models.

## Project overview
This project aims to forecast carbon monoxide (CO) levels in air quality data using various machine learning models. Accurate air quality prediction is crucial for public health and environmental monitoring, making this study valuable for early warnings and policy-making. We explore different models, ranging from traditional statistical approaches to advanced deep learning techniques, to compare their effectiveness in short-term air quality forecasting.

## Models used
1. Moving Average (MA)
The Moving Average model is a simple statistical approach used to smooth out fluctuations in CO level data by averaging past values over a fixed window. While it provides a baseline for trend analysis, it lacks predictive power for sudden changes or complex patterns.

2. Random Forest (RF)
Random Forest is an ensemble learning method that constructs multiple decision trees to improve prediction accuracy and reduce overfitting. By leveraging feature importance, it helps in understanding the impact of different environmental factors on CO levels. However, it may struggle with time-dependent sequences due to its nature of handling data independently at each step.

3. XGBoost (Extreme Gradient Boosting)
XGBoost is a powerful boosting algorithm that enhances decision trees' predictive performance through gradient boosting techniques. It efficiently handles large datasets and captures non-linear relationships in air quality data. While XGBoost performs well with structured data, it requires careful hyperparameter tuning to prevent overfitting.

4. Long Short-Term Memory (LSTM)
LSTM, a deep learning-based recurrent neural network (RNN) variant, is specifically designed to handle sequential data and long-term dependencies. It excels in capturing temporal patterns in CO levels and provides accurate short-term forecasts. However, LSTM models require significant computational resources and large datasets for effective training.
