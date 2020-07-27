## Goals
To write a python function that takes in the wikipedia, kaggle, and ratings data and cleans it then uploads the dataframes to sequel.

## Findings
we get a list of 7033 rows of movies, although not all of them have values for each column.

## Assumptions
When cleaning the data some assumptions are made to eliminate bad data in the sets.
1. There are no other languages then the ones listed in our code in the data set that also have an alternate title.
2. There won't be any other numerical data in the kaggle data that needs to be converted.
3. The wiki data and kaggle metadata will be small enough files that they can be loaded all at once, and won't require batches, like the ratings data. 
4. The kaggle ids and the ratings movies ids are a match and for the same movie.
5. There won't be any other columns in the data set that are supposed to be monetary data outside of box office (revenue) and budget, that need to parsed and cleaned and made into a uniform manne
