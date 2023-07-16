# Prediction of Toxic_tweets
This project has a collection of Tweets. Its labelled as Toxic - 1, Non toxic - 0. Applying the NLP methods to predict the toxicity of the tweets.
# Here are the steps on how to predict the toxicity of tweets using NLP methods:

Download the dataset from the Kaggle competition.
here is the link for dataset : https://www.kaggle.com/datasets/ashwiniyer176/toxic-tweets-dataset

After downloading the dataset, import all the required libraries
Convert the CSV file to a Pandas DataFrame.
Clean the text data by removing stop words, punctuation, and other unwanted characters.
Convert the text data to bag-of-words or TF-IDF features.
Train a decision tree classifier, random forest classifier, naive Bayes classifier, K-nearest neighbors classifier, and support vector machine classifier on the features.
Evaluate the performance of each classifier using precision, recall, F1-score, confusion matrix, and ROC-AUC curve.

Source code of this project will load the dataset, clean the text data, create bag-of-words features, train a decision tree classifier, random forest classifier, naive Bayes classifier, K-nearest neighbors classifier, and support vector machine classifier on the features, and evaluate the performance of each classifier.

We can run this code on your computer by installing the necessary Python libraries and running the code in a Python interpreter.

The output of the code will show the accuracy of each classifier. The accuracy is the percentage of tweets that the classifier correctly classified as toxic or non-toxic.

We can also calculate other metrics, such as precision, recall, and F1-score, to get a more detailed understanding of the performance of each classifier.

The confusion matrix will show us how many tweets each classifier correctly classified as toxic or non-toxic, and how many tweets it misclassified.

The ROC-AUC curve will show us the trade-off between the classifier's true positive rate and false positive rate.

By analyzing these metrics, we can choose the classifier that is best suited for our needs.
