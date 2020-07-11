# Predictive-Maintenance-Using-LSTM
Multiple Multivariate Time Series Prediction with LSTM Recurrent Neural Networks in Python with Keras

Sotware Environment

Python 3.6
numpy 1.13.3
scipy 0.19.1
matplotlib 2.0.2
spyder 3.2.3
scikit-learn 0.19.0
h5py 2.7.0
Pillow 4.2.1
pandas 0.20.3
TensorFlow 1.3.0
Keras 2.1.1

Problem Description

In this example I build an LSTM network in order to predict remaining useful life (or time to failure) of aircraft engines  based on scenarios. The network uses simulated aircraft sensor values to predict when an aircraft engine will fail in the future so that maintenance can be planned in advance. The question to ask is "Given these aircraft engine operation and failure events history, can we predict when an in-service engine will fail?" We re-formulate this question into two closely relevant questions and answer them using  machine learning models:


* Binary classification: Is this engine going to fail within w1 cycles?

Data Summary

In the Dataset directory there are the training, test and ground truth datasets. The training data consists of multiple multivariate time series with "cycle" as the time unit, together with 21 sensor readings for each cycle. Each time series can be assumed as being generated from a different engine of the same type. The testing data has the same data schema as the training data. The only difference is that the data does not indicate when the failure occurs. Finally, the ground truth data provides the number of remaining working cycles for the engines in the testing data.


LINK - https://cainvas.ai-tech.systems/notebooks/details/?url=cainvas-static.s3.ap-south-1.amazonaws.com/media/user_data/praveena002/Untitled.ipynb
