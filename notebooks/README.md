# Scripts Directory

This folder contains Python code used to perform the main data processing and analytical steps of the project.

## Contents

The code in this directory perform the following tasks:

- Loading and cleaning raw datasets
- Converting and standardizing date formats
- Merging environmental and water quality data
- Identifying unsafe water events based on E. coli thresholds
- Aggregating statistics at the beach level
- Constructing a composite risk score
- Exporting results for visualization and reporting

## Key Processing Steps

1. Import spatial beach monitoring data
2. Import daily weather observations
3. Standardize date formats
4. Merge datasets based on sampling date
5. Create derived variables (month, year, unsafe event indicator)
6. Calculate risk metrics for each beach

## Output

The scripts generate summary datasets that are stored in the `outputs` directory and used for visualization and interpretation.

## Reproducibility

Running the main analysis script will reproduce the risk ranking results used in the project.
