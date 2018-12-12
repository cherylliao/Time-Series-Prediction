# Time-Series-Prediction
This is a multivariate forecasting problem.  Given a historical data of climate conditions, predict the temperature of the NEXT HOUR based on climate conditions and temperature over the last 24 hours. 

The models best suited for this task are recurrent neural networks.  Specifically LSTM or GRU.  In my case I chose to use 3 layers of convultional nets to capture the pattern, then pass the patterns through 3 layers of GRU to retain important long term vs. short term patterns, then one final dense layer with linear activation, since this is essentially a regression problem, to produce the predictions. 

Youtube Link: 
https://www.youtube.com/watch?v=P4gzqK6XRy8&feature=youtu.be&hd=1

