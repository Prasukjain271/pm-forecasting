@"
# PM2.5 / PM10 Forecasting with Deep Learning

Hourly forecasting of PM10 and PM2.5 across 21 stations using LSTM, TCN and 1D-CNN, plus cross-pollutant analysis.

## Dataset
Air quality dataset (Vrbančič, Mendeley Data, 2026), DOI: 10.17632/p86hnykz3d.2.
Not included in this repo. Download it and place the CSVs in a local data folder.

## Notebooks
1. 01_EDA: cleaning and exploratory analysis
2. 02_LSTM: LSTM forecasting (H = 1, 6, 24 h)
3. 03_TCN_CNN_Comparison: TCN and 1D-CNN vs LSTM vs persistence

## Setup
pip install pandas numpy matplotlib seaborn statsmodels scikit-learn torch
"@ | Out-File -Encoding utf8 README.md
