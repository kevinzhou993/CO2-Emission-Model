# CO2 Emission Mapping Model

## Overview
This project builds a machine learning–based CO2 emission mapping model for vehicles by integrating
historical fuel consumption data, electric vehicle datasets, and on-chain vehicle mint data.

The goal is to estimate and analyze vehicle-level CO2 emissions when direct emission data is unavailable.

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
