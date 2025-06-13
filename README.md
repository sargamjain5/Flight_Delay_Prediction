# Flight_Delay_Prediction
This project aims to predict airline arrival delays using supervised machine learning techniques. It includes both:

Classification – to predict whether a flight will be delayed by more than 15 minutes (arr_del15), and

Regression – to estimate the actual arrival delay time in minutes (arr_delay).

The pipeline covers data preprocessing, model training using Random Forests, performance evaluation with metrics like confusion matrix, ROC-AUC, and visualization of feature importance using SHAP. Trained models are saved and reusable for inference on new flight data.

The dataset used is based on real-world airline delay causes and includes flight information, dates, weather-related fields, and delay indicators.

This project is a practical demonstration of applying explainable machine learning to transportation and operational delay forecasting.
