# Energy Equity Project Data Pipeline

This repository showcases how data was collected, cleaned, processed and organized for EEP's mapping tool.

## Relevant Files
- eep_final_data.csv.zip
   - This is a CSV of the EEP dataset (includes all variables except for map geometries). Census tracts can be identified by the GEOID column which follows the US Census Bureau's structure.
- eep_final_simplified.json.zip
   - This is a GeoJSON and holds the EEP dataset (includes all variables). Census tracts can be identified by the GEOID column which follows the US Census Bureau's structure.

Our data goes through different stages:
1. Collect Raw Data
2. Clean and Preprocess data

## Collecting Data

- retrieval.ipynb documents how the raw data was collected.
- support_overview.ipynb documents supporting procedures and data. These were specifically used to either connect to the different sources or better organize the data.

## Clean and Preprocess Data

- clean_preprocess.ipynb documents how the raw data was cleaned and combined together in one dataframe.