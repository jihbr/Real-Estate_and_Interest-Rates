# SIADS Milestone I GITHUB Repository
This is a repository for the first capstone project at the Master of Applied Data Science program at the University of Michigan. In this project, we are doing an exploratory analysis regarding the Federal Funds Effective Rate and other public data variables relevant to the housing market (see datasets below for description of each). 

There is one directory within the repository, **src**, and a subdirectory called **src/data**.

## src
Correlation Analysis.ipynb
- This notebook performs a correlation analysis on all the fields from a merged dataframe (full_df.csv) of all the datasets.
Distribution Analysis.ipynb
- This notebook performs summary statistics on a merged dataframe (full_df.csv) of all the datasets. Then it performs a distribution analysis on all fields, excluding year.
Income Analysis.ipynb
- This notebook performs a quick analysis on median income in 2022 dollars per year-month and the proportion of home owners faceted by region.
primary_&_secondary_notebook.ipynb
- This notebook merges the primary_df.csv and secondary_df.csv files into full_df.csv.
primary_df_notebook.ipynb
- This notebook creates the primary_df.csv file by merging all the datasets within ./data/FRED.
secondary_df_notebook.ipynb
- This ntoebook creates the secondary_df.csv file by merging all the datasets within ./data/HIT & ./data/MHS.
## src/data
This subdirectory of src contains all of the datasets organized by category.
### FRED
This contains datasets from the website https://fred.stlouisfed.org.
- CPIAUCSL.xls
  - City average of consumer price index starting in 1947.
  - Source: https://fred.stlouisfed.org/series/CPIAUCSL 
- FEDFUNDS.xls
  - Federal funds effective rate starting in 1954.
  - Source: https://fred.stlouisfed.org/series/FEDFUNDS
- MORTGAGE30US.xls
  - Average 30 year fixed mortgage rate starting in 1971.
  - Source: https://fred.stlouisfed.org/series/MORTGAGE30US
- RSAHORUSQ156S.xls
  - Percentage of households lived in by the owner (as opposed to rented).
  - Source: https://fred.stlouisfed.org/series/RSAHORUSQ156S
### HIT
This contains a dataset from the https://www.census.gov/data/tables/time-series/econ/mhs
- h06ar.xlsx
  - Median and mean income by region for all races.
  - Source: https://www2.census.gov/programs-surveys/cps/tables/time-series/historical-income-households/h06ar.xlsx
### MHS
This contains a dataset from the https://www.census.gov/data/tables/time-series/demo/income-poverty/historical-income-households.html
- mhstabavgsls2014-2022.xlsx
  - This dataset was renamed to include the start and stop year.
  - Average home sales price organized by home size and region.
  - Source: https://www2.census.gov/programs-surveys/mhs/tables/time-series/mhstabavgsls.xlsx
