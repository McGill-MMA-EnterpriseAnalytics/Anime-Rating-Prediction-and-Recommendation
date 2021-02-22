# Anime-Rating-Prediction-and-Recommendation
With the vast content and products available online, customers/content users face a significant challenge to pick the right content or products. Same with customers, the content providers or online shops also surfer from getting exposure to the right customers. The recommendation system is critical and necessary to solve the needs of customers/content users and online shop/content providers. In other words, the recommendation system closes the gap of the demands from both ends and exposes the right content to the right audiences. 

The anime industry has experienced consecutive growth for more than 10 years, and its total worthiness had reached more than 24 billion US dollars in 2019. It has well established markets throughout the world, include Japan, China, North America and Europe. Given the current pandemic situation, demands on indoor entertainment activities/products has increased significantly, and it presents a great opportunity for the anime industry. However, the large number of existing animes sometimes makes people hard to decide what to watch, especially for those who don't usually spend their time on watching animes. Thus, an anime recommendation system could be implemented to solve this problem. 

In our UC, We're using a sample dataset to build a recommendation system to suggest user new animes and predicte a user rating for MyAnimeList, a privately held US company founded in 2006 that operates an online anime rating site. This would Help MyAnimeList to attract more users to their website and increase their users’ satisfaction level
<br> <br>
### Use Case/Problem Statement: 
    - One goal is to build a predictive model that estimates the user ratings on animes using supervised ML techiniques.
    - The other goal is to build recommendation systems with different algorithms(KNN, KMeans, and Pearson R correlation) and compare the recommendation results
### Objectives/Benefits: 
    - Prediction model on anime ratings could help the website better understand the preference of users 
    - Recommendation system could help users find animes of their interests faster, hence generate higher income for content providers
    - Increase user satisfaction level & site traffic
    - Increase advertising revenues 
### Proposed Solution: 
    - Build a predictive model to predict user ratings on animes 
    - Build a recommendation system that filters and recommends animes to users based on (predicted) ratings and similarities of animes 
### Desired Outcome:
    - The precentage error of the prediction system is below 20% (using MSE/MAPE for testing)
    - The recommendation system could generate a meaningful list of recommended animes for the users based on their inputs - anime names (using Surprise python package for testing)


# Data
The data is taken from Kaggle. It contains 73,516 users rating on 12,294 anime. <br>
https://www.kaggle.com/CooperUnion/anime-recommendations-database 

# Codes

Prediction system:
- https://github.com/McGill-MMA-EnterpriseAnalytics/Anime-Rating-Prediction-and-Recommendation/blob/main/Data_Preprocess_And_Prediction.ipynb

Recommendation system (models built by using KNN, K-Means Clustering, and Pearson R Correlation):
- https://github.com/McGill-MMA-EnterpriseAnalytics/Anime-Rating-Prediction-and-Recommendation/blob/main/Recommendation_System_with_Three_Algos_With_Evaluation.ipynb

# Presentation Slides
https://github.com/McGill-MMA-EnterpriseAnalytics/Anime-Rating-Prediction-and-Recommendation/blob/main/Anime-Rating-Prediction-and-Recommendation_Presentation.pptx
