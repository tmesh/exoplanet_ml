# Exoplanet mass and radius prediction

Chen and Kipping (2016) derived a linear mass-radius relationship for exoplanets (planets around stars other than the sun), however the relationship was derived following human selected break points in the data. The goal o fthis project is to take the updated exoplanet table of parameters (from the NASA exoplanet archive) and use machine learning to find a model to describe the mass-radius relationship of planets from the unstructured data alone, without hard-coded breakpoints. I used k-means clustering to find the data which are similar to each other and divided the data up into clusters.  I varied the number of clusters from 2 to 6. 
I broke the data up into training and testing data and used linear regression to fit a model to the data in each cluster. I used a metric (in this case, the Mean Absolute Error) to assess the accuracy of the model. 

Note: since the data are only from the NASA exoplanet archive, they do not include stars so the fourth category of bodies, on the right of this diagram "Stellar worlds" will not be included in this analysis.
