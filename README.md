# Unveiling the Relationship: Greenhouse Gas Emissions, Facilities, and Air Quality
# README.md
## Overview
This project investigates the relationship between industrial facilities, greenhouse gas emissions, population density, and air quality in various US counties. The study aims to identify the facilities primarily linked to greenhouse gas emissions and predict air pollution levels in different counties. The findings demonstrate the significant impact of industrial activities and population density on air pollution. The establishment of the models in this study provides valuable insights for policymakers to address air pollution caused by industrial activities.

## Project Goals
1. **Identify Facilities Linked to Greenhouse Gas Emissions**: Determine which industrial facilities are predominantly responsible for greenhouse gas emissions (e.g., CO2, CH4, N2O) and pose a significant threat to the climate.
2. **Predict Air Pollution Levels**: Utilize information on these facilities to predict air pollution levels in various counties, considering factors such as population density and industrial activity.

## Data Sources
1. **EPA's Greenhouse Gas Reporting Program (GHGRP)**: Includes datasets `us_greenhouse_gas_emissions_direct_emitter_facilities.csv` and `us_greenhouse_gas_emission_direct_emitter_gas_type.csv`, detailing greenhouse gas emissions reported by facilities.
2. **EPA's Air Quality System (AQS)**: Contains `us_air_quality_measures.csv`, providing air quality measurements on a county level from approximately 4000 monitoring stations across the US.
3. **Population Estimates**: The dataset `PopulationEstimates.csv` provides population estimates and Federal Information Processing Standards (FIPS) codes for US counties in 2010.

## Methodology
1. **Data Cleaning and Wrangling**: Cleaned and merged the datasets to ensure consistency and usability. This included renaming columns for readability, filtering top air quality measures, and synchronizing datasets by common years (2010 and 2011) and states.
2. **Model Construction**: Developed two models:
  - Model 1: Predicted the industry type of facilities based on their gas emissions.
  - Model 2: Predicted county air quality levels based on the sum of gas emissions from facilities, population density, and major industry type.
3. **Analysis**: Conducted exploratory data analysis to identify trends and correlations between air quality, greenhouse gas emissions, and population density.

## Key Findings
- Industrial activities and population density significantly impact air quality.
- The models demonstrate the potential to predict air quality levels using data on greenhouse gas emissions and industrial facility types.
- The findings highlight the importance of targeting specific industrial sectors to mitigate air pollution.

## Conclusion
The models developed in this study offer a quantitative approach to understanding the relationship between industrial emissions, population density, and air quality. These insights can inform policy decisions aimed at reducing air pollution and protecting public health. Future work may involve refining these models with additional features and data to enhance their predictive accuracy.