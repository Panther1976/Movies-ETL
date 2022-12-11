# Movies-ETL

## Overview and Purpose of Project

This project was created to develop an automated pipeline that extracts, transforms and loads new data into exisiting tables. The code from the module was refractored to create one function that extracts data from Wikipedia, Kaggle metadata and MovieLens rating data, transforms the data and loads it to a PostgreSQL database.

### Deliverable 1: Converting the Wikipedia, Kaggle and MovieLens files

Wiki_movies_df:

<img width="387" alt="D1_wiki_df" src="https://user-images.githubusercontent.com/106631875/206935707-8e08a21f-1784-4b11-bb17-abfc4f3a72d0.png">

Kaggle_metadata DataFrame:

<img width="386" alt="D1_kaggle_df" src="https://user-images.githubusercontent.com/106631875/206935691-49c557bf-34cc-43c9-8373-afdf5cfa04b2.png">

MovieLens Ratings DataFrame:

<img width="163" alt="D1_ratings_df" src="https://user-images.githubusercontent.com/106631875/206935701-e79744ea-7574-44d3-9650-9d18213e9b0e.png">

### Deliverable 2: Extract and Transform the Wikipedia Data

Wiki_movies_df:

<img width="392" alt="D2_wiki_df" src="https://user-images.githubusercontent.com/106631875/206935807-861ae2aa-44a3-4953-bc1e-7ba4748a0274.png">

Wiki_movies_df Columns:

<img width="245" alt="D2_wiki_columns" src="https://user-images.githubusercontent.com/106631875/206935802-b4a922c0-1870-481d-b0ea-fcf8306b8682.png">

### Deliverable 3: Extract and Transform the Kaggle Data

Kaggle movies_with_ratings_df:

<img width="388" alt="D3_movies_w_ratings" src="https://user-images.githubusercontent.com/106631875/206935899-d6c9ea16-3571-4d42-b1a0-90bd87d7722c.png">

Movies_df:

<img width="388" alt="D3_movies_df" src="https://user-images.githubusercontent.com/106631875/206935929-36b60356-d2e5-48c2-8e7f-83645b2a0d4b.png">

### Deliverable 4: Create the Movie Database

Time Elapsed to Load Data to SQL:

<img width="368" alt="time_elapsed_to_sql" src="https://user-images.githubusercontent.com/106631875/206935996-631ead4d-f9cb-4e9e-8c5b-6b6c64e90256.png">

Movies_query:

<img width="155" alt="movies_query" src="https://user-images.githubusercontent.com/106631875/206936014-f24a0f2c-40e4-4a85-bbc7-bc20b2434bae.png">

Ratings_query:

<img width="165" alt="ratings_query" src="https://user-images.githubusercontent.com/106631875/206936019-80a868bb-fa73-45b0-9f8b-149a463637d9.png">
