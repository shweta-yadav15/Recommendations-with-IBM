# Recommendations-with-IBM

## Motivation 

IBM has an online data science community where members can post tutorials, notebooks, articles, and datasets. For this project I will be analyzing the interactions that users have with articles on the IBM Watson Studio platform, and make recommendations to them about new articles they will like. 

## I. Exploratory Data Analysis

Before making recommendations of any kind, I need to explore the data. This section is about diving deep into exploration.

## II. Rank Based Recommendations

To get started in building recommendations, I will first find the most popular articles simply based on the most interactions. Since there are no ratings for any of the articles, it is easy to assume the articles with the most interactions are the most popular. These are then the articles I might recommend to new users (or anyone depending on what we know about them).

## III. User-User Based Collaborative Filtering

In order to build better recommendations for the users of IBM's platform, I could look at users that are similar in terms of the items they have interacted with. These items could then be recommended to the similar users. This would be a step in the right direction towards more personal recommendations for the users.

## IV. Matrix Factorization

Finally, a machine learning approach to building recommendations. Using the user-item interactions, I will build out a matrix decomposition. Using decomposition, I will get an idea of how well I can predict new articles an individual might interact with (spoiler alert - it isn't great). 
