# Movie_Project

## Movie Search Engine
Using the D3 JavaScript library, we created a dashboard that allows users to search for a movie title & query the OMDB API & return the following details:  the plot, release date, director, rating, genre, runtime, imdb rating, production company, & poster.

![alt text](https://github.com/chrisholyoake/Movie_Project/blob/master/search.png
 "Movie Search Engine")
 
## Visualizations 
We then compiled a list of the top rated movies of all time and looked at the following:
* Is there a correlation between a movie’s rating (G, PG, PG-13, R, etc.) and its Metacritic score.
* What are the most common movie genres among the top 250 movies of all time?

To do this, we scraped a list of 250 top rated movies from IMDB using Beautiful Soup, then pulled information on each movie from the OMDB API and stored the results in SQLite.

We then built a front-end webpage using a Flask server, HTML/CSS, & JavaScript.

Using the Plotly and Highchart JavaScript libraries, we visualized both sets of data.

![alt text]( https://github.com/chrisholyoake/Movie_Project/blob/master/visualizations.png
 "Movie Trend Visualizations")
