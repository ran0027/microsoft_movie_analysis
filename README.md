Picture?

# Microsoft Breaks Into the Film Industry

Author: Rebecca Neel

## Overview

This project looks for film characteristics which are correlated to higher revenues. By examining the worldwide gross of films of various genres, released at various times of year and produced by groups of production companies, it becomes clear that certain types of films have earned higher revenues historically than others. Additionally, certain production companies already dominate the film industry. Since partnering with one ore more production companies is already an accepted practice in the film industry, we have analyzed the most successful production companies to determine possible suitable partners for Microsoft in a joint venture. Microsoft can use this information to specify the genre and release time of their first film and to determine an appropriate production company with which to partner, if a joint venture is desired, to maximize revenue and the reach of their film.

## Business Problem

Microsoft may be able to maximize revenue earned on films produced by choosing a genre of film that has proven popular and timing their releases to correspond to peaks in movie-going, to generate buzz around the film and garner the highest revenue possible in ticket sales. Additionally, having knowledge of established production companies which have been successful gives Microsoft the opportunity to look for a partner or partners who can lend their expertise to the film-making process, and, in some cases, the distribution process as well, to increase the likelihood of making a film which is a popular success.

## Data

We used data from the IMDB database, The Movie Database, The Numbers and Box Office Mojo. Data was organized by film and provided a variety of information about each film in addition to movie release date and movie title. Data was linked via the film title and release year, and ultimately included production budget, worldwide gross, genre, production companie(s) involved in the production and release date (month/day/year). Runtime and IMDB rating were also originally included, but were dropped after being shown to be un-correlated with movie gross.

## Methods

This project uses descriptive analysis. Film data was grouped by a specific field (genre, release time band or production company involved in its production), then aggregate data was used to determine the groups of films which were most successful in that context.

For release time band, each movie was assigned a category: early, mid or late in a particular month. So there were 36 total release time categories.

In the case of production companies specifically, we created a "market share" metric which approximates the market share of each production company in the film industry.

## Results

Action/Adventure/Science-Fiction films were shown to have grossed the highest amount (total) of all genres over time. In fact, Action/Adventure films with a Science-Fiction element have grossed over 3 times as much as Action/Adventure films with a comedic element or a drama element. Over 75% of films in the Action/Adventure/Sci-Fi genre bring in revenue that is greater than the average production budget for a film in this genre. There are some large outliers, which are relatively recent Marvel films.

Movies released in mid-December have grossed the highest amount of all release-times overall. Movies released in late-May have a higher average gross per film, but not as many films are released at this time of year.

Only 16 of 1429 production companies in the data set have more than 1% of the market share in the film industry. Together, these 16 companies have about 35% of the market share, so there are clearly many production companies that have a relatively small share in the market. *add more here*

## Conclusions

This analysis leads to three recommendations for maximizing revenue on Microsoft's first film released:

- Produce an Action / Adventure / Science-Fiction film. These are massively popular, thus helping to establish Microsoft as a major player in the entertainment industry in the public eye, leading to maximum current and future revenue for the studio.
- Schedule the release of your film(s) for mid-December or late-May, to ensure the maximum gross for your film(s) at the box office.
- Consider reaching out to one of the 16 dominant production companies in the industry to make a contract to co-produce one or more films.

## Next Steps

- Better understanding of current trends in the movie industry versus long-standing successes. Grouping data by time as well as genre, or time as well as release-date, might provide some insight into recent changes in the success of certain types of films, leading to a better sense of trends that might develop next.
- Increasing sample size to verify results and look for more information about what makes a film successful within a genre. We only had data on 69 movies in the most successful genre, Action / Adventure / Science-Fiction movies. Overall, genre was missing for 2/3 of the films for which we had financial data. Because genre is relatively easy to find, and financial data is not, it could be worth adding the genre manually to the films in our dataset, to triple our sample size and try to identify differences in keywords between films in the bottom and top quartiles in this genre. (Though Action / Adventure / Science-Fiction films grossed the most overall, there was at least one film in this genre which earned no revenue, while others earned billions. Determining what makes a film fall flat or rise to the top in this genre would provide Microsoft with data-driven insights to guide the production of a film in this genre more closely.)

## For More Information

See the full analysis in the Jupyter Notebook or review this presentation. *add hyperlinks*

For additional information, contact Rebecca Neel at rebecc.clark@gmail.com.

Picture?

## Repository Structure

Picture