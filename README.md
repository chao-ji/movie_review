# movie_review

This dataset is from kaggle: kaggle.com/c/word2vec-nlp-tutorial

In this project we want to predict the sentiment (recommended or not) of movie reviews from IMDB. We need to extract features directly from the raw text of reviews. 

I found some interesting trend that probably nobody else has discovered: Extremely long and extremely short reviews tend to be more positive and medium length reviews.

In addition to the straightforward bag of words representation, I also used the word embedding and document embedding. The document embedding appeared to be slightly better in the binary classification task in terms of classification accuracy.

* [Part 1: Data Preparation](https://github.com/chao-ji/movie_review/blob/master/Part%201%20Data%20Preparation.ipynb)
* [Part 2: Bag of Words](https://github.com/chao-ji/movie_review/blob/master/Part%202%20Bag%20of%20Words.ipynb)
* [Part 3: Word2Vec](https://github.com/chao-ji/movie_review/blob/master/Part%203%20Word2Vec.ipynb)
* [Part 4: Doc2Vec](https://github.com/chao-ji/movie_review/blob/master/Part%204%20Doc2Vec.ipynb)


I also also tried pyLDAvis, a powerful tool for visualizing topic models: http://nbviewer.jupyter.org/github/chao-ji/movie_review/blob/master/Topic%20Model%20Viz%20Toy%20Example.ipynb
