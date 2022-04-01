# LSTM-Model-for-Time-Series-Forecasting
This model is required to learn from the series of past observations to predict the next value in the sequence.

## Working Principle
Firstly we will prepare the independent and dependent features from the given array (data). Now we will build the LSTM model. LSTM layer requires a three-dimensional input and LSTMs by default will produce a two-dimensional output as an interpretation from the end of the sequence. We can address this by having the LSTM output a value for each time step in the input data by setting the return_sequences=True argument on the layer. This allows us to have 3D output from the hidden LSTM layer as input to the next. After that we will predict the next 'n' number of values

## APPROACH
-Preparing independent and dependent features 

-Building LSTM Model

-Predicting For the next n data

-Visualizing The Output

## Packages Used
1. TensorFlow
2. Keras
3. numpy 
4. matplotlib

## OS used
Windows 10
