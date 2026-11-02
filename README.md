# Movie Rating Prediction with Linear Regression

I cleaned an IMDb India dataset from 15,509 films down to 5,659 usable rows, then used linear regression to predict ratings from year, votes, duration, genre and cast.

It scored an R² of 0.71, but that's probably flattering. I built the average rating features for genre and actors before splitting the data, so some test information leaked into training. That's the first thing I'd fix if I redid it.
