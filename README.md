## Some finance/business type projects and notebooks to practice

# Probabalistic Forecasting of Stock Returns

Bayesian MCMC model to predict next month stock returns & attempting to quanitfy the uncertainty of said predictions. Goal is to see the distribution of outcomes. 

Using monthly adjusted close prices from yfinance api for 10 tickers i chose.
Used a bayesian normal likelihood model with priors from S&P500 historical data. MCMC sampling using PyMC
<img width="790" height="490" alt="image" src="https://github.com/user-attachments/assets/cc144533-524e-4fc8-8f69-8bac79d63f6a" />
