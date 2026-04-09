# Toronto Environmental Risk Analysis

## Project Overview

This project develops a data-driven analytical framework to identify and prioritize recreational beaches in Toronto that are more likely to become unsafe due to elevated E. coli levels. By integrating historical water quality measurements with environmental conditions such as temperature and precipitation, the analysis supports evidence-based monitoring strategies.

The objective is to help decision-makers allocate monitoring resources more efficiently and identify environmental drivers associated with unsafe recreational water conditions.

## Key Research Questions

- Which beaches show the highest historical risk of unsafe water conditions?
- Under what environmental conditions are unsafe events more likely to occur?
- How can monitoring efforts be prioritized across sites?

## Methodology

The analytical framework consists of the following steps:

1. Data ingestion and cleaning
2. Temporal alignment of water quality and weather datasets
3. Identification of unsafe events using the standard E. coli threshold (>100)
4. Aggregation of beach-level statistics
5. Construction of a composite risk score
6. Spatial visualization using GIS tools

The resulting framework provides a transparent and reproducible method for ranking beaches by risk level.

## Technologies Used

- Python
- Pandas
- GeoPandas
- NumPy
- QGIS
