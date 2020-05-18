### Project Overview

 As an Amazon data scientist and we have been asked to find out insights from the 'Amazon Fine Foods Review' data. Our aim is to do text classification using Deep Learning on the reviews. This dataset has various features but for this project we will only need the reviews(text) as training data. This is a supervised Learning task so we will use Score as the label, while training. We have to make a classification model which will rate the review at a scale from 1 to 5.


### Learnings from the project

 After completing this project I understood the basic pipeline of sentiment classification using Deep Learning. In this project I applied the following concepts:
1- TF-IDF vectorization
2- Word2Vec
3- LSTM using keras


### Approach taken to solve the problem

 The approach was first to understand the data set. It is a multinominial classification problem.
As text has to be coverted to vector form various tools available can be used to do this. TF-IDF Vectorization, Count Vectorization, Word2vec etc. 
After the conversion of text to numbers, the model is prepared, compiled and then fit. The train-test split is used to check the score and validate the model.


### Challenges faced

 Challenges faced were :
1- Word2vec training model - Visited basics of word2vec and understood the math behind it.
2- Local machine taking ample time to run code - Used Google Colab for running the code.
3- Concepts of RNN - Revisited achitecture of RNN to understand the basics.


