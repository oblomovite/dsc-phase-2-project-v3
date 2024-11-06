# Overview

The goal of this analysis is to provide insights to a business stakeholder who is interested in creating a new movie studio. The stakeholder has no experience in creating movies and is looking for guidance on what types of films are currently doing the best at the box office. The analysis will focus on the consolidated dataset that was prepared for this project. The dataset includes information on the box office performance of movies, as well as ratings from various sources. The analysis will focus on the return on investment (ROI) and average rating for each movie. The analysis will provide three concrete business recommendations based on the findings.

## Structure

The project directory is structured as follows:

```bash
├── data
│   ├── bom.movie_gross.csv.gz
│   ├── im.db
│   ├── rt.movie_info.csv.gz
│   ├── rt.reviews.csv.gz
│   ├── tmdb.movies.csv.gz
│   ├── tn.movie_budgets.csv.gz
│   └── derrived_data.csv
├── images
├── .gitignore
├── README.md
├── presentation.pdf
├── project_proposal.md
└── student.ipynb
```

# Business Understanding

The key business questions that will be addressed in this analysis are:

- What types of films are currently doing the best at the box office?
- What is the relationship between the return on investment (ROI) and the average rating for movies?
- What are the top genres by ROI and average rating?

These findings will be used to provide actionable insights to the head of the new movie studio to help decide what type of films to create.

# Data Understanding and Analysis

## Source of Data

The data for this analysis was sourced from the following websites and is available in the `data` directory:

- [Box Office Mojo](https://www.boxofficemojo.com/)
- [IMDB](https://www.imdb.com/)
- [Rotten Tomatoes](https://www.rottentomatoes.com/)
- [TheMovieDB](https://www.themoviedb.org/)
- [The Numbers](https://www.the-numbers.com/)

## Description of Data

The consolidated dataset includes the following columns, these will be the key factors used in the analysis:

- 'rating': the average rating for each movie
- 'domestic_gross': the domestic gross revenue for each movie
- 'worldwide_gross': the worldwide gross revenue for each movie
- 'production_budget': the production budget for each movie
- 'genres': the genres for each movie
- 'roi': the return on investment for each movie

## Visualizations

# Conclusion

- Summary of Conclusions
