# Recommendations-with-IBM

# Table of Contents<a name="Table of Contents"></a>

1. [Introduction](#introduction)
2. [File Descriptions](#files)
3. [Project](#project)


# Introduction<a name="introduction"></a>
In this project I analyze the interactions that users have with articles on the IBM Watson Studio platform, and make recommendations to them about new articles I think they will like.


# File Description<a name="files"></a>
* Recommendations_with_IBM.ipynb: Jupyter notebook containing main implementation and analysis.
* Recommendations_with_IBM.html: A copy of Recommendations_with_IBM.ipynb in html format.
* data/user-item-interactions.csv: Csv file with user-item interactions.
* data/articles_community.csv: Csv file with indexed items.


# Project<a name=“project”></a>
My project is divided into the following tasks

I. Exploratory Data Analysis
Visualising and creating descriptive statistics about the distribution of articles a user interacts within the dataset.

II. Rank Based Recommendations
Two functions to get n top articles names and n top articles ids.

III. User-User Based Collaborative Filtering 
Identifying users that are similar in terms of the items they have interacted with. 

IV. Matrix Factorization 
Using matrix factorization to make article recommendations to the users on the IBM Watson Studio platform
