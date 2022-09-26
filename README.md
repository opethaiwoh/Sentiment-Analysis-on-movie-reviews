# Performing-sentimental-Analysis-on-amazon-and-yelp-dataset-reviews

Sentiment Analysis helps data scientists to analyze any kind of data i.e., Business, Politics, Social Media, etc., For example, the IMDb dataset "movie_data.csv" file contains 25,000 highly polar ‘positive’ (12500) and ‘negative’ (12500) IMDB movie reviews (label negative review as ‘0’ and positive review as ‘1’).
Similarly, “amazon_data.txt” and “yelp_data.txt” contain 1000 labeled negative review as ‘0’ and positive review as ‘1’

##  Steps performed

a) Read all the above data files (.csv and .txt) in python Pandas DataFrame.

\\ For each dataset, I made 70% as training and 30% as test sets.

b) By using both CountVectorizer and TfidfVectorizer separately of the sklearn library, I performed the Logistic regression classification in the IMDb dataset
and evaluated the accuracies in the test set.

c) Classified the Amazon dataset using Logistic Regression and Neural Network (two hidden layers) and compare the performances and show the confusion matrices.

d) Generated classification model for the Yelp dataset with K-NN algorithms.

e) Fit and test the model for different values for K (from 1 to 5) using a for loop and record and plot the KNN’s testing accuracy in a variable (scores).

e) Generated prediction for the following reviews based Logistic regression classifier in Amazon dataset:

Review1 = "SUPERB, I AM IN LOVE IN THIS PHONE"
Review 2 = "Do not purchase this product. My cell phone blast when I switched the charger"
