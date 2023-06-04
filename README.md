# nosql-challenge
This is the repo for Assignment #12 -  No SQL Databases.

This repo contains a folder named EatSafe_Love. Inside of it, there are two jupyter notebook files. In NoSQL_setup_starter.ipynb there are instructions about importing data, creating a MongoDB database, cleaning and updating it. In NoSQL_analysis_starter.ipynb, there is the code used for answering the main questions "Eat Safe, Love" magazine asked:
1: Which establishments have a bad hygiene score (equal to 20)?
2: Which establishments in London have a Rating Value greater than or equal to 4?
3: What are the top 5 establishments with a Rating Value of 5, sorted by best hygiene score, nearest to the new restaurant, "Penang Flavours"?
4: How many establishments in each Local Authority area have a hygiene score of 0? Results show the top ten Local Authority Areas.

Resources folder contains the JSON source file named "establishments" used to import the data. 

References
UK Food Standards Agency (2022). UK food hygiene rating data API. https://ratings.food.gov.uk/open-data/en-GB. Contains public sector information licensed under the Open Government Licence v3.0.
Accessed Sept 9, 2022 and Sept 12, 2022 with the establishment settings as follows: longitude=51.5072, latitude=-0.1276, maxdistancelimit=4567, pagesize=10000, sortoptionkey=distance, pagenumber=(1,2,3,4,5,6,7,8).