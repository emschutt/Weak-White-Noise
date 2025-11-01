# Weak-White-Noise

In this notebook I simulate weak white noise and check its properties.

### Key steps of this notebook

* Generate data using `np.random.normal`

* Check moments: sample mean/variance

* Quick eyeballing using a line plot to se the evolution and a histogram for the distribution, with a normal curve overlay for comparison

* Plotting ACF/PACF using statsmodels.tsa.stattools and graphics.tsaplots

* Using Ljung–Box test to check p-values across lags to confirm no autocorrelation
  
* Repeat the same steps in a log differentiated time series of SPY prices
