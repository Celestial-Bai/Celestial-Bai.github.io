# Extension
  
From above we can find that VAR model may not predict the data of COVID-19 as well as our expectation. That is because the time-series of COVID-19 cases is not stationary, and we can use acf() to test whether the time-series is stationary.  
<font color=Blue>Note: The method we will use in the Extensions Section (LSTM) cannot perform well in RMarkdown, so I will share them in this document. It is also R code, and we will only use time-series data of the daily infected cases in Tokyo as the example.</font>  
