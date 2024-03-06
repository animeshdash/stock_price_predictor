# stock_price_predictor

The primary goal of the paper is to predict stock market values using machine learning techniques to build a robust forecasting model.
Application of deep learning method of LSTM (long short term memory) , to show how deep learning triumphs over machine learning.

Data:

We have used the stock market price of of Apple for the year May 2015 to May 2020. And we have used 

Methodology:

I have chosen Apple which has hight impact on the market. The data consists of daily index of Apple over a stretch of five years from 2015- 2020 starting from May 2015 to May 2020.
This data has been used to predict the stock market values over a weekly horizon for one year.

The raw data consists of variables containing information about the daily index of these companies. The variables are namely date, open values, closed values, high values, low values, volume and range.

We have converted these variables into their normalised form using min-max normalisation, to make them suited for use in machine learning models.

For calculating the accuracies, we had to reverse transformed the normalized values by using the formula (RMSE/mean absolute values)%. For calculating the accuracies, we had to reverse transformed the normalized values by using the formula (RMSE/mean absolute values)%.

LSTM(Long Short Term Memory):

LSTM - LSTM is a very efficient deep learning method which is a sub branch of RNN (Recurrent Neural Networks). RNN has a feature which LSTM inherits, i.e., it allows back-propagation method simultaneously unlike the multi-level perceptron’s (MLP’s) feed-forward process. 

The back propagation helps to resolve the weightage problem (vanishing gradient and exploding gradients) of the nodes and leads us to more impressive results. This is why LSTM is appropriate for time series analysis, handwriting recognition and speech processing.

LSTM architecture consists of many software blocks ,out of which there are basically  salient three regulator gates connected by several information channels and a memory cell. These gates of three types i) The input gates ii)The output gate iii) The forget gate.
The  LSTM model is built using the frameworks Keras and Tensorflow 2.0.0 , with python being the underlying language.

Conclusion:

This use case best describes a Time Series problem. LSTM (Long Short Term Memory) are the few best available approaches to deep learning. The models demonstrated considerable confidence in predicting share price with minimal error. In this instance, data size is relatively less, and therefore the selection of the model is based on performance(error reduction) instead of computational efficiency.  Considering the financial impact of share price prediction, The LSTM model scores better than machine learning models.

As different techniques of machine and deep learning have produced different performances, as a future scope of work we plan to explore the possibility of fine tuning these models and aim for higher prediction accuracy. For example ARIMA and ARMA model might be more accurate in this type Time series based application.