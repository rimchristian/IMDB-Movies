![Forks](https://img.shields.io/badge/forks-44-blue)
![Stars](https://img.shields.io/badge/stars-13-yellow)

# Movie Recommendations Report 
Main goal of this analysis is recommending what makes a movie successful and recommendations to the stakeholders on how to make a successful movie.  I will be creating a MySQL database to explore the data after extracting API data from the IMDB movie dataset. 

# File Import 
These are the files I will be exploring and filtering. 
1. importing the data from 'title.basics.tsv.gz'
    basics_url="https://datasets.imdbws.com/title.basics.tsv.gz"
 
2. importing the data from 'title.akas.tsv.gz'
    akas_url = 'https://datasets.imdbws.com/title.akas.tsv.gz'
   
3. importing the data from 'title.ratings.tsv.gz'
   ratings_url = 'https://datasets.imdbws.com/title.ratings.tsv.gz'
 

 
 
 # These are the steps of creating the full Movie Project. 
 
#### Part 1: Downloaded the above files from the IMDB movie data set and filtered out the subset of moves requested by the stakeholder. 
**Specifications**
- Excluded any movies with missing values for genres or runtime. 
- Included any full-length movies 
- Included any fictional movies (Took out all of the documentary film) 
- Included movies that was released from 2000 - 2021
- Included only US Movies

#### Part 2: Used APIs to extract box office revenue and profit data to add to my dataset and performed exploratory data analysis. 
**Specifications**
After extracting the data, I answered the following questions:
1. How many movies had at least some valid financial information (values > 0 for budget OR revenue)?
2. How many movies are there in each of the certification categories (G/PG/PG-13/R)?
3. What is the average revenue per certification category?
4. What is the average budget per certification category?

#### Part 3: Constructed and exported a MySQL database using the data. 
#### Part 4: Applied hypothesis testing to explore what makes a movie successful. (A/B Testing)



 
 
