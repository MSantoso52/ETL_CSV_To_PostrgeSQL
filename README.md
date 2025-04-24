# ETL_CSV_To_PostrgeSQL
ETL Process from CSV file as input into PostrgeSQL local database:
1. Extract csv file into pandas data frame
2. Transform the data frame -- remove duplicates, remove n/a, data type correction
3. Load python library for postgres connection & interaction
4. Load transform data into postgresql 
