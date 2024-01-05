# Solar Power Optimization Project

## Project Overview

This project aims to optimize solar power generation by analyzing environmental factors that influence the efficiency of solar panels. A key focus is on the impact of precipitation on generated solar power. By understanding this relationship, we can better predict and optimize solar power generation under varying weather conditions.

## Data Sources

The analysis is based on two primary datasets:
- Solar power generation data (`solar-panel-data.csv`): Contains historical data on generated power and various environmental parameters. (https://www.kaggle.com/datasets/stucom/solar-energy-power-generation-dataset)
- Weather data from INMET (`inmet-weather2023.csv`): Provides detailed meteorological data, including precipitation measurements at various stations. (https://www.kaggle.com/datasets/gregoryoliveira/brazil-weather-information-by-inmet/data)

## Methodology

The approach involves several key steps:
1. **Data Preprocessing**: Cleaning and transforming data for analysis. This includes:
   - Filtering and renaming columns.
   - Handling missing values.
   - Converting precipitation measurements from millimeters to inches.

2. **Data Analysis and Visualization**: Exploring the relationship between total precipitation and solar power generation using scatter plots and statistical analysis.

3. **Predictive Modeling**: Implementing a Linear Regression model to predict generated power based on precipitation data. The model was trained on historical data and tested on new, unseen weather data.

4. **Model Application**: Applying the trained model to predict generated power for specific weather conditions, focusing on data from the INMET weather station 'A771 - São Paulo - Interlagos'.
