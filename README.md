# Time-Series-Prediction---CO2-emission

Datasource: https://www.kaggle.com/datasets/ucsandiego/carbon-dioxide
I used XGBoost to build prediction for CO2 emission, we'll test data from 2015 to end.
At first, the result only good with few months close to early 2015, and it's totally off with farer years although the model evaluate right about feature importances.
After applying cross validation, the result was much better.

My code was built based on tutorial of Rob Mullar for Time series Forecast.

I also tried ARIMA auto, but it didn't help at all. I don't know much about ARIMA model, please feel free to give me feedback
