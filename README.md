# ETL-Project

## Background
This was a collaborative project in a case study of Extracting, Transforming and Loading data. 

We obtained four separate datasets from three sources: COVID-19 Vaccinations by U.S. State from Kaggle, U.S. Population by State from the USDA, U.S. Poverty Data by State rom the USDA and COVID-19 Cases by State from Worldometers.

Each dataset was extracted from the appropriate website by web scraping or downloading the csv file. Data transformation was completed using Python and Pandas within a jupyter notebook. The datasets were cleaned, columns and rows of interest selected, and filtered appropriately with the goal of being able to easily join the tables by location (U.S. state). Schema was developed for each table in Postgres SQL and tables were loaded into a SQL database using Python and Pandas.