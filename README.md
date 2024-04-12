# Deep-Learning-based-content-recommendation-system
**Dataset Link** - https://grouplens.org/datasets/movielens/latest/
**Python 3+ Dependencies** - pandas, nltk, sklearn, numpy, matplotlib, tensorflow, keras, jupyter-notebook

## Project Description
This project is a hybrid model of deep learning and bag of words technique for recommending movies. 
It consists of three parts:-
  - Popularity Based - Just a simple popularity based recommendation system used for testing
  - Bag of Words - Uses nltk stemmer and count vectorizer for prerocessing and cosine similarity for generaitng results
  - Deep Learning - Uses a tensorflow and keras defined model for generating recommendations

After getting the recommendations from the two models I use a point based metric to rank all the recommendations to give the best curated recommendations

Please comment out the following since these are local saves I used for this model:-
  - open search by ctrl + f and search `l = set()` and comment out the whole block
  - next search `for i in l:` and comment the whole cell
  - next search `seen = []` and comment the whlole cell
  - next search `model = tf.keras.models.load_model(r'C:\Users\user\Jupyter Files\Recommender System\Saves\deep_learning_recsys_v4.h5')` and comment the whole cell
  - next search `model.save(r'C:\Users\user\Jupyter Files\Recommender System\Saves\deep_learning_recsys_v4.h5')` and change the path to wherever you want to save the trained model or if you dont want to then comment this out as well
