# LSTM_Stock_Predictor

1. Data Prep for training and testing.
2. Build and train custom LSTM RNNS
3. Evaluate model performance

Files:</br>
[LSTM - Closing Price Prediction](https://github.com/kyleplathe/LSTM_Stock_Predictor/blob/main/lstm_stock_predictor_closing.ipynb) </br> [LSTM - Fear and Greed Prediction](https://github.com/kyleplathe/LSTM_Stock_Predictor/blob/main/lstm_stock_predictor_fng.ipynb)

## Data Prep for training and testing
- Use the FNG values to predict future closing prices.
- Use the past closing prices to predict future closing prices.
- Apply the MinMaxScaler to the X and Y values to scale the data for the model.
-Reshape X_train and X_test to fit the model requirements (samples, time steps, and features)

## Build and train custom LSTM RNNS
- Create a notebook to fit the data using FNG Values.
- Create a notebook to fit the data using the closing prices.

## Evaluate Model Performance
- Determine which model had the lowest loss. - The model using closing prices
</br>
- Determine which model tracks the actual values best over time. - The model using closing prices.
- Determine the appropriate Window Size for the model.  - 10 Day window for the closing price seemed to be the best.

![Closing Price](images/lstm_stock_predictor_closing.png)
![Fear and Greed Price](images/lstm_stock_predictor_fng.png)