# NLP-Project---Yelp-Dataset

This project was developed as a part of the Python for Data Science and Machine Learning Bootcamp

In this NLP project we will classify Yelp Reviews into 1 star or 5 star categories based off the text content in the reviews.

We will use the Yelp Review Data Set from Kaggle.

First, we use CountVectorizer to make a bag of words and use Multinomial Naive Bayes to classify text content.
Then, we will make a pipeline with CountVectorizer, TF-IDF method to assign importance to certain words, and use Multinomial Naive Baye as a classifier. 
The same steps will be done with Random Forest Classifier.
The final pipeline performs the same steps without TF_IDF method. 

The performance of these models evaluated using precision, recall and F1-score metrics. 
