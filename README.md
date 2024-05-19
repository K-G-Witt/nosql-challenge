# nosql-challenge
Data on restaurant establishments across the United Kingdom were analysed to explore hygiene ratings by location and Local Authority Area.


## Project Description:
Raw data has been saved as **establishments.json**, located within the **Resources** subfolder. 


## Installation and Run Instructions:
Executing the script provided in the **NoSQL_setup_starter.ipynb** file will load the **establishments.json** in to a MongoDB, update the database to include a new restaurant, named Penang Flavours, and convert data to the approprate formats for analysis. 

Executing the script provided in the **NoSQL_analysis_starter.ipynb** file, will output the following:
1. Restaurant establishments with a hygiene score of 20
2. Restaurant establishments in the London Local Authority with a RatingValue greater than or equal to 4
3. Top 5 restaurant establishments within 0.01 degrees of the newly added Penang Flavours restaurant with a RatingValue equal to 5
4. Number of restaurants with a hygiene score of 0 within each Local Authority Area

This script will also convert the above queries to Pandas DataFrames.
   

## Credits:
This code was compiled and written by me for the html scraping challenge class homework in the 2024 Data Analytics Boot Camp hosted by Monash University.
