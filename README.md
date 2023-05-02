# Simple_chatbot
This project is all about creating a friendly chatbot that answers huge number of questions covering several health topics using cosine similarity.
This journey would help you a lot to look more closely at some phases in NLP pipeline while working on most of text classification projects like Text preprocessing and representation and Model training and evaluation.
# Required libraries
+ Numpy
+ Pandas
+ re
+ NLTK
+ Sklearn
# About the dataset
Mental_Health_FAQ dataset is one of kaggle datasets that can be easily found (you can find it in the repo). It consists of 98 rows and 3 columns (ID, Questions, Answers).
# project implementation
+ import necessary libraries
+ load dataset
+ clean/preprocess data
+ vectorize text
+ train cosine similarity model
+ test model
# Why this project is noteworthy?
Implementation of this project applying whatever algorithm you prefer could be the stepping stone to the world of machine learning and NLP especially text generation and classification fields. Besides, the simplicity of this dataset will really motivate you to explore more challenges later.
# Text preprocessing vs Text representation(vectorization)
Text preprocessing involves transforming raw text data into a format that is suitable for analysis by a machine learning or NLP algorithm. This may involve techniques such as tokenization, stop word removal, lemmatization, lowercasing, and removing special characters and punctuation marks. The goal of text preprocessing is to clean and transform the text data so that it can be easily understood and analyzed by the algorithm.

On the other hand, text representation involves converting the preprocessed text data into a numerical format that can be used as input to machine learning or NLP algorithms. This typically involves representing the text data as vectors of numerical features, which can be used to train machine learning models or to perform similarity analysis between different pieces of text. One of the most common text representation techniques is term frequency-inverse document frequency (TF-IDF) models.
# You can findout more in
[NLP pipeline](https://www.analyticsvidhya.com/blog/2022/06/an-end-to-end-guide-on-nlp-pipeline/#:~:text=NLP%20Pipeline%20is%20a%20set,and%20Pipeline%20is%20non%2Dlinear.)
