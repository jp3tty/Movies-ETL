# Movies-ETL
## Overview
This project creates an automated extract-transform-load (ETL) pipeline that takes in new movie data, performs the appropriate transformations, and loads the data into existing tables. The data for this project was sourced from a Wikipedia .json file and two .csv files from Kaggle.

## Process
The pipeline was written using Jupyter Notebooks to extract and transform raw data into Pandas dataframes. The data was then loaded into a SQL database (PostgreSQL) for a user to query.

The data was cleaned by removing missing or corrupted data, consolidating duplicate information, and using regular expressions to standardize some data forms.

## Results
The databases, labeled "movies" and "ratings" can be queried for a variety of information and the extract-transform-load function in the Jupyter Notebook is able to add new information as often as needed.

A count query on the Movie database reveals 6052 rows of data.
![Movie_table](https://github.com/jp3tty/Movies-ETL/blob/main/Images/Movies_table.PNG)

A count query on the Ratings database reveals 24,000,000 row of data.
![Ratings_table](https://github.com/jp3tty/Movies-ETL/blob/main/Images/Ratings_table.PNG)