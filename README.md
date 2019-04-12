# NLP notebooks
Various approaches to NLP problems using Keras and TensorFlow. 

1. [Sentiment analysis of IMDB reviews] (imdb_reviews.ipynb)
 IMDB dataset contains labeled (25k for positive and 25k for negative) and unsupervised (50k) reviews.
 Models used to predict a sentiment:
 - word embedding dataset GloVe. Prediction accuracy ~ 54%
 - LSTM model. Prediction accuracy ~  53%
LSTM model should be fine-tuned for a better result.
