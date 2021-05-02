# Movies-ETL
## Overview
We were tasked with gathering movie data, along with moving rating data, and combine all to form an sql database to be used for a hackathon for Amazing Prime

## Results
 - Using a wikipedia JSON file, I cleaned up the data using the ETL method and created a movies dataframe
 - Downloaded data from Kaggle in the form of a csv. Cleaned all data and merged into the movies dataframe
 - Obtained a very large csv file of movie ratings data. Cleaned the data and merged into the movies dataframe
 - An SQL database was created with a Movies table and a ratings table
 - An automated pipline was created to automatically update the database with new movie data by performing the ETL process and adding the data to a PostgreSQL database
 
## Summary
An SQL database was successfully created using the data from all sources. The query results for the movies and ratings table are included in the Resources table