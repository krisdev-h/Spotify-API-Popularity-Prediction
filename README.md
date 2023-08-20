# Spotify-API-Popularity-Prediction

## Abstract 
My Spotify API Popularity Prediction Project presents the results and findings 
of predicting song track popularity using a variety of regression models: linear
regression, k-nearest neighbors, elastic net, polynomial regression, random
forest, gradient-boosted trees, and pruned decision tree. Utilizing `rmse` or
root mean square error metrics to choose the best fitting model, as the lowest 
`rmse` indicates the closest predictions to actual observations founded on 
Euclidean distance. We eventually found that the elastic net model produces our 
lowest `rmse` of 4.23, and although our testing `rmse` was a bit lower than our 
training `rmse`, elastic net maintains its status as a very good fit as our model 
predictions were only on average around 4 values off from the actual observations.
Next time, a larger train-test split and more observations could help with 
decreasing our training `rmse`. 

**Please Reference our HTML Final Report for more Details**
