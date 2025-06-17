# COVID-19 Data Analysis with SQL

This repository contains SQL scripts for analyzing global COVID-19 data, focusing on case and death trends, vaccination metrics, and country-level comparisons.

## Overview

The SQL workflow performs the following:

- Renaming and preparing data tables for clarity
- Inspecting table schema and distinct countries for data exploration
- Extracting the latest COVID-19 case and death statistics per country
- Calculating key metrics such as:
  - Cases and deaths as a percentage of population
  - Deaths as a percentage of total cases

## Key Queries and Features

- **Table renaming:** `compact` to `covid_data`
- **Latest data extraction:** Using Common Table Expressions (CTEs) to get the most recent data per country
- **Metrics calculation:** Cases/deaths vs population and cases
- **Vaccination analysis:** Coverage and ratios relative to cases
- **Data curation:** Creating `covid_selected_columns` table with comprehensive features including testing, hospitalizations, and socioeconomic indicators

## How to Use

1. Load the raw COVID-19 data into your SQL environment.
2. Run the provided SQL scripts sequentially to rename tables, inspect data, calculate metrics, and create curated datasets.
3. Use the curated dataset `covid_selected_columns` for further data analysis or visualization projects.

## Technologies

- SQL Server (T-SQL)

## Notes

- Excludes aggregated regional data (e.g., continents, income groups) to focus on individual countries.
- Date `'2021-02-22'` is used as a cut-off to compare pre- and post-vaccination death counts.





