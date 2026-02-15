# Leveraging Statistical Analysis and Interactive Dashboards for Diesel Consumption Monitoring in IoT-Enabled Peacekeeping Operations.
## Overview

This repository contains the code developed for my MSc thesis on IoT-based diesel fuel consumption monitoring, analysis, and short-term forecasting.

The project implements a structured analytical workflow based on CRISP-DM, including:

- Data preprocessing and noise cleaning

- Temperature correction of fuel levels

- Time-series decomposition (STL)

- Spatial correlation analysis (Moran’s I)

- Short-term forecasting using statistical, machine learning, and deep learning models

## Notes

Due to confidentiality and operational sensitivity, the original dataset used in this research is not publicly available.

The repository contains only the analysis code.

## Dataset
Below you can find a sample dataset:

| DATE                  | DEVICE ID | Fuel Level  | Total Capacity | LAT      | LONG     |
|-----------------------|-----------|-------------|----------------|----------|----------|
| 2024-01-01 1:00:00 PM | 558       | 1500        | 2000           | 40.7128  | -74.0060 |
| 2024-01-02 2:00:00 PM | 559       | 1600        | 3000           | 34.0522  | -118.2437|
| 2024-01-03 3:00:00 PM | 591       | 1700        | 4000           | 51.5074  | -0.1278  |
| 2024-01-04 4:00:00 PM | 456       | 1800        | 5000           | 48.8566  | 2.3522   |
| 2024-01-05 5:00:00 PM | 670       | 1900        | 6000           | 35.6895  | 139.6917 |

## Authors

Elahe Torabidashti (Student)- elahe.torabidashti@gmail.com

Dr. Sergi Trilles (Main Supervisor)- strilles@uji.es
