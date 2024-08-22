# Background
Every year me and a group of my friends make an NBA fantasy basketball league. I have always used the approach of just who I think will do good in the season when it comes to picking my players but what if there was a way to use machine learning to help me come up with players to pick. In this notebook I will go over my attempt to make a model that will help predict NBA player performance that will hopefully give me an edge for the next fantasy season.

In order to do this I will be scraping data from a website called basketball reference that has all the players stats for almost every season.

# Methods
I scraped web data from the website www.basketball-reference.com. I extracted the player names, ages, positions, season years, games played, as well as their averages for various stats in that season. I then used this data to make a fantasy value similar to the one used in the leagues that I play in which I then used to compare players. I then calculated this fantasy value for all the seasons I extracted data from and was able to get a line of best fit for each player which I then calculated the slope of to see where this player was trending which I used to help the model predict which players to pick.
