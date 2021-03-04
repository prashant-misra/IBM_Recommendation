## Recommendations_with_IBM_Project
Udacity Data Scientist Nanodegree Project

This project is part of the Data Science Nanodegree by Udacity. It features an important collaboration with IBM, the provider of the dataset. The aim is to develop a recommendation engine and suggest new articles to the IBM Watson Community users.


# Table of Contents
1) Project Motivation
2) File Description
3) Code WorkFlow
4) Acknowledgements

# Project Motivation
In this Project, aim is to utilize interaction of users, similarity between users  and give recommendations for new articles to the users of IBM Watson Community

# File Descriptions
1) Recommendations_with_IBM.ipynb: This is the Jupyter Notebook with the actual Recommendation Code
2) Recommendations_with_IBM.html: This is the HTML version of the Notebook
3) data Folder: It contain the data we need for analysis before recommending new article to a user.
    a.  articles_community.csv: It contain details of all the articles present in IBM Watson.
    b.  user-item-interactions: It contain data regarding interaction of user to articles. It contain data which articles is seen by which users.

# Code WorkFlow
Thw whole recommendation code in the notebook is divided into following parts:

# Exploratory Data Analysis
In this part we did some basic analysis od our data to understand it better before using it in making recommendations. This part did a brief analysis on unique features of our data, like Number of unique users, number of unique articles, most popular artcle etc.

# Rank Based Recommendations
This part is used to make recommendations to users based rank of the articles. Ranking of articles is done on the basis of higher interaction with a articles. This method is particularly useful in making recommendation for new user as no data is available for them

# User-User Based Collaborative Filtering
This part finds out the similarity among various users in the community and make recommendation based on articles seen by similar users.

# Matrix Factorization
This part finds out user-article interaction to find out the recommeendations. In this SVD is used on User-item matrix to fit our data on train data and then estimate articles for the test data.

# Acknowledgements
1) IBM Watson for the valuable data to analyze
2) Udacity for encouraging and helping in this project
