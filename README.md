# Movie_Recommendation_Engine

The analysis explored the movie data from datalens (url: https://grouplens.org/datasets/movielens/).

A recommendations was created using singular value decomposition (SVD) to create representative latent features of the movies, and with the latent features, cosine similarity was used to generate predictions given user movie ratings.

Having completed the above, a recommendation dashboard app using plotly and dash was created and deployed to Heroku https://movie-dash-app.herokuapp.com/ (**Username**: data, **Password:** analyst, **Note** - the dashboard takes a few seconds to load and is optomized for a 13-inch desktop). The dashboard allows the user to rate three movies to recieve top 10 movie recommendations.

Anyone looking to explore and get a deeper look into Toronto's restaurants can use this app.

Methods Used
Descriptive Statistics - used for preliminary data exploration.
Singular Value Decomposition (SVD) - used to create 2 restaurant recommendation engines basis all standards or food standards.
Cosine Distances - used to measure similarities between latent features of restaurants.

## Results

Test Data results

## Dashboards

**Plotly & Dash Dashboard**:

![](ReadMe_Images/Dash2.png)

**Tableau Dashboard**:

![](ReadMe_Images/Dash1.png)
