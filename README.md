# Nepal Weather Data Pipeline

Fetch, clean, analyze, and model Nepal weather data from Open-Meteo using Python.

## Overview

## Data
- Source: Open-Meteo Historical Weather API (free, no API key)
- Cities: Kathmandu (more planned)
- Period: 2026:september, daily
- Variables: temperature (max/min/mean), rainfall, wind speed

## Project Structure
```
nepal-weather-data-pipeline/
├── data/raw/
├── data/clean/
├── notebooks/
|   ├── 01_fetch.ipynb
|   ├── 02_clean.ipynb
|   ├── 03_eda.ipynb
└── requirements.txt
```

## How to Run
```powershell
pip install -r requirements.txt
```
Run the notebooks in order: 01 → 02 → 03.

## Findings


## Roadmap
- [x] Phase 1: fetch, clean, EDA
- [ ] Phase 2: statistical tests
- [ ] Phase 3: regression and clustering
- [ ] Phase 4: automated ETL pipeline with SQL storage