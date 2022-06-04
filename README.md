# Movies-ETL

## Purpose
To create an automated pipeline that takes in new data, performs the appropriate transformations, and loads the data into existing tables.To create one function that takes in the three files—Wikipedia data, Kaggle metadata, and the MovieLens rating data—and performs the ETL process by adding the data to a PostgreSQL database.

### Deliverable 1: Write an ETL Function to Read Three Data Files.
A function that reads in the three data files and creates three separate DataFrames.

### Deliverable 2: Extract and Transform the Wikipedia Data.
To extract and transform the Wikipedia data so it can be merged with the Kaggle metadata. While extracting the IMDb IDs using a regular expression string and dropping duplicates, use a try-except block to catch errors.

### Deliverable 3: Extract and Transform the Kaggle Data.
To extract and transform the Kaggle metadata and MovieLens rating data, then convert the transformed data into separate DataFrames. Then merge the Kaggle metadata DataFrame with the Wikipedia movies DataFrame to create the movies_df DataFrame. Finally merge the MovieLens rating data DataFrame with the movies_df DataFrame to create the movies_with_ratings_df.

### Deliverable 4: Create the Movie Database.
To add the movies_df DataFrame and MovieLens rating CSV data to a SQL database.
![](Resources/movies_query.png)
![](Resources/ratings_query.png)
