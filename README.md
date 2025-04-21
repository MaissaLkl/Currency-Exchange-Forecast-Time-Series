# 💱 Currency Exchange Rate Time Series Analysis

## 📌 Overview
This project applies time series analysis techniques using R to study Algeria's currency exchange rates. The analysis focuses on identifying trends, seasonality, and forecasting patterns from a dataset spanning over two decades. It includes data wrangling, decomposition, stationarity checks, modeling with ARIMA, and visualization.

## 🚀 Features
✅ Time series cleaning and transformation
✅ Handling of missing values and non-stationary behavior
✅ Visualization of long-term exchange rate trends
✅ Decomposition of time series into components (trend, seasonality, residual)
✅ ACF & PACF analysis
✅ Forecasting using models like ARIMA
✅ Evaluation of model performance using error metrics

## 📦 Requirements
- tidyverse
- lubridate
- zoo
- forecast
- tseries
- ggplot2
- dplyr

## 📂 Project Structure
``` bash
├── Data/
│   └── currency_exchange_rate.csv
├── TSA_Currency_Exchange_Rate.ipynb
└── README.md
```
## 🔧 Installation
Clone the repository:
``` bash
git clone https://github.com/MaissaLkl/Currency-Exchange-Forecast-Time-Series.git
```
Open the .ipynb file in R-compatible Jupyter or RStudio with IRkernel support.
Install required packages in R:
```bash
install.packages(c("tidyverse", "lubridate", "zoo", "forecast", "tseries", "ggplot2", "dplyr"))
```

## 📊 Usage
### 🧹 Preprocessing

✔ Convert columns to time series format
✔ Handle missing values
✔ Select and transform specific currency columns
✔ Normalize or log-transform skewed data

### 🔍 Time Series Analysis

- Plot time series for exploratory insights
- Decompose into trend, seasonal, and residual components
- Test for stationarity (ADF test)
- Plot ACF and PACF for model identification

### 🔮 Forecasting

- Fit ARIMA model on selected currency (Euro)
- Generate forecast for future dates
- Visualize and compare predictions
- Evaluate using MAE, RMSE, MAPE

### 🧠 Models
#### 🎯 ARIMA (AutoRegressive Integrated Moving Average)

- Handles non-stationary series with differencing
- Uses ACF/PACF to select p, d, q parameters
- Evaluated using residual diagnostics and forecast error metrics

### 📈 Visualizations
📌 Currency trends over time
📌 Decomposed time series components
📌 Autocorrelation and partial autocorrelation plots
📌 Forecasts vs. actual data
📌 Error metric comparisons

## 📊 Results
✔ Identified stable and volatile currencies
✔ Modeled and forecasted exchange rates with ARIMA
✔ Detected seasonal and long-term patterns
✔ Highlighted the importance of preprocessing for time series modeling

## 🚧 Limitations & Future Work
🔹 Add support for multivariate time series
🔹 Test additional models (SARIMA, Prophet, LSTM)
🔹 Automate model selection and tuning
🔹 Include macroeconomic indicators for enhanced prediction

## 🙌 Acknowledgments
**Dataset:** 'currency_exchange_rates_02-01-1995_-_02-05-2018' via https://drive.google.com/file/d/1EI32JPCMIZseDKoWcSm9IxSIh2VkPFtY/view?usp=sharing
Notebook developed as part of a Time Series Analysis course project.

💡 *"Forecasting currency movement through time – one pattern at a time."*