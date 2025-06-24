# Air-Quality-Index

Air pollution is a global challenge, significantly impacting public health and the environment. Accurate 
prediction of air quality is essential for mitigating its adverse effects and guiding effective policy decisions. 
This study employs machine learning techniques to forecast Air Quality Index (AQI) levels using publicly 
available datasets containing critical environmental parameters such as pollutant concentrations (e.g., 
PM2.5, NO2, and SO2). 

Six regression models, including Random Forest Regressor (RFR), Multiple Linear Regression (MLR), 
Polynomial Regression (PR), Decision Tree Regressor (DTR), XGBoost (XGB), and Support Vector 
Regressor (SVR), were trained and tested to identify the most accurate approach for AQI prediction. Model 
performance was evaluated using metrics such as R², Root Mean Squared Error (RMSE), Mean Absolute 
Error (MAE), and Root Mean Squared Logarithmic Error (RMSLE). 

The results indicate that the Random Forest Regressor outperformed other models, achieving the highest R² 
(0.9983) and the lowest RMSE (3.8577), MAE (1.7016), and RMSLE (0.0423). XGBoost also performed 
well, with an R² of 0.9979 and comparable error metrics. Polynomial Regression demonstrated the weakest 
performance, with a negative R² value (-4.1400) and high error rates, indicating overfitting and poor 
generalization.
