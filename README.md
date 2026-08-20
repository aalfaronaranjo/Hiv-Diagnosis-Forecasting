# Hiv-Diagnosis-Forecasting

## Overview

This project analyzes trends in HIV diagnoses in the United States utilizing data from the CDC HIV Surveillance Report. 

The analysis was completed as part of PSTAT 199 at the University of California, Santa Barbara. This was completed over the course of a 10 week quarter and was supervised by Dr. Holmes. 

## Tools

- R
- R Markdown
- ggplot2
- forecast
- readxl
- dplyr / tidyr

## Analysis

This project includes:

- Data cleaning and preparation of CDC surveillance data
- Exploratory analysis of HIV diagnosis over time
- Linear regression modeling
- Exponential Smoothing (ETS)
- ARIMA modeling
- Model comparison using Root Mean Squared Error (RMSE)
- Demographic analysis of HIV diagnoses by sex
- Data visualization using ggplot2

## Results

Three forecasting approaches were compared utilizing RMSE:

Linear Regression : 1782.55
ARIMA : 2247.82
ETS : 2269.10

Among the models evaluated, linear regression produced the lowest RMSE. The demographic analysis also found that HIV diagnoses were consistently higher among males than females during the study period, whereas both groups showed similar percentage increases between the years 2019 and 2023.

## Limitations

The primary time series contains only five annual observations from 2019 to 2023. Because of the small sample size, the forecasting results should be interpreted as preliminary.

## Data Source

Centers for Disease Control and Prevention (CDC), HIV Surveillance Report, 2023. 
