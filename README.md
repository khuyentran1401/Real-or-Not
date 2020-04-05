# About this Project
Kaggle competition to predict which Tweets are about real disasters and which ones are not

# Dataset
The dataset from this repository can be found in [Kaggle](https://www.kaggle.com/c/nlp-getting-started)
# Methods
* Data exploration
* Preprocessing
* Model training
  * Tf-Idf (with Select K-Best)
  * Tf-Idf with N-gram (Characters and Words)
  * Binary Vectorizer (with SelectKbest)
  * Word2Vec (with Twitter word vectors from Glove)
  * Combination of binary vectorizer and word2vec
  * Neural Network with PyTorch
  * Convolutional Neural Network (with w2v embedding)

# Result
Best f1 score is .8. Tf_Idf vectorizer and binary vectorizer perform better than other methods
 
| precision | recall | f1-score | support
------------ | ------------ | ------------- | ------------- | -------------
0 | 0.82 | 0.85 | 0.84 | 1762
1 | 0.79 | 0.75 | 0.7 | 1284

accuracy | 0.81 | 3046
macro avg | 0.81 | 0.80 | 0.80 | 3046
weighted avg | 0.81 | 0.81 | 0.81 | 3046
