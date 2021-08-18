# Module8-Challenge: Movies-ETL

## Overview
This project needs to create an automated pipeline that takes in new data, performs the appropriate transformations, and loads the data into existing tables. And it is also required to refactor the code from this module to create one function that takes in the three files—Wikipedia data, Kaggle metadata, and the MovieLens rating data—and performs the ETL process by adding the data to a PostgreSQL database.

## Dataset
The rating.csv is too big to upload to github. Fortunately, all the dataset comes from the [website](https://www.kaggle.com/rounakbanik/the-movies-dataset).

## ETL_function_test.ipynb
 - Data is extracted from the website in JSON and CSV formats.
 - Data is transformed into Pandas data frames.
 - JSON file needs to load file first and then transform into data frame.

## ETL_clean_wiki_movies.ipynb
 - Python list comprehensions.
 - apply() and map() methods in combination with lambda functions.

## ETL_clean_kaggle_data.ipynb
 - Changing datatypes, using methods pd.to_numeric, astype() and python comparison operators for Boolean types.
 - Filling missing values and filtering unwanted columns.
 - Merging data frames using pd_merge method.

## ETL_create_database.ipynb
 - removing return line at the bottom of the function and adding the line to connect PostgreSQL database, then adding the movies_df DataFrame to a SQL database.
 - Using qurey tools to count the rows of table ratings and movie_data in PostgreSQL and saving the output as PNG.

