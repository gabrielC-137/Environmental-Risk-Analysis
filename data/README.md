# Data Directory

This directory contains the raw datasets used for the analysis of recreational beach water quality in Toronto.

## Files

### Toronto Beach Water Quality (GeoJSON)

This dataset contains spatial locations of monitored beaches along with historical E. coli measurements collected during recreational water quality monitoring programs.

Key attributes include:
- Beach name
- Sample collection date
- E. coli concentration
- Geographic coordinates

### Toronto Daily Weather Data (CSV)

This dataset contains daily meteorological observations used to evaluate environmental drivers of water contamination.

Variables include:

- Date
- Mean daily temperature
- Precipitation
- Year
- Month

## Data Usage

The two datasets are temporally aligned using the sampling date of water quality measurements. Weather conditions for the corresponding dates are then merged to allow analysis of environmental factors associated with unsafe water events.
