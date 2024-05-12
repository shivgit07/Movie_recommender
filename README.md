# Movie_recommender
This project implements a content-based movie recommendation system that suggests similar movies to users based on the content (e.g., genres, plot keywords) of movies they have rated or liked. The system utilizes movie metadata and cosine similarity scores to identify movies with similar characteristics.
</br>
</br>

The `Movie_recommendation_system.ipynb` file contains following 3 tasks: </br>
**Task 1: Create a Recommendation system**</br>
* Parsed `movies.csv` and created a c**ontent based recommendation** system using TfidfVectorizer and cosine_similarity from sklearn</br>
* Parsed `ratings.csv` and creatde a **collaborative filtering** based recommendation system using Surprise or Librecommender 

**Task 2: Prediction**</br>
Generated 10 recommendations using: </br>
* content-based system using the user's historical movie preferences. </br>
* collaborative filtering system using user’s ratings

**Task 3: Evaluation**</br>
Provide Metrics to judge recommendation systems 
</br>
</br>
**Resources:** 
* `Dataset - https://files.grouplens.org/datasets/movielens/ml-25m.zip`
* `Surprise documentation - https://surprise.readthedocs.io/en/stable/index.html` 
* `Librecommender - https://pypi.org/project/LibRecommender/0.0.1/`
