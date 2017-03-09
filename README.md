# movie_review

![wordcloud](https://github.com/chao-ji/movie_review/blob/master/wordcloud.png)
![cluster](https://github.com/chao-ji/movie_review/blob/master/cluster.png)

This dataset is from kaggle: kaggle.com/c/word2vec-nlp-tutorial

This is a **real world** dataset that contains 25000 movie reviews from IMDB with highly polarized sentiment, together with 50000 unlabeled movie reviews. Th goal is to predict the sentiment class (positive or negative) of movie reviews based on features extracted from the text.

In this work, I applied a wide range of techniques for feature extraction and feature engineering (e.g. bag of words, word and document embedding, LSA), in the supervised (binary document classification) and unsupervised (clustering, topic modeling) machine learning tasks. I end up with a few novel discoveries (some are surprising while some are expected): extremely long or short reviews tend to be more positive than medium-length reviews; the topic composition of all reviews have a similar structure (general terms and specific terms).  

* [Part 1: Data Preparation](https://github.com/chao-ji/movie_review/blob/master/Part%201%20Data%20Preparation.ipynb)
* [Part 2: Bag of Words](https://github.com/chao-ji/movie_review/blob/master/Part%202%20Bag%20of%20Words.ipynb)
* [Part 3: Word2Vec](https://github.com/chao-ji/movie_review/blob/master/Part%203%20Word2Vec.ipynb)
* [Part 4: Doc2Vec](https://github.com/chao-ji/movie_review/blob/master/Part%204%20Doc2Vec.ipynb)
* [Part 5: Misc (Wordcloud, Clustering, Topic Modeling)](https://github.com/chao-ji/movie_review/blob/master/Part%205%20Misc%20(Wordcloud%2C%20Clustering%2C%20Topic%20Modeling).ipynb)
