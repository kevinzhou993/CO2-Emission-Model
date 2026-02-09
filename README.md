# CO2 Emission Mapping Model

## Overview
This project builds a machine learning–based CO2 emission mapping model for vehicles by integrating
historical fuel consumption data, electric vehicle datasets, and on-chain vehicle mint data.

The goal is to estimate and analyze vehicle-level CO2 emissions when direct emission data is unavailable.

## Why This Project
Vehicle-level CO2 emission data is often incomplete or unavailable, especially for electric and hybrid vehicles.
This project addresses that gap by learning emission patterns from historical fuel consumption data and
mapping them to vehicles with missing emission records.

## My Contribution
- Designed the end-to-end data pipeline across heterogeneous datasets
- Performed data cleaning, feature alignment, and preprocessing
- Implemented and evaluated a Random Forest regression model for CO2 estimation
- Analyzed model behavior and results for downstream sustainability analysis
- Additional methodological details are provided in the accompanying documentation file

---

## Data Sources
- Battery Electric Vehicles (2012–2024)
- Plug-in Hybrid Electric Vehicles (2012–2024)
- Fuel Consumption Ratings (1995–2024)
- Vehicle Mint Data (off-chain metadata)

---

## Methodology
- Data cleaning and preprocessing across multiple datasets
- Feature alignment by vehicle make, model, and year
- Random Forest regression for CO2 emission estimation
- Model evaluation using standard regression metrics

---

## Files
- `Emission model.ipynb`: End-to-end data processing and model training
- `vehicle_mint_data.csv`: Vehicle mint metadata
- `*_fuel-consumption-ratings.csv`: Historical fuel consumption data
- `2012_2024_*_vehicles.csv`: EV and PHEV datasets

---

## Results
The model demonstrates strong performance in estimating vehicle CO2 emissions based on fuel consumption
and vehicle attributes, supporting downstream analytics and sustainability assessments.

---

## Author
Zifeng Zhou
