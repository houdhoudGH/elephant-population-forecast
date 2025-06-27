# Forecasting African Elephant Population

This project started as an idea to raise awareness about elephant extinction.  
I wanted to predict how the population of African elephants might evolve over time using time series forecasting.

## Forecast Plot

Below is the forecast I generated using an ARIMA model:

![Forecast Plot](/data/processed/elephant_forecast.png)

As you can see, the result is mostly flat.  
This is because the data isn't well-suited for forecasting.

## What I Learned

- The data comes from different locations and years with large gaps
- Many elephant populations only had data for a few scattered years
- After resampling and averaging, the variation mostly disappeared
- The model couldn't detect any strong trend or pattern

## Why I'm Still Sharing This

Even if the result wasn't great, the process taught me a lot:
- How to clean and organize real-world time series data
- How to check for stationarity and apply differencing
- How to build ARIMA models and evaluate their output
- How to recognize when a dataset isn't suitable for a certain kind of analysis

I believe it's important to share not only successful projects, but also the ones that didn't fully work.  
This shows the full data science process, including analysis, decision-making, and when to pivot.

## Tools Used

- Python
- Pandas, Matplotlib
- Statsmodels (ARIMA)
- Interpolation, resampling, ADF stationarity test

Thanks for reading <3