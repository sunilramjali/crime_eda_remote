# UK Crime Data Exploratory Data Analysis

This Project performs exploratory data analysis on UK police crime data across multiple police forces.

## Data Source
https://data.police.uk/data/
Following lists were selected downloading data:
Date range : Jan 2024 to Jan 2026
Forces: City of London Police, Metropolitan Police Service, Surrey Police, Thames Valley Police, West Midlands Police, West Yorkshire Police.
Data Sets: Include crime data

https://www.ons.gov.uk/peoplepopulationandcommunity/populationandmigration/populationestimates/datasets/lowersuperoutputareamidyearpopulationestimatesnationalstatistics
Data set: Mid-2022 revised (Nov 2025) to mid-2024 edition of this dataset

## Project Structure
data/ - Raw crime datasets (ignored in Git)
notebooks/ - Data preprocessing and EDA notebooks
	- ..preprocessing_exploratory.ipynb - exploring preporcessing
	- ..preprocessing_piplein.ipynb - run to create clean csv files 
	- ..eda.ipynb - EDA & visualisation
documentation/ - Project Statement of Work and EDA report
.gitignore - Prevents large data files from being tarcked by Git

## Github URL:
https://github.com/sunilramjali/crime_eda_remote.git