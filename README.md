# Movie-Genre-Prediction
The objective of this assignment is to get started with predictive Analytics with Apache Spark.
The goals of the assignment are to use Spark Libraries to implement an end to end Predictive
Analytics Pipeline and introduce you to the data science competition platform Kaggle.

# Part 1
- The objective of the assignment is to implement a movie genre prediction model using
Apache Spark
- The dataset provided to you contains information about movies.
- train.csv has movie summaries of around 31K movies along with their genres. You will
use this to train your predictive analytics model
- test.csv has just plot summaries. You will be predicting the genre of these movies
- The task of predicting the genre is essentially a multi-label classification problem. A
movie can have multiple genres associated with it. Your model should be able to predict
all the genre associated with the movie
- sample.csv is a sample submission file. This is the format in which you will upload the
predictions to the Kaggle website. The format of the submission file is movie_id (string),
predictions(string). The predictions are expected to be a string of 1’s and 0’s
corresponding to the presence and absence of a particular genre.
- The mapping of the genre to the string index is given by the mapping.csv. For example
presence of genre ‘Drama’ is indicated by a ‘1’ in the first position of the prediction string
and an absence of this genre is indicated by ‘0 in the first position.
- 20 Logistic Regression model were created ( one model for each genre) for this task.
- The accuracy was 98.17%

# Part 2

- Focussing on the summary of the movie, implement Term Frequency-Inverse Document
Frequency (TF-IDF) based feature engineering technique to improve the performance of
the model
- Similar to part 1, generated predictions and the accuracy was 98.43%

# Part 3

- The accuracy was further improved to 100% by Word2Vec feature engineering method. 

# Kaggle Leaderboard
- Link: https://www.kaggle.com/c/dic487-587/leaderboard
- Team: CSK
