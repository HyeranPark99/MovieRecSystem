# MovieRecSystem

This project is to build a movie recommendation system using data from Kaggle.
The competition is provided by BTT AI X GOOGLE.

The datasets include keywords, metadata, movie IDs, and user IDs. 
Our group used collaborative filtering using cosine similarity, and additionally, we used content-based filtering with keywords and metadata datasets.
With the combined two methods, when the user ID and movie ID are given, this algorithm predicts the rating of the movie.

I used scikit-learn and surprise to implement the algorithm. The evaluation is scored on RMSE.

## :bulb: How to run 

- Download the dataset and locate the path to the datasets. 
- Change the string after pd.read_csv to your path 


## :scroll: Result 
- With the hybrid method, RMSE score was 0.2003. 
- When we only using collaborative filtering with cosign similiarity and tunig hyper parameters, the best score was 0.18.

