# Movies_ETL
## Overview
Refactored code from module in order to help automate the process for ETL of movie data. This mostly involved creating a new function and then pulling the results into a dataframe. This information was then exported to SQL.
## Resources
- Software: PostgreSQL 12.11.1, pgAdmin 4, Jupyter Notebook
  - movies_metadata.csv
  - ratings.csv (NOT INCLUDED BECAUSE SIZE WAS TOO LARGE TO UPLOAD)
  - wikipedia-movies.json
 ## Summary
 For this we refactored our movie_data code in order to automatce the process of extraction, transforming and loading movie data for a hackathon. This will potentiallly allow additional data to be uploaded to SQL without overwiting old data in order to build up the database even more. We created three different notebooks that steadily increased the complexity of the code while allowing us to make sure that previous steps were accurate. The end results were as expected, except the movie_df was shorter by one row since I removed an outlier row from the wikipedia data before merging.
