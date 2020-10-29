#Wrangle and Analyze Data Project

## **Introduction**
This project is part of the Udacity Data Analyst Nanodegree Program. WeRateDogs is a popular Twitter page that posts photos of dogs, and rates them using a unique scale (where dogs typically achieve scores higher than a 10/10). It is more of an dog appreciation page and is not meant to be viewed as critique. As the account continues to gain popularity, it would be interesting to scrape Tweet data and see what kinds of posts typically gain the most momentum.

Therefore, throughout the project I gather, assess and clean data from the WeRateDogs account, and produce a few simple visualizations. The project is largely centered around wrangling the data, and places little emphasis on analysis.

## **Process and Data Sources**
The different processes (gathering, assessment, cleaning and analyzing) are labeled as separate sections throughout the project. For the gathering stage, I collect data from the twitter account by querying the Tweepy API (for each individual tweet's JSON), and also use data from CSV files provided. The assesment stage is both visual and programatic, and interesting findings are documented along the way. The cleaning stage goes through a "define, code, test" process for each individual issue.


## **Findings**
Missing data, incorrect data types, redundant columns that can be merged/melted and incorrect null items are some of the most significant issues I find within the dataset. After my extensive cleaning process, I concluded the project by analyzing data to answer three questions about the data. 

The questions and their answers are as follows:

Q1: **Is there a relationship between the amount of retweets and the amount of favorites a tweet gets?**


A: My scatterplot shows a positive correlation between the number of favorites and retweets a tweet gets. In fact, the tweet that had the most favorites (by over 20,000!) is also the tweet that got the most retweets (also by over 20,000!). 


Q2: **Is there a dog breed (based on type listed in prediction) that seems to be the most popular?**


A: A retweet count of over 2744, and a favorite count of more than 10,111 puts a tweet in the top quartile of all tweets in our dataframe. This data sets the bar for "popularity". Taking this into account, golden retrievers have the highest engagement (49 of the top retweeted and favorited dogs were golden retrievers), followed by labrador retrivers, pembrokes and chihuahuas.


Q3: **What rating is given most frequently by the account holder?**

A: Our distribution in the Histogram shows that the majority of ratings fall between 10 and 13.
