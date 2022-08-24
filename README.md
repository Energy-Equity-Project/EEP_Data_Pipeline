# Energy Equity Project Data Pipeline

## Relevant Files
The eep.zip file contains 2 files:
- eep_dataset.csv
   - Holds the EEP dataset (includes all variables). Census tracts can be identified by the GEOID column which follows the US Census Bureau's structure.
- eep_codebook.csv
   - An excel file describing variables in the EEP dataset.

This repository showcases how data was collected, cleaned, processed and organized for EEP's mapping tool.

Our data goes through different stages:
1. Collect Raw Data
2. Clean and Preprocess data

## Collecting Data

- retrieval.ipynb documents how the raw data was collected.
- support_overview.ipynb documents supporting procedures and data. These were specifically used to either connect to the different sources or better organize the data.

## Clean and Preprocess Data

- clean_preprocess.ipynb documents how the raw data was cleaned and combined together in one dataframe.