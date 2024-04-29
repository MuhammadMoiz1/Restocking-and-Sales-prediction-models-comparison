# Restocking-and-Sales-prediction-models-comparison
## Sales prediction
Four models were trained and analysed for sales prediction the data was processed to convert it from daily to weekly information and then the models (LSTM, XGBoost regressor, Sarimax , Multivariate Prophet) were trained.
## Restock prediction
LSTM was used in two ways first was just training LSTM and predicting , the second was first trained Random forest and combined the actual sales and prediction sales from random forest and trained the LSTM according to these two columns.
