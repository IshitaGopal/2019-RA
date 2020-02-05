# RA Work: Fall 2019 
## for Kevin Munger 

<ins>**Project 1 Goal**:</ins> To record the birth dates of representatives who have served congress and the year(s) in which they served for the time period between 1935-2019.

*Data used comes from* :

  1. https://theunitedstates.io/congress-legislators/legislators-current.json
  2. https://theunitedstates.io/congress-legislators/legislators-historical.json
  
*Implementation:*

Seperate out the senators. Extract the birth date of each representative from the Json and record it as a column. For each year between 1935-2019, create a column and fill in with a 0 or 1 to indicate if the representative served in congress in that year.

<ins>**Project 2 Goal**:</ins> Repeat the above task but this time for senators. 

<ins>**Project 3 Goal**:</ins> To record the age of all actors appearing in a film in a given year.

*Data used comes from :*

  1. https://www.kaggle.com/rounakbanik/the-movies-dataset#credits.csv
  2. https://www.kaggle.com/rounakbanik/the-movies-dataset#movies_metadata.csv
  3. https://datasets.imdbws.com/ 

*Implementation:*

Link the first dataset (link 1.) which contains the actors and actresses from each film with the 
second dataset that gives the fims's year of release. Using string matching, match the actor names
with the thrird dataset (link 3.). This will match actors with their birthyears.

