				Stock Price Predictor
Obtained ‘Apple’ stock price dataset using pandasdatareader.api and analysed the data.Cleaned the data based on very correlated dropped.
Analysed the stock-price closing data using ‘MOVING AVERAGE’. Built a Linear_Regression model for ‘Close’ price analysis to take into account the trend.
 Created new dataset for feeding into Deep Learning model which comprises of data of past time_care(input) days.
 Built a function of Deep_Predictor which returns an LSTM based model for the column_data feeded into the fuction.
 Used loss function as ‘MeanSquaredError’ after normalizing the column_dataset.
 Built deep learning models for all imp columns and trained the models (Technical analysis).
Build a future predictor function which appends new predicted data into already existing data using deep learning models(taking inverse scale) and linear regression model ensembled.
