# Wordometry
Wordometry is a project that analyzes tweets using Natural Language Processing Techniques. The files in this repository display examples of topic modelling, sentiment analysis, and more using NLP modules such as Gensim, TextBlob, and NLTK as well as common Deep Learning modules like TensorFlow and Keras.
This repository also holds some training datasets used in testing the files. Note that some files are missing due to the fact that GitHub cannot hold files larger than 25 MB.
Model analyzers can be summarized to have the following purposes:
- The Google News model analyzer loads a Word2Vec model trained using Google News and evaluates it using analogies to see how effective the model was trained.
- The Topic Modelling file trains a Latent Dirichlet Allocation (LDA) statistical model to determine groups of words that best summarize the topics of each tweet.
- The Sentiment Analysis determines the sentiment of a file in multiple ways as follows: 1) Using TextBlob's sentiment built-in method and 2) Creating a Doc2Vec model to translate tweets of words to a vector and then training a dataset of document word vectors with labelled sentiment data using a Deep Neural Network and 3) Using NLTK's implementation of the VADER sentiment dataset as a built-in method.
