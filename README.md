# CSCE 415/615 Machine Learning Project

## Data

This folder contains the project data. Because the files are too large for GitHub, they are stored on local machines and in the shared Google Drive.

- `data/raw/sas/`: original BRFSS SAS transport files as downloaded
- `data/raw/csv/`: CSV versions of the raw BRFSS data for use in Python
- `data/clean/`: cleaned datasets produced by the preprocessing notebooks

## Preprocessing

This folder contains scripts and notebooks used to convert and clean the BRFSS data.

- `sas2csv.R`: converts BRFSS `.XPT` files into CSV format
- `2018.ipynb`: loads the 2018 raw CSV, selects diabetes-related variables, removes invalid or missing values, recodes fields, renames columns, and saves the cleaned output to `data/clean/`

## References

- Original BRFSS-based repo by [Winston Larson](https://github.com/winstonlarson/brfss)
- CDC BRFSS annual data page: [BRFSS Annual Data](https://www.cdc.gov/brfss/annual_data/annual_data.htm)

## Notes

- This project currently includes preprocessing for the 2018 diabetes-related dataset.
- Additional BRFSS years were added beyond the years covered in the original upstream repo.