# stock-market-analysis-and-prediction
GitHub repository for researching and forecasting trends in the stock market. It includes code, information, and documentation about statistical analysis, machine learning, and other methods for comprehending the stock market and predicting trends in the future. For investors or analysts who are interested in understanding stock market behaviour, the repository might contain visualisation tools and other useful materials.


This code performs two separate tasks. The first task is to perform a basic analysis of the stock market for four companies - Apple, Google, Microsoft, and Amazon. The code downloads data for each company, concatenates the data into a single dataframe, and plots the historical view of the closing price and total volume of stock being traded each day. It also calculates the moving average for each company and plots a chart of the adjusted closing price along with the moving averages.

The second task is to perform a stock market prediction for the Apple stock using the Long Short-Term Memory (LSTM) algorithm. The code downloads historical stock price data for Apple, scales the data, and creates a training dataset to be used for training the LSTM model. Then, the code constructs an LSTM model and trains it on the training dataset. Finally, the model is used to make predictions on the test dataset.

Overall, the code is written in Python using several popular libraries such as Pandas, Numpy, Matplotlib, Seaborn, and Tensorflow.
