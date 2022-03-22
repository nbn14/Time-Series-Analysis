# Time-Series-Analysis
Introduction to fundamental time series analysis concepts and modeling using SARIMA
-----------------------------------------------------------------------------------

In this notebook, we will go through basic concepts in time series analysis, introduce SARIMA modeling, and systematic parameter tuning methodology. The structure of the notebook follows:
1. Import libraries
2. Import data
3. Exploratory Data Analysis
4. Time series data pre-processing:
    - Smoothing of time series
    - Decomposition of time series
5. Time series analysis: identification of underlying processes
    - Autocorrelation
    - Partial autocorrelation
    - Recognising time series processes using ACF and PACF:
        - Noise
        - Autoregression (AR)
        - Moving average (MA)
    - Stationarity
        - Definition & visualisation
        - Statistical testing
6. Introduction to modeling using SARIMA
    - Basic concepts and parameters
    - Model selection and parameter tuning:
        - Initial estimates of parameters using ACF and PACF
        - Residuals diagnostics
        - Gridsearch for selected parameter space 
    - Best model's result visualisation & prediction


Data used in this analysis can be found at: https://raw.githubusercontent.com/jbrownlee/Datasets/master/daily-min-temperatures.csv
