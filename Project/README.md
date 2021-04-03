Project for predict sales in ROSSMANN store. It used ARIMA, XGBoost, ETS, LSTM, GPU models. Calculated metrics RMSE and MAPE.
ETS is the one of simplest and at the same time the more exact model. However, the crucial fact is to correct determine initial seasonality. Non-correctly estimation seasonality lead to significantly increase of errors (RMSE+50%).
ARIMA has a long procedure of fitting and setting. At the same time this model does not differ distinctive quality of predictions. 
LSTM and GPU thanks to fact that they have very similar underpinning principles show about identical results. These models require a notable data preprocessing in contrast with other models. 
