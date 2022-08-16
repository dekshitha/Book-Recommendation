# Book-Recommendation
Book Recommendation System - Machine Learning Project


A recommendation engine is a class of machine learning which offers relevant suggestions to the customer. The recommendation system today are so powerful that they can handle the new customers too who has visited the site for the first time. A recommendation system is usually built using three techniques which are content-based 
filtering, collaborative filtering and a combination of both. 

This project uses Content based filtering methods based on the description of an item and the user’s preferred choices. K-Nearest Neighbors is incorporated to find similar books in terms of Language, Author and rating and build the recommender system. It is one of the simplest Machine Learning algorithms based on Supervised Learning technique. This algorithm assumes the similarity between the new case/data and the available cases and put the new case into the category that is most similar to the available categories. It stores all the available data and classifies a new data point based on the similarity. This means when new data appears then it can be easily classified into a well suite category. It does not learn from the training set immediately instead it stores the dataset and at the time of classification, it performs an action on the dataset. At the training phase, it just stores the dataset and when it gets new data, then it classifies that data into a category that is much similar to the new data.

Moreover, this project uses certain libraries for data exploration, in order to get highly rated books, best-selling Authors and many more. It plots the bar graphs to  get better insights about the features of the dataset. Finally, it trains the model and user’s choice of a particular book is passed. It returns 10 other similar books and hence recommender system is built.
