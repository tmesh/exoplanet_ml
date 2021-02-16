# Exoplanet mass and radius prediction

In this notebook, I aim to take data from the NASA exoplanet archive and search for the mass-radius relation from the unstructed data alone, without hardcoded breakpoints. I use k-means clustering with varying k (number of clusters) from 2 to 6. I divide the data into training and testing data and perform linear regression on those points. I assess the accuracy of the model using the Mean Absolute Error (MAE).

Note: since the data are only from the NASA exoplanet archive, they do not include stars so the fourth category of bodies, on the right of this diagram "Stellar worlds" will not be included in this analysis.
