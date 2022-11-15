# Natural-Language-Processing
> CS 6120 Natural Language Processing Assignments

## Assignment 1: Naive bayes
> Will use Sentiment Analysis using Naive Bayes algorithm to assess if a given review is positive or negative using the provided dataset.
- Sample same size of data
- Preprocess data
- Calculate logprior and loglikelihood for Naive Bayes algorithm
- Predict the review
- Calculate the Accuracy

```
Train accuracy: 98.19%
Test accuracy: 85.16%
```

## Assignment 2: Multinomial Naive Bayes and Neural Networks.
> Text classification of news groups using Multinomial Naive Bayes and Neural Networks using TF-IDF Vectorization.
- TF-IDF vectorization of dataset for Bag of Words 
- Multinomial Naive Bayes model fitting and prediction
- Vector visualisation
- Calculate accuracy
- Neural networks using Tensorflow keras
- L2 regulariser with drop out value of 0.5

> Multinomial Naive Bayes Metrics
```
F1 Score: 0.88
Accuracy: 88.80%
```

## Assignment 3: Word sense disambiguation.
> Implement n-gram language models, latent semantic analysis using Singular value decomposition (SVD), Bidirectional Long short-term memory (LSTM) over emotions dataset.
- Preprocessing of dataset
- TF-IDF vectorization of dataset for Bag of Words 
- SVD of dataset vectors
- N gram models: unigram, bigram, trigram
- Calculate perplexity for n-gram models
- LSTM using tensorflow keras
- Graphs for accuracy, loss, precision, recall
- Save files in pickle format

## Assignment 4: Expectation maximisation and clustering.
> Implement expectation-maximization to train a word-sense induction system, Heirarchical Clustering for Name Entity Tagging, Viterbi Algorithm based on Hidden Markov Model for Part-of-speech tagging.
- Preprocessing of dataset
- TF-IDF vectorization of dataset for Bag of Words 
- Implement EM algorithm
- Find accuracy of EM clustering
- Implement and plot AgglomerativeClustering, WordCloud, dendrogram
- Implement viterbi algorithm for Hidden Markov model
- Calculate Transition and Emission matrix
- Find Part of Speech taggeed from the trained data
