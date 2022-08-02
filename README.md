# Movies-ETL
## Overview
Amazing Prime loves the dataset and wants to keep it updated on a daily basis. Create an automated pipeline that takes in new data, performs the appropriate transformations, and loads the data into existing tables. Refactor the code from this module to create one function that takes in the three files—Wikipedia data, Kaggle metadata, and the MovieLens rating data—and performs the ETL process by adding the data to a PostgreSQL database.
## Deliverable 1
Using knowledge of Python, Pandas, the ETL process, and code refactoring, write a function that reads in the three data files and creates three separate DataFrames.
## Deliverable 2
Using knowledge of Python, Pandas, the ETL process, and code refactoring, extract and transform the Wikipedia data so you can merge it with the Kaggle metadata. While extracting the IMDb IDs using a regular expression string and dropping duplicates, use a try-except block to catch errors.
## Deliverable 3
Using knowledge of Python, Pandas, the ETL process, and code refactoring, extract and transform the Kaggle metadata and MovieLens rating data, then convert the transformed data into separate DataFrames. Then, merge the Kaggle metadata DataFrame with the Wikipedia movies DataFrame to create the movies_df DataFrame. Finally, merge the MovieLens rating data DataFrame with the movies_df DataFrame to create the movies_with_ratings_df.
## Deliverable 4
Use knowledge of Python, Pandas, the ETL process, code refactoring, and PostgreSQL to add the movies_df DataFrame and MovieLens rating CSV data to a SQL database.
![movies_query](https://user-images.githubusercontent.com/101649525/182282334-55734d9e-d70f-4205-a06d-b273fde0b8b2.png)

<img width="708" alt="ratings_query" src="https://user-images.githubusercontent.com/101649525/182282352-d4b897e1-4760-4817-aaf8-5fef2854817d.png">
