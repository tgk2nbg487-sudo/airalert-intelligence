# airalert-intelligence
Time-series analysis of air raid alerts in Kyiv

## Project Overview

This project analyzes the timing of air raid alerts in Kyiv, Ukraine, using time-series analysis and machine learning.

## Data Source

The data is obtained from the Kyiv Open Data Portal.

- **Dataset:** Air raid alerts in Kyiv (JSON)
- **Source:** [Download airalerts.json](https://data.kyivcity.gov.ua/dataset/bb0f27d3-00e2-414a-9d6e-a8b6633f8a2a/resource/5e4fb8a8-f0c8-4a12-885f-192d1f0dba75/download/airalerts.json)

## Methods

- Data cleaning and quality checks
- Timestamp and timezone handling
- Hourly time-series analysis
- Feature engineering
- Logistic Regression and baseline comparison

## Limitations

The analysis depends on the completeness and correct interpretation of the source timestamps. The model is an educational research project and is not intended for operational air raid warnings.
