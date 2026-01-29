# bitcoin price prediction Using ARIMA and LSTM
  This project focuses on predict the price of bitcoin using forecasting (ARIMA and LSTM) models. The proposed study focuses on comparing the two very different models a statistical one (ARIMA) and deep learning one (LSTM) for the bitcoin price prediction.This project adopts an experimental research design, allowing for the development, evaluation and comparison of time-series and machine-learning model in the bases of performance and perfection.This project is made within the jupyter notebook.

Here some information about the forecasting models:

1.ARIMA:
  An ARIMA model, which stands for Autoregressive Integrated Moving Average, is a statistical technique used for analysing time series data. It's a powerful tool for understanding and forecasting trends in data that's collected over time. 
  Here's a breakdown of what ARIMA models are used for:
  -Understanding time series data: 
   ARIMA can help uncover patterns and relationships within the data, allowing you to gain insights into how the data has changed over time.
  -Forecasting future trends: 
   By analysing past data, ARIMA models can be used to predict future values in the time series. This is helpful for tasks like business 
   forecasting, sales prediction, and stock price analysis.

2.LSTM:
  LSTMs (Long Short-Term Memory) are a specific type of Recurrent Neural Network (RNN) that excel at time series forecasting within the realm of deep learning models. They address a major challenge faced by regular RNNs the vanishing gradient problem. This problem hinders RNNs from learning long-term dependencies in data sequences.
  Here's what makes LSTMs particularly adept at time series forecasting:
  -Internal Memory: 
   Unlike standard RNNs, LSTMs have an internal cellular structure that includes a cell state. This cell state acts like a memory lane, allowing the model to store information about past elements in the sequence and use it for processing later elements.
  -Gating Mechanism: 
   LSTMs control the flow of information through the cell state using special gates. These gates, namely the forget gate, input gate, and output gate, decide what information to keep, what new information to add, and what information to output. This selective process helps the model remember relevant past data for accurate forecasting.

 The ARIMA model is Simpler and easier to implement compared to LSTM,more interpretable and works well for stationary time series data with clear trends or seasonality.but it have limited ability to capture complex non-linear relationships in data and not suitable for data with significant structural changes or outliers.Comparatively, the LSTM model is Powerful for capturing complex patterns and non-linear relationships in time series data, it can handle large datasets effectively and it can automatically learn important features from data without extensive pre-processing. But it is more complex to implement, less interpretable and it can be prone to overfitting if not trained carefully with proper regularization techniques.
 
 When dealing with stationary data for Bitcoin price prediction, ARIMA can be a strong contender compared to LSTMs. In this project ARIMA having high accuracy than LSTM because data is stationary or clean format and LSTM made for non-stationary data. 
 
 Overall, this project demonstrates the potential of machine learning for Bitcoin price prediction. The chosen models (ARIMA and LSTM) achieved a level of accuracy in predicting the direction and magnitude of price movements. There’s no single "best" model universally. Experiment with both ARIMA and LSTMs on your specific data to determine which one performs better for your Bitcoin price prediction task.
 However, it's crucial to recognize the limitations. Bitcoin prices are influenced by various unpredictable factors, and no model can guarantee perfect forecasts

