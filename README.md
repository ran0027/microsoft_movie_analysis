![Picture of Movie Tickets](Images/ticket-image.jpg)

# Microsoft Breaks Into the Film Industry

Author: Rebecca Neel

## Overview

This project looks for film characteristics which are correlated to higher average revenue. Grouping film data by genre and release time reveals that certain choices of these characteristics correspond to higher average revenue. Microsoft can use this information to determine what type of film to produce, and when to release it, to maximize revenue.

## Business Problem

Microsoft may be able to maximize revenue earned on films produced by choosing a genre of film that has proven popular and timing their releases to correspond to peaks in movie-going, to generate buzz around the film and garner the highest revenue possible in ticket sales.

Additionally, within the most popular genre of film, there is no evidence that spending significantly above the average production budget correlates with higher revenue. We recommend that Microsoft spend no more than the average on producing a film in this genre to maximize profit earned.

## Data

We used data from the IMDB database, The Movie Database, The Numbers and Box Office Mojo. Data was organized by film and provided a variety of information about each film in addition to movie release date and movie title.

Data was linked via the film title and release year, and ultimately included production budget, worldwide gross, genre, and release date (month/day/year). Runtime and IMDB rating were also originally included, but were dropped after being shown to be un-correlated with movie gross.

## Methods

This project uses descriptive analysis. Film data was grouped by a specific field (genre, release time band), then aggregate data was used to determine the groups of films which were most successful in that context.

For release time band, each movie was assigned a category: early, mid or late in a particular month. So there were 36 total release time categories.

Genres were given as multi-genre categories: e.g. "Action Adventure Animation". These multi-genre categories were preserved.


## Results

Action/Adventure/Science-Fiction films were shown to have the highest average gross of all genres for which we had a sufficient number of films in the dataset from which to draw conclusions.

Roughly 96% of films in the Action/Adventure/Sci-Fi genre break even, and the average film in this genre grosses nearly $600 million. The average production buget is about $175 million. There was a weak moderate positive correlation between production budget and worldwide gross (about 50%.)

Movies released in late-May have the highest average gross, followed closely by movies released in early July and mid-December.

## Conclusion

This analysis leads to three recommendations for maximizing revenue on Microsoft's first film released:

- Produce an Action / Adventure / Science-Fiction film. This type of film generates the most revenue on average, which is good for the company in and of itself, and also implies a certain amount of popularity which could be leveraged to produce a franchise based on the movie and generate further revenue.
- Spend no more than $175 to $200 million on production. The average gross on a film in this genre is about $525 million. About 50% of films make even more than this. (Side note: the mean and median worldwide gross are very similar, as you likely can infer.) While there is always a possibility of producing a film in the lower 50%, you have at least a 50% chance of making a 100% return or more.
- Schedule the release of your film(s) for late-May, mid-December or early July to ensure the maximum gross for your film(s) at the box office.

## Next Steps

- Better understanding of **current** trends in the movie industry versus long-standing successes. Grouping data by release year as well as genre, or release year as well as the time of year of the release, might provide some insight into recent changes in the success of certain types of films, leading to a better sense of trends that might develop next.

- Increasing sample size to verify results and look for more information about what makes a film successful within a genre. We only had data on 69 movies in the most successful genre. An analysis of keywords for movies in the bottom and top quartiles by total gross in this genre was inconclusive due to small sample size. We can potentially triple the size of our data set by adding genre information to films with financials which are missing genre.

- Ultimately, though Action / Adventure / Science-Fiction films grossed the most overall, there was at least one film in this genre which earned no revenue, while others earned billions. Determining what makes a film fall flat or rise to the top within the most popular genre(s) would provide Microsoft with data-driven insights to guide the production of a film more closely.

## For More Information

See the full analysis in this [Jupyter Notebook](./Presentation.ipynb) or review the [Google Slides presentation](./presentation.ppt).

For additional information, contact Rebecca Neel at rebecc.clark@gmail.com.

## Repository Structure

Picture