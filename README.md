# big-data-challenge
Exploring Amazon user review data and storing it in a database.

## Summary
In order to interact with the Amazon Review Data without storing it locally (due to large file sizes), Amazon Web Services' RDS software was utilized. On the RDS platform, two database instances were created to store each of the two datasets that were explored, the first of which contained user reviews of lawn and gardening products, and the second involving musical instruments. Using pgAdmin 4 to access PostgresQL, tables were created from the schema contained in the amazon.sql file. These tables were necessary in order to populate the review data into the requisite RDS database. The data was preprocessed and cleaned in each of the notebooks through Google Colab and stored in DataFrames. Once these DataFrames were created, each of the three tables were populated (in both database instances).
