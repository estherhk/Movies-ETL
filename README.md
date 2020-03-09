# Movies-ETL

## Project Overview
AmazingPrime Video requested an algorithm to predict the popular low budget films to buy the rights to stream their movies.  A dataset it created from two data sources using Extract-Transform-Load (ETL) into a SQL table.

## Resources
1. Data Source:
- movies_metadata.csv
- ratings.csv

2. Software:
- Jupyter Notebook
- pgADMIN

## ETL
- Extract: Extracted the data from movies_metadata.cvs and ratings.csv to create one dataset
- Transform: Transformed the information to so duplicates wouldn't appear and information that is not correct or irrelevant to the specific data it should pertain to
- Load: Load data into the existing table 

## Assumptions
From loading to PostgreSQL, five assumptions can be considered:

1) Minions (imdb_id:tt293640) had the highest popularity of 547.488298. 
2) Falling From Grace (imdb_id: tt0104225) had the lowest popularity score of 0.000001.
3) Avator (imdb_id:tt0499549) had the highest revenue(that's available) of $2,787,965,087.
4) Washington Squar (imdb_id: tt0120481) had the lowest revenue(that's available) or $1.
5) Pirates of the Caribbean: On Stranger Tides(imdb_id: tt1298650) had the highest budget of $380,000,000 ending with a revenue of $1,045,713,802.  This shows that there was a profit of $665,713,802.  

## Summary 
With the new dataset that includes both movies_metatdata.csv and ratings.csv, an algorithm would be created to help AmazingPrime to select which movies they would like to buy the rights to for their streaming service.  The dataset includes revenue, budget, and popularity, which would be major factors to determine which are the low budget films that made a substantial profit.  


