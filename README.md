# Panama Electricity Load Forecasting

## Overview
This project focuses on short-term electricity load forecasting for the Panama power grid.
The goal is to predict hourly electricity demand for one week (168 hours) using deep learning
models and compare the results with the official weekly pre-dispatch forecasts.

## Dataset
- Hourly historical electricity load (post-dispatch)
- Official weekly pre-dispatch forecasts
- Weather data (temperature, humidity, precipitation, wind speed)
- Calendar information (holidays, school periods)

## Forecasting Setup
- Forecast horizon: 168 hours (1 week)
- Weekly forecast window: Saturday to Friday
- A 72-hour unseen data gap is enforced before each forecast period
- Data resolution: hourly

## Models
- LSTM
- 1D CNN 
- CNN-LSTM (hybrid)

## Evaluation
- MAE
- RMSE
- sMAPE
