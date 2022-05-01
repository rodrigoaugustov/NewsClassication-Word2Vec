# Analytics News Classification

This project goal is to build a ML Model that can correct classify Analytics related News. We have a curated dataset with news headlines.


First we do the text processing, cleaning the data, removing stopwords, stemming, etc. To help with that task, I`ve build a class with all logic, that can be re-used on futures projects.

Next step, is create a embedding to represent each news headline. For that I've choosed to use the Word2Vec model to vectorize the words and then we use the TF-IDF score to weight the sum of word's vectors.

Later, is where we build the ML Model, here I show how to try differents models and visualize the outputs.

After choose a model, we apply an optmization technique to try improve the performance.

And finnaly we save the model using Pickle.

The next steps should be build a microservice to consume this model via REST API.
