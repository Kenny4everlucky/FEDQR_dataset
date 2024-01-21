# INTRODUCTION
The data set is provided to the paper Feature-Enhanced Deep Learning Method for Electric Vehicle Charging Demand Probabilistic Forecasting of Charging Station

## About Data sets

### Load
This folder contains the raw data sets (raw_data.xlsx) form Jan 1st 2022 to Dec 31st 2022, as well as the data sets used for predictions under various seasonal scenarios (load_season.csv).

### Correlation_norm
This folder organizes the various variable sequences and normalizes them for correlation analysis (season_norm.csv).

### Forecasting results
This folder contains the point predictions for each model under each seasonal scenario (benchmark_season.xlsx).

### QR_calculation
The contents of this folder are used to calculate the qualification rate (QR) of each model.

## Environment Requirement
pytorch-lightning>=1.5.0
torch>=1.8.0
catboost>=1.0.6
holidays>=0.11.1
ipython>=5.0.0
joblib>=0.16.0
lightgbm>=2.2.3
matplotlib>=3.3.0
nfoursid>=1.0.0
numpy>=1.19.0
pandas>=1.0.5
pmdarima>=1.8.0
prophet>=1.1.1
requests>=2.22.0
scikit-learn>=1.0.1
scipy>=1.3.2
statsforecast>=1.0.0
statsmodels>=0.13.0
tbats>=1.1.0
tqdm>=4.60.0
xarray>=0.17.0
shap>=0.40.0

## About the Code
After this work is accepted, any researcher with a strong interest in this work is welcome to reasonably request the related code of this work.
