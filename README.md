# A Movie Recommendation Engine

## Objective 
Build a content-based recommendation engine that helps Netflix identify similar movies to users based on movie characteristics.

## The Data 
* Contains metadata for 4,803 movies listed in TMDb movie database
* Consists of movies released on or before July 2017
* Information includes cast, crew, plot keywords, budget, revenue, posters, release dates, languages, production companies, countries, TMDb vote counts and vote averages 
* Downloaded from: https://www.kaggle.com/tmdb/tmdb-movie-metadata#tmdb_5000_movies.csv

## Feature Engineering 
* Categorical: Genres, Keywords, Cast, and Director (Multi-hot/one-hot encoding)
* Natural Language: Overview (TFIDF)
* Numeric: Popularity, Year, Runtime, Vote Count and Vote Average 

## Clustering 
* K-means 
* Hierarchical 
* GMM

## Dimensionality Reduction 
* PCA
* T-SNE
* UMAP

## Evaluation Matrices
* Similarity: Silhouette coefficeint 
* Consistency: Intersection over Union (IoU)

## Recommendation Engine 
* GMM 10-Cluster Solution 

## Summary 
* Used multiple clustering algorithms to unpack teh underlying pattern of movie data
* Grouped 4K+ movies into 10-15 clusters based on their characteristics 
* Evaluated algorithm performance from various perspectives 

## Future Work 
* Incorperate indivisual user rating data and build collaborative filtering system 

