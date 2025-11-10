# F3 Innovate — Frost Risk Forecast Challenge (2025)

## California Frost Forecasting Data Release

Creator: [F3 Innovate](https://f3i.org) | Platform: [National Data Platform (NDP)](https://nationaldataplatform.org)

## Overview 
This repository hosts the core datasets for the F3 Innovate Frost Risk Forecast Challenge (2025) — a competition designed to advance local frost prediction models across California.

The datasets include hourly meteorological observations (2010–2025) from 18 California Irrigation Management Information System (CIMIS) stations.
Participants will use these data to build, test, and validate machine learning models that forecast frost risk and temperature minima under microclimate variability.

## Content

| File / Folder                   | Description                                                                                                                         |
| ------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------- |
| **`cimis_all_stations.csv.gz`** | Combined dataset containing hourly weather data from **18 CIMIS stations (2010–2025)**. Compressed CSV (~2.3M rows, 38 MB gzipped). |
| **`stations/`**                 | Folder containing **individual station files** (`.csv`), one per site, each covering 2010–2025.                                     |
| **`README.md`**                 | This documentation file.                                                                                                            |

## Data Access
All data are cataloged and accessible through the National Data Platform (NDP).
Participants are encouraged to use the NDP environment for analysis and model development.
Advanced users may download data directly via this repository.