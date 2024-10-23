# Foreign Residents Spatial Statistics 2022

This repository contains code for preprocessing and analyzing foreign resident statistics in South Korea at the administrative district level (읍면동).

## Data Preprocessing
The Jupyter notebook `데이터전처리(총조사shp과 행안부 외국인주민csv 조인).ipynb` performs the following tasks:
1. Processes foreign resident population data from CSV
2. Joins the data with administrative boundary shapefile
3. Handles data cleaning and standardization
4. Exports processed data in both CSV and Shapefile formats

## Required Libraries
- pandas
- geopandas

## Input Data (not included in repository)
- 2022년 외국인인구.csv
- 20224Q읍면동경계_2022_총조사총인구.shp

## Output Files
- processed_foreign_population_2022.csv
- 20224Q읍면동경계_2022_총조사총인구_외국인인구.csv
- 20224Q읍면동경계_2022_총조사총인구_외국인인구.shp
- unmatched_results.txt