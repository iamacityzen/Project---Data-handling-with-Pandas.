### Project Overview

 The Olympic Games, considered to be the world's foremost sports competition has more than 200 nations participating across the Summer and Winter Games alternating by occurring every four years but two years apart.

Throughout this project, we will explore the Olympics dataset(scraped from https://en.wikipedia.org/wiki/All-time_Olympic_Games_medal_table) , look at some interesting statistics and then try to find out which country is the King of Olympic Games.


### Learnings from the project

 After completing this project, we will have a better understanding of data handling with python(pandas). In this project, we will be applying the following concepts :

Dataframe operations,
Conditional statement and loops,
List operations,
Bar Plotting,
Mathematical operations.


### Approach taken to solve the problem

 1.  Loading the dataframe using 'pd.read_csv' and do renaming of column.
2.  Figure out which olympic event does a country perform better in. (used np.where() , value_counts())
3.  Finding out the list of best performing countries across all events.(created a user defined function, used nlargest(), set())
4.  Plotting the medal count of the top 10 countries for better visualisation using the list created in above task.(used isin(), bar plot)
5. Finding the best performing countries with respect to the ratio between gold medals won and total medals won.
6. Find the top country based on the total points achieved during the olympic games.
7. Plot a stacked bar plot of the medals won by the top country in olympic games



