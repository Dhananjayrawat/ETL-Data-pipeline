# ETL-Data-pipeline

Data pipeline built to automate the flow of data from different sources into an analysis-ready MySQL database. 

What it does : 

1. Extract - pulls the data from csv local file and mysql database using oops . 
2. Transform - automatically cleans the messy data columns names (lowercasing , trimming and formatting)  and handles missing values using strategies like FFill, BFill, or Targeted Dropping. 
3. Loads- uses sqlalchemy to create table and load data also uses sqlalchemyerror to catch any database related errors

