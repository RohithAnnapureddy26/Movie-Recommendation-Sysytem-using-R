# Movie-Recommendation-Sysytem-using-R

## Introduction:
The "Movie Recommendation System using R" project aims to create a personalized recommendation engine for suggesting movies to users based on their preferences and viewing behavior. This project utilizes the MovieLens dataset, which is widely recognized for its comprehensive information on movie ratings.

## Demo:
Navigate to the directory "Hybrid Model/End Deployment," ensure all necessary files are present locally, and execute the "deployment_test.Rmd" file.

## Dataset Overview:
The MovieLens 20M dataset offered a useful and varied dataset for developing and evaluating movie recommendation systems. It showcased user interactions with movies through ratings and tags, making it an invaluable tool for both research and practical implementations. Its structured format and comprehensive coverage of user preferences provided significant insights into recommendation system design.
**Dataset**: https://www.kaggle.com/datasets/grouplens/movielens-20m-dataset

## Methodology:
https://drive.google.com/file/d/1t1SGPx1AcvTdz9g9Hab2q_iM6seGojb7/view?usp=sharing

## Tech stack used:
- R
- Shiny for deployment

## Repository Structure:
### Content Based Filtering:
**Content_based_filtering.Rmd**: The working code for content based filtering using nearest neighbors approach on the merged dataset.

### Data Preprocessing:
**data preprocessing_DM.Rmd**: Data Preprocessing steps and merging of movies.csv and rating.csv for content based filtering.

### Hybrid Model-
End Deployment
1. clustered_data.csv- Data after applying KMeans.
2. deployment_test.Rmd- Deployment script to run the shiny app.
3. kmeans_model.rds, merged_data_with_clusters.rds and clustering_features_scaled.rds are their erspective weights.
Training and Execution
1. Hybrid.Rmd- Working for performing data preprocessing, KMeans and Nearest neighbors approach on the merged dataset.


Item Based CF
1. Untitled.Rmd- Working code using Cosine similarity as an item based filtering using the merged dataset.

User Based Filtering
1. user_based_cf.Rmd- Code on using KMeans clustering on user specific data after merging on movies.csv and rating.csv.