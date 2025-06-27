<hr style="height: 2px; background-color: #f8bbd0; border: none;">

<h1 style="color: #f8bbd0;">Forecasting African Elephant Population</h1>

This project started as an idea to raise awareness about elephant extinction.  
I wanted to predict how the population of African elephants might evolve over time using time series forecasting.

<h2 style="color: #d1c4e9;">Forecast Plot</h2>

Below is the forecast I generated using an ARIMA model:

![Forecast Plot](/data/processed/output.png)

As you can see, the result is mostly flat.  
This is because the data isn't well-suited for forecasting.

<h2 style="color: #d1c4e9;">What I Learned</h2>

- The data comes from different locations and years with large gaps  
- Many elephant populations only had data for a few scattered years  
- After resampling and averaging, the variation mostly disappeared  
- The model couldn't detect any strong trend or pattern  

<h2 style="color: #d1c4e9;">Why I'm Still Sharing This</h2>

Even if the result wasn't great, the process taught me a lot:  
- How to clean and organize real-world time series data  
- How to check for stationarity and apply differencing  
- How to build ARIMA models and evaluate their output  
- How to recognize when a dataset isn't suitable for a certain kind of analysis  

I believe it's important to share not only successful projects, but also the ones that didn't fully work.  
This shows the full data science process, including analysis, decision-making, and when to pivot.

<h2 style="color: #d1c4e9;">Tools Used</h2>

- Python  
- Pandas, Matplotlib  
- Statsmodels (ARIMA)  
- Interpolation, resampling, ADF stationarity test  

<hr style="height: 2px; background-color: #f8bbd0; border: none;">

<h1 style="color: #f8bbd0;">Thanks for reading !!</h1>
