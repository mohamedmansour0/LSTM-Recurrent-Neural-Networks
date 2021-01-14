# LSTM-Recurrent-Neural-Networks

The dataset "airline-passengers.csv" gives the monthly number of
airline passengers in units of thousands.

I plotted the Time Series Data first, then I built the LSTM network
using Keras to predict the number of passengers next month given the 
number this month. then I built another LSTM network to do the same
prediction using this month and the previous two months.

The evaluation of the networks were based on the Root Mean Square 
Error rate (RMSE) for the Test score, and it was observed that the
first model (RMSE Test Score:0.10) performed better than the second
model (RMSE Test Score:0.13)
