# About this Project
Kaggle competition to predict which Tweets are about real disasters and which ones are not

# Dataset
The dataset from this repository can be found in [Google](https://www.google.com) - _Google | Youtube | Gmail | Maps | PlayStore | GoogleDrive_

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
  
