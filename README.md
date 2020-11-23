# Recommendations with IBM
Recommendation engine with Watson Studio data from IBM, a part of Data Science Nanodegree by Udacity.

## Introduction
For this project you will analyze the interactions that users have with articles on the IBM Watson Studio platform, and make recommendations to user 

## Resource used
- Python
- Pandas
- Numpy
- Matplotlib
- Pickle

## File descriptions
-	Recommendations_with_IBM.ipynb: Jupyter notebook containing main implementation and analysis.
-	Recommendations_with_IBM.html: A copy of Recommendations_with_IBM.ipynb in html format.
-	data/user-item-interactions.csv: Csv file with user-item interactions.
-	data/articles_community.csv: Csv file with Articles details.

## Tasks
The project is divided into the following tasks.

I. Exploratory Data Analysis
Before making recommendations of any kind, I will need to explore the data I am working for the project.  

II. Rank Based Recommendations
To get started in building recommendations, I will first find the most popular articles simply based on the most interactions. Since there are no ratings for any of the articles, it is easy to assume the articles with the most interactions are the most popular. These are then the articles we might recommend to new users.

III. User-User Based Collaborative Filtering
In order to build better recommendations for the users of IBM's platform, I could look at users that are similar in terms of the items they have interacted with. These items could then be recommended to the similar users. This would be a step in the right direction towards more personal recommendations for the users.

IV. Matrix Factorization
Finally, I will complete a machine learning approach to building recommendations. Using the user-item interactions, I will build out a matrix decomposition. Using the decomposition, I get an idea of how well I can predict new articles an individual might interact with user and finally discuss which methods I might use moving forward, and how you might test how well your recommendations are working for engaging users.

## Acknowledgements
-	Github
-	Stackoverflow
-	Youtube

 
